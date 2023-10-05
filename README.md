# Overview

Rekord is a multi-platform backup tool with **deduplication and asymmetric encryption**, with support for multiple storage back-ends including:

- Local filesystem
- S3 storage
- SFTP servers

It is currently alpha quality and **should not be used in production**, more documentation will come in the future.

# Source code

This repository does not contain the code of Rekord but only exists as a front. For pratical reasons, I've started using a single repository for all my projects in 2018 because it is easier to manage.

The source code is available here: https://github.com/Koromix/rygel/ (in the *src/rekord* subdirectory).

Monorepositories have two killer features for me:

- Cross-project refactoring
- Simplified dependency management

You can find a more detailed rationale here: https://danluu.com/monorepo/
