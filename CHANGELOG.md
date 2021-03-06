# Version 2.0.0

## Features

* Added changelog file (#25)
* [Breaking changes] Changed navigation part of screen.json metadata (#18) see wiki: https://github.com/tesler-platform/tesler/wiki/Metadata.-Navigation.
  * Changed JSON contract in liquibase module and ui module
  * Remove deprecated delegation feature.
  * Changed archetype modules.
* [Breaking changes] Added ability to run a Spring Boot with 2 or more EntityManagerFactory (#22)
  * Replaced the user and department with an Long identifier on some core entities
  * Some classes now use collection of EntityManagers instead of one.
  * Added support of declare ChainedTransactionManager.

## Fixes

* Fixed typo in io.tesler.model.core.converter package bug (#24)
* Fixed ActionCancel, now adding action happens without AutoSaveBefore.

# Version 1.0.4

## Features

* Breadcrumbs hiding flag added (#17).

# Version 1.0.3

## Features

* Add autoSaveBefore flag on ActionDTO (#15).
* Added README.md and CONTRIBUTING.md (#9).
* Bump lombok and commons-lang3. Added Java 11 compatibility (#8).
* Added feature to use custom DB sequences in entities, which are inherited from BaseEntity (#7).

## Fixes

* Fixed event processing order (#11).




