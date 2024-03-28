You can find these instructions on the [official web page](https://rekkord.org).

# Overview

Rekkord is a **multi-platform backup tool**, with the following features:

- *Write-only passwords / keys* (using asymmetic encryption)
- *Data deduplication* based on content-defined chunking
- *Local and remote storage back-ends*: local directory, S3 storage, SFTP servers

This software has not been stabilized yet and **must not be used as your primary backup** tool. You've been warned!

Use the following links for more information:

- Documentation: https://rekkord.org
- Changelog: https://github.com/Koromix/rygel/blob/master/src/rekkord/CHANGELOG.md

Up-to-date binaries are available here:

- [Windows](https://download.koromix.dev/windows/)
- [macOS](https://download.koromix.dev/macos/)
- [Linux (Debian)](https://rekkord.org/start#linux-debian)
- [Linux (RPM)](https://rekkord.org/start#linux-rpm)

# Source code

This repository does not contain the code of Rekkord but only exists as a front. For pratical reasons, I've started using a single repository for all my projects in 2018 because it is easier to manage.

The source code is available here: https://github.com/Koromix/rygel/ (in the *src/rekkord* subdirectory).

Monorepositories have two killer features for me:

- Cross-project refactoring
- Simplified dependency management

You can find a more detailed rationale here: https://danluu.com/monorepo/
