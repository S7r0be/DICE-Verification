# DICE-Verification

Verification tool for the DICE project. The repository contains a server component and an Eclipse plugin suite.

## Components

- [Server](d-vert-server/): Python entry point, dependency requirements and Docker configuration.
- [Eclipse plugins](plugin/): Java/Maven plugin modules.
- [Documentation](docs/)
- [License](LICENSE)

## Suggested workflows

Validate the Python server and Java/Maven plugins in separate jobs after checking their supported runtime versions. Keep Redis and other integration services isolated. Review legacy dependencies before enabling builds with network access.

Build, security and runtime qualification have not been established by this documentation update.
