# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)


## Unreleased as of Sprint 72 ending 2017-10-30

### Added
- Targeted refresh for pods using watches [(#54)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/54)
- Annotate successful images with details [(#41)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/41)

## Gaprindashvili Beta1

### Added
- Prometheus alerts [(#22)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/22)
- Container Template: Parse object_labels [(#25)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/25)
- Allows get_container_images=true, but instead of saving metadata on all images, save it only for images that have been mentioned by pods.
- Use the kubernetes options for Openshift [(#32)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/32)
- Add openshift persister and test also batch saver strategy [(#39)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/39)
- Run provider generator to sync changes from core [(#38)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/38)
- Openshift graph refresh [(#34)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/34)

### Removed
- Remove hawkular support for inventory collection [(#49)](https://github.com/ManageIQ/manageiq-providers-openshift/pull/49)