# @benchsdk/client

## 0.3.0

### Minor Changes

- 1769324: Add participant helpers to the public API: the `BaseParticipant` type plus `selectParticipants()` (filter by `--provider` names) and `filterParticipantsByEnv()` (split participants by whether their `requiredEnvVars` are set).

## 0.2.1

### Patch Changes

- 9f16e68: Initial publication of the `@benchsdk/client` npm package, consolidated out of the `computesdk` monorepo (formerly `@computesdk/bench`). Same public API surface (`createBenchmarkClient`, `defineStep`/`defineTask`/`defineWorker`/`defineBench`, `BenchmarkReporter`, `createSystemMetricsCollector`); only the source repository and npm publish name changed.
