# dbvis-database-profiles
Additional XML database profiles for DbVisualizer

## About
This repository is dedicated for additional database profiles, which are not shipped with DbVisualizer.
This repository could also be used to extend existing database profiles, which are shipped with DbVisualizer.

## Howto write and import profiles
Each DbVisualizer release is shipped with some common, well-known databases with specific features by specific profiles, which can be found under ./resources/profiles of DbVis' installation directory. Other databases are supported by a generic profile, which uses common JDBC instruction sets only. Additional profiles can by written in XML language und published in this directory. DbVis will scan this directory at each startup and provide the new profiles in the profile list. New databases can then be switched from generic profile to a specific profile, offering much more features. For more details please visit the "Database Profiles" section of DbVis' User Guide. (http://confluence.dbvis.com/display/UG92/Database+Profiles)

## Rules of contribution
Commited profiles are open source.
Every profile should be written and commented in a separate directory under this repository.
Each profile should have a correspondent .md file, where documentation is done (feature list, known bugs, wishlist).
All files should have UTF-8 encoding and UNIX line endings.

## Copyright
Open Source
