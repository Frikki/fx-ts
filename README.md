# fx-ts: Computational environments

fx-ts is a library for writing effectful functional programs in TypeScript.

Pure functions are easy to reason about and test because they aren't entangled with the environment in which they're called.  They always give the same answer for the same inputs.  But useful programs need to interact with their environment: databases, external services, configuration, etc.

The goal of fx-ts is to enable writing programs that interact with their environment _and_ that are easy to reason about and test.


