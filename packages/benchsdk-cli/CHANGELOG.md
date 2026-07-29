# @benchsdk/cli

## 0.1.1

### Patch Changes

- 1769324: Initial publication of `@benchsdk/cli`, the benchmark runner framework. Provides `LogBuffer`, `loggedStep`, `uploadWorkerLog`, and `defineBenchmark` for building self-contained benchmark scripts that report to the benchmarks platform via `@benchsdk/client`.
- 1769324: `runBenchmark()` now rejects with the exported `NoAvailableParticipantsError` (carrying the `skipped` participants and their missing env vars) instead of a plain `Error` when every participant is env-gated out, so callers can treat an unprovisioned provider as a skip rather than a failure.
- Updated dependencies [1769324]
  - @benchsdk/client@0.3.0
