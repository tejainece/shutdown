## 0.3.0

**Breaking changes**

The suggested way is to use `shutdown` prefix when using the package, methods were renamed accordingly:

  - `addShutdownHandler` -> `addHandler`
  - `registerDefaultProcessSignals` -> `triggerOnSigInt` (and similar ones)

## 0.2.0

- Initial version: basic priorities.
- OS signal hooks.
