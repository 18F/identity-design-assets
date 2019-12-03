# Changelog
All notable changes to `design.login.gov` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.0] - 2019-12-16

The color palette now has a wider range of tokens so that it is more easy to identify the difference between elements on screens.

### Added

- Feature: Created more color tokens for extended palette: `Primary`, `Secondary`, `Ink`, and `Accent Cool`
- Feature: Defined state palette throughly by clarifying what color tokens could be used from extended palette: `Info`, `Error`, `Warning`, `Success`, and `Disabled`
    - Text: Added "State palette" section (five possible lightness grades) to differ itself from "Extended palette" section (seven possible lightness grades)

### Changed

- Heading
    - _Main palette_ heading to _Featured palette_
- Primary palette
    - Text: "Input Blue" to "Lightest Blue"
    - Text: "Light Blue" to "Lighter Blue"
    - Text: "Medium Blue" to "Light Blue"
    - Text: "Navy" to "Navy / Darker Blue"
    - Token: Create Darkest Blue / `.primary-darkest`
- Secondary palette
    - Text and `code`: Pink / `.secondary-light` to Lightest Red / `.secondary-lightest`
    - Token: Create Lighter Red / `.secondary-lighter`
    - Token: Create Light Red / `.secondary-light`
    - Token: Create Darkest Red / `.secondary-darkest`
- Ink
    - TBD
- Accent cool
    - Text and `code`: Light Teal / `.accent-cool-light` to Lightest Teal / `.accent-cool-lightest`
    - Token: Created Lighter Teal / `.accent-cool-lighter`
    - Token: Modified Light Teal / `.accent-cool-light` — Previously `#ecfcff`; now `#7BBFD6`
    - Token: Created Dark Teal / `.accent-cool-dark`
    - Token: Created Darker Teal / `.accent-cool-darker`
    - Token: Created Darkest Teal / `.accent-cool-darkest`
- Info
    - Created `.info-` classes
    - Added three lightness grades: `.info-lighter`, `.info-light`, ``.info-dark`, and `.info-darker`
- Error
    - Created `.error-` classes
    - Added two lightness grades: `.error-light` and `.error-darkest`
- Warning
    - Created `.warning-` classes
    - Added three lightness grades: `.warning-light`, `.warning-dark`, and `.warning-darkest`
- Success
    - Created `.success-` classes
    - Added one lightness grade: `.success-light`
- Disabled
    - Created `.disabled-` classes
    - Added two lightness grades: `.disabled-light` and `.disabled-dark`

### Removed