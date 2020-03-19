[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

| |Current Status|
|---|---|
|Build|[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2FOpenBankingToolkit%2Fcdr-parent%2Fbadge%3Fref%3Dmaster&style=flat)](https://actions-badge.atrox.dev/OpenBankingToolkit/cdr-parent/goto?ref=master)|
|Tag |[![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/openbankingtoolkit/cdr-standards-model)](https://github.com/OpenBankingToolKit/cdr-standards-model/tags)|
|Release|[![GitHub release](https://img.shields.io/github/v/release/OpenBankingToolKit/cdr-parent?sort=semver)](https://github.com/OpenBankingToolKit/cdr-parent/releases)|
|Code coverage|[![codecov](https://codecov.io/gh/OpenBankingToolkit/cdr-parent/branch/master/graph/badge.svg)](https://codecov.io/gh/OpenBankingToolkit/cdr-parent)|
|License|![license](https://img.shields.io/github/license/ACRA/acra.svg)|

Consumer Data Right (CDR) parent maven pom
==========================================

Maven pom descriptor Parent of all maven common components in the Consumer Data Right project (CDR).

It contains all the dependencies, their specific version and remote repositories.

The idea is to avoid having each project importing a different version of a library.

By sharing the same parent, we can assure a certain consistency between the different CDR maven projects.

Consumer Data Right Standards: https://consumerdatastandardsaustralia.github.io/standards.

## Artifact
cdr-parent

## Usage
```
<parent>
    <groupId>com.forgerock.cdr.standards</groupId>
    <artifactId>cdr-parent</artifactId>
    <version>1.0.0</version>
    <relativePath /> <!-- lookup parent from repository -->
</parent>
```
