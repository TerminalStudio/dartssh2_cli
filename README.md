This repo contains the source code for `dartssh` and `dartsftp` command line tools.

## Install

```sh
# Install the `dartssh` command.
dart pub global activate dartssh2_cli

# Then use `dartssh` as regular `ssh` command.
dartssh user@example.com

# Example: execute a command on remote host.
dartssh user@example.com ls -al

# Example: connect to a non-standard port.
dartssh user@example.com:<port>

# Transfer files via SFTP.
dartsftp user@example.com
```

> If the `dartssh` command can't be found after installation, you might need to [set up your path](https://dart.dev/tools/pub/cmd/pub-global#running-a-script-from-your-path).