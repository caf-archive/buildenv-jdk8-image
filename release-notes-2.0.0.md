#### Version Number
${version-number}

#### New Features
- Updated Maven to version [3.8.6](https://maven.apache.org/docs/3.8.6/release-notes.html).

#### Known Issues
- None

#### Breaking Changes
- **SCMOD-7700**: Stops the docker container if the execution of any of the startup scripts fail instead of ignoring it.
- **SCMOD-14638**: Docker image has been renamed from `opensuse-jdk-maven` to `buildenv-jdk8`.
