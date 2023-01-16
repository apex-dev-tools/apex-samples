# Apex Test Samples

This directory contains a number of test samples as git modules for regression testing.

## Usage

It is recommended to checkout a specific tag. You can clone a version and the submodules in one command:

  ```sh
  git clone -b [latest-tag] --recurse-submodules [repo-url]
  ```

To update and init the submodules after empty clone or switching branches:

  ```sh
  git clone [repo-url]
  git checkout tags/v1.0.0
  git submodule update --init
  ```

## Contributing

To make a new release of the samples, submodules must be updated to latest remote commit:

  ```sh
  git submodule update --init --remote
  ```

To add a new sample, it must be nested in another directory so that supporting files (e.g. custom `sfdx-project.json`) or dependent submodules can be included.

  ```sh
  git submodule add [repo-url] [name]/[name]
  ```
