# Overview

Rekord is a **multi-platform backup tool**, with the following features:

- *Write-only passwords / keys* (using asymmetic encryption)
- *Data deduplication* based on content-defined chunking
- *Local and remote storage back-ends*: local directory, S3 storage, SFTP servers

This software has not been stabilized yet and **must not be used as your primary backup** tool. You've been warned!

Use the following links for more information:

- Documentation: https://koromix.dev/rekord
- Changelog: https://github.com/Koromix/rygel/blob/master/src/rekord/CHANGELOG.md
- Source code: https://github.com/Koromix/rygel/ (see below for an explanation)

# Source code

This repository does not contain the code of Rekord but only exists as a front. For pratical reasons, I've started using a single repository for all my projects in 2018 because it is easier to manage.

The source code is available here: https://github.com/Koromix/rygel/ (in the *src/rekord* subdirectory).

Monorepositories have two killer features for me:

- Cross-project refactoring
- Simplified dependency management

You can find a more detailed rationale here: https://danluu.com/monorepo/
