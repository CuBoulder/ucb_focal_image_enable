# CU Boulder Focal Image Enable

All notable changes to this project will be documented in this file.

Repo : [GitHub Repository](https://github.com/CuBoulder/ucb_focal_image_enable)

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

- ### Adds "Focal Image - Wide" style to Consumer
  Enables the consumer created on site-install to access both the "focal image square" and "focal image wide" image styles and provide them via JSON:API requests. Will be needed for blocks like the `Article Feature` where users will be able to choose which image style is applied to the article display in their dynamic block. 
  
  Testing: Consumer is found in Configuration/Web Services/Consumer
  
  Resolves #6 
  
  Related to: https://github.com/CuBoulder/tiamat-theme/issues/318
---

- ### Adds `CHANGELOG.MD` and workflows; updates `core_version_requirement` to indicate D10 compatibility
  Additionally uses "CU Boulder" package and adds additional supporting files to match our other custom modules. Resolves CuBoulder/ucb_focal_image_enable#4
---
