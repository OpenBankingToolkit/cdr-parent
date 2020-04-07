[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

| |Current Status|
|---|---|
|Build|[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FOpenBankingToolkit%2Fcdr-standards-starter-parent%2Fbadge%3Fref%3Dmaster&style=flat)](https://actions-badge.atrox.dev/OpenBankingToolkit/cdr-standards-starter-parent/goto?ref=master)|
|Tag |[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/openbankingtoolkit/cdr-standards-starter-parent)](https://github.com/OpenBankingToolKit/cdr-standards-starter-parent/tags)|
|Release|[![GitHub release](https://img.shields.io/github/v/release/OpenBankingToolKit/cdr-standards-starter-parent?sort=semver)](https://github.com/OpenBankingToolKit/cdr-standards-starter-parent/releases)|
|Code coverage|[![codecov](https://codecov.io/gh/OpenBankingToolkit/cdr-standards-starter-parent/branch/master/graph/badge.svg)](https://codecov.io/gh/OpenBankingToolkit/cdr-standards-starter-parent)|
|License|![license](https://img.shields.io/github/license/ACRA/acra.svg)|

Consumer Data Right (CDR) standards parent maven pom
==========================================

Maven pom descriptor Parent of all maven common components in the Consumer Data Right project (CDR).

It contains all the dependencies, their specific version and remote repositories.

The idea is to avoid having each project importing a different version of a library.

By sharing the same parent, we can assure a certain consistency between the different CDR maven projects.

Consumer Data Right Standards: https://consumerdatastandardsaustralia.github.io/standards.

## Artifact
cdr-standards-parent

## Usage
```
<parent>
    <groupId>com.forgerock.cdr.standards</groupId>
    <artifactId>cdr-standards-starter-parent</artifactId>
    <version>${cdr-standards-starter-parent.version}</version>
    <relativePath /> <!-- lookup parent from repository -->
</parent>
```
