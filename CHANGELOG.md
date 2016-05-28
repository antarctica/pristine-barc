# BAS Base Project (Pristine) - BARC Flavour - Change log

All notable changes to this project will be documented in this file.
This role adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased][unreleased]

## 0.3.0 - 28/05/2016

### Removed - BREAKING!

* Files directory removed from testing provisioning as certificates sub-directory should not be included in BARC
flavours where TLS certificates are unexpected

### Added

* Extra context for variables in setup script
* Ansible compatibility information
* Ansible 2.0 support

### Fixed

* README white-spacing and formatting
* Header formatting in README, change log
* White space inconsistencies

### Changed

* Updating dynamic inventories to remove debug code and improve stability
* Ignoring Ansible retry files

### Removed

* README section of BARC non-system sources variable, which is not included in roles by default

## 0.2.0 - 06/04/2016

### Added

* Setup script to automate setting up new instances of this project template
* Template `README` and `CHANGELOG`, which were previously tracked as documentation appendices

### Fixed

* Wrong environment for Vagrant dynamic inventory
* Wrong variable for role description in meta file
* Wrong path to vagrant directory in test environment
* Syntax typo in CHANGELOG template

## 0.1.0 - 31/03/2016

### Added

* Initial version based on version 0.1.0 of the Pristine Base flavour
