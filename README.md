<a href="https://buymeacoffee.com/koromix" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

You can find these instructions on the [official web page](https://rekkord.org).

# Overview

Rekkord is a **multi-platform backup tool**, with the following features:

- Write-only passwords / keys (using asymmetric encryption)
- Data deduplication based on content-defined chunking
- Data compression with LZ4
- Local and remote storage back-ends: local directory, S3 storage, SFTP servers

> [!CAUTION]
> This software has not been stabilized yet and **must not be used as your primary backup** tool. You've been warned!

Use the following links for more information:

- Documentation: https://rekkord.org
- Download: https://rekkord.org/download
- Changelog: https://rekkord.org/changelog

# Source code

This repository does not contain the code of Rekkord but only exists as a front. For pratical reasons, I've started using a single repository for all my projects in 2018 because it is easier to manage.

The source code is available here: https://codeberg.org/Koromix/rygel/ (in the *src/rekkord* subdirectory).

Monorepositories have two killer features for me:

- Cross-project refactoring
- Simplified dependency management

You can find a more detailed rationale here: https://danluu.com/monorepo/
