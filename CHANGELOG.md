# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.1] - 2021-09-27

### Changed
- Setup rspec-html-matchers and use it for complex components specs (#65)

### Fixed
- Fix errors methods in `BaseComponent` and `FieldComponent` (#71)

## [0.1.0] - 2021-09-16

### Added

- `FormBuilder`: add `.namespace` method to allow local lookup of components (#54)
- Add basic `ViewComponent::Form::Builder` that can be used in place of Rails' `ActionView::Helpers::FormBuilder` (#1)
- Add all standard FormBuilder helpers provided by Rails, implemented as ViewComponents (#4)
- Add a custom FormBuilder generator (#34)
- Add CHANGELOG (#50)
- Add CI (#2)

[Unreleased]: https://github.com/pantographe/view_component-form/compare/v0.1.1...HEAD
[0.1.1]: https://github.com/pantographe/view_component-form/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/pantographe/view_component-form/releases/tag/v0.1.0
