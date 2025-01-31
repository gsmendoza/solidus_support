# Changelog

## [Unreleased](https://github.com/solidusio/solidus_support/tree/HEAD)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.8.1...HEAD)

**Closed issues:**

- Release 0.5.2  version [\#64](https://github.com/solidusio/solidus_support/issues/64)

**Merged pull requests:**

- Compatibility layer for the legacy/new event system [\#70](https://github.com/solidusio/solidus_support/pull/70) ([waiting-for-dev](https://github.com/waiting-for-dev))
- Fix dependency on the engines load order when adding paths [\#65](https://github.com/solidusio/solidus_support/pull/65) ([waiting-for-dev](https://github.com/waiting-for-dev))
- Remove support for Solidus \<= 2.3 [\#62](https://github.com/solidusio/solidus_support/pull/62) ([elia](https://github.com/elia))
- Update the changelog with the latest releases [\#61](https://github.com/solidusio/solidus_support/pull/61) ([elia](https://github.com/elia))

## [v0.8.1](https://github.com/solidusio/solidus_support/tree/v0.8.1) (2021-01-27)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.8.0...v0.8.1)

**Merged pull requests:**

- Fix combined\_first\_and\_last\_name\_in\_address version [\#59](https://github.com/solidusio/solidus_support/pull/59) ([kennyadsl](https://github.com/kennyadsl))

## [v0.8.0](https://github.com/solidusio/solidus_support/tree/v0.8.0) (2021-01-19)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.7.0...v0.8.0)

**Implemented enhancements:**

- Add a method to check if combined address name is being used  [\#58](https://github.com/solidusio/solidus_support/pull/58) ([kennyadsl](https://github.com/kennyadsl))

**Fixed bugs:**

- Fix project' specs [\#57](https://github.com/solidusio/solidus_support/pull/57) ([kennyadsl](https://github.com/kennyadsl))

## [v0.7.0](https://github.com/solidusio/solidus_support/tree/v0.7.0) (2020-10-28)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.6.0...v0.7.0)

**Closed issues:**

- Could we get a new release? [\#49](https://github.com/solidusio/solidus_support/issues/49)

**Merged pull requests:**

- Use `Spree::Event. activate_all_subscribers` when available [\#53](https://github.com/solidusio/solidus_support/pull/53) ([spaghetticode](https://github.com/spaghetticode))
- Support Rails 5.1.x [\#51](https://github.com/solidusio/solidus_support/pull/51) ([brchristian](https://github.com/brchristian))
- Remove redundant `solidus_core` dev dependency [\#50](https://github.com/solidusio/solidus_support/pull/50) ([brchristian](https://github.com/brchristian))

## [v0.6.0](https://github.com/solidusio/solidus_support/tree/v0.6.0) (2020-07-24)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.5.1...v0.6.0)

**Implemented enhancements:**

- Autoload Solidus Event subscribers from extensions [\#45](https://github.com/solidusio/solidus_support/pull/45) ([spaghetticode](https://github.com/spaghetticode))

**Fixed bugs:**

- Load event subscribers only when Spree::Event is available [\#47](https://github.com/solidusio/solidus_support/pull/47) ([spaghetticode](https://github.com/spaghetticode))

**Closed issues:**

- Namespace Conflicts [\#48](https://github.com/solidusio/solidus_support/issues/48)

**Merged pull requests:**

- Stop using SolidusSupport.solidus\_gem\_version [\#46](https://github.com/solidusio/solidus_support/pull/46) ([elia](https://github.com/elia))
- Add frontend/backend/api decorators to autoload path [\#44](https://github.com/solidusio/solidus_support/pull/44) ([kennyadsl](https://github.com/kennyadsl))

## [v0.5.1](https://github.com/solidusio/solidus_support/tree/v0.5.1) (2020-04-15)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.5.0...v0.5.1)

**Merged pull requests:**

- Push decorators to autoload path using config.autoload\_paths [\#43](https://github.com/solidusio/solidus_support/pull/43) ([kennyadsl](https://github.com/kennyadsl))

## [v0.5.0](https://github.com/solidusio/solidus_support/tree/v0.5.0) (2020-02-18)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.4.1...v0.5.0)

**Merged pull requests:**

- Load Solidus engine extension files automatically [\#42](https://github.com/solidusio/solidus_support/pull/42) ([aldesantis](https://github.com/aldesantis))
- Update solidus\_dev\_support [\#41](https://github.com/solidusio/solidus_support/pull/41) ([aldesantis](https://github.com/aldesantis))
- Replace manual cache checks w/ require\_dependency [\#39](https://github.com/solidusio/solidus_support/pull/39) ([elia](https://github.com/elia))
- Fixes isse when zeitwerk is not enabled [\#38](https://github.com/solidusio/solidus_support/pull/38) ([softr8](https://github.com/softr8))
- Deprecate SolidusSupport.solidus\_gem\_version [\#37](https://github.com/solidusio/solidus_support/pull/37) ([kennyadsl](https://github.com/kennyadsl))
- Spring cleaning [\#33](https://github.com/solidusio/solidus_support/pull/33) ([aldesantis](https://github.com/aldesantis))

## [v0.4.1](https://github.com/solidusio/solidus_support/tree/v0.4.1) (2020-01-16)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.4.0...v0.4.1)

**Closed issues:**

- Should use require\_dependency instead of require/load [\#34](https://github.com/solidusio/solidus_support/issues/34)
- Add a LICENSE [\#20](https://github.com/solidusio/solidus_support/issues/20)

## [v0.4.0](https://github.com/solidusio/solidus_support/tree/v0.4.0) (2019-12-16)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.3.2...v0.4.0)

**Closed issues:**

- Configure CircleCI [\#30](https://github.com/solidusio/solidus_support/issues/30)
- Models::SolidusGlobalize::Spree::TaxonomyDecorator \(NameError\) [\#26](https://github.com/solidusio/solidus_support/issues/26)

**Merged pull requests:**

- Fix issues with test runs [\#32](https://github.com/solidusio/solidus_support/pull/32) ([aldesantis](https://github.com/aldesantis))
- Add CircleCI configuration [\#31](https://github.com/solidusio/solidus_support/pull/31) ([aldesantis](https://github.com/aldesantis))
- Introduce solidus\_extension\_dev\_tools [\#29](https://github.com/solidusio/solidus_support/pull/29) ([aldesantis](https://github.com/aldesantis))
- Remove support for testing and extensions [\#28](https://github.com/solidusio/solidus_support/pull/28) ([MinasMazar](https://github.com/MinasMazar))
- Add SolidusSupport::EngineExtension::Decorators to load decorators [\#27](https://github.com/solidusio/solidus_support/pull/27) ([kennyadsl](https://github.com/kennyadsl))
- Add support for Codecov [\#24](https://github.com/solidusio/solidus_support/pull/24) ([aldesantis](https://github.com/aldesantis))

## [v0.3.2](https://github.com/solidusio/solidus_support/tree/v0.3.2) (2019-08-08)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.2.1...v0.3.2)

**Merged pull requests:**

- Add `capybara-screenshot` dependency [\#23](https://github.com/solidusio/solidus_support/pull/23) ([spaghetticode](https://github.com/spaghetticode))
- Do not reset spree preferences starting from v2.9 [\#22](https://github.com/solidusio/solidus_support/pull/22) ([kennyadsl](https://github.com/kennyadsl))
- Update Travis config [\#19](https://github.com/solidusio/solidus_support/pull/19) ([aitbw](https://github.com/aitbw))
- Override Capybara JS driver via `CAPYBARA_DRIVER` ENV variable [\#18](https://github.com/solidusio/solidus_support/pull/18) ([spaghetticode](https://github.com/spaghetticode))
- Migrate from Poltergeist to Headless Chrome [\#16](https://github.com/solidusio/solidus_support/pull/16) ([aitbw](https://github.com/aitbw))
- Remove running rubocop on rake task [\#14](https://github.com/solidusio/solidus_support/pull/14) ([kennyadsl](https://github.com/kennyadsl))
- Cleanup extension [\#13](https://github.com/solidusio/solidus_support/pull/13) ([kennyadsl](https://github.com/kennyadsl))
- Fix how we compare gem versions to determine new gateway code usage [\#12](https://github.com/solidusio/solidus_support/pull/12) ([kennyadsl](https://github.com/kennyadsl))
- Add payment method parent class [\#8](https://github.com/solidusio/solidus_support/pull/8) ([tvdeyen](https://github.com/tvdeyen))
- Improve gem documentation [\#7](https://github.com/solidusio/solidus_support/pull/7) ([kennyadsl](https://github.com/kennyadsl))

## [v0.2.1](https://github.com/solidusio/solidus_support/tree/v0.2.1) (2018-02-22)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.2.0...v0.2.1)

**Merged pull requests:**

- Ensure database cleaning is very last in each spec [\#9](https://github.com/solidusio/solidus_support/pull/9) ([jhawthorn](https://github.com/jhawthorn))

## [v0.2.0](https://github.com/solidusio/solidus_support/tree/v0.2.0) (2017-10-25)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.5...v0.2.0)

**Merged pull requests:**

- Rename FactoryBot [\#6](https://github.com/solidusio/solidus_support/pull/6) ([tvdeyen](https://github.com/tvdeyen))
- Remove unused files [\#5](https://github.com/solidusio/solidus_support/pull/5) ([tvdeyen](https://github.com/tvdeyen))

## [v0.1.5](https://github.com/solidusio/solidus_support/tree/v0.1.5) (2017-07-27)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.4...v0.1.5)

## [v0.1.4](https://github.com/solidusio/solidus_support/tree/v0.1.4) (2017-07-26)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.3...v0.1.4)

## [v0.1.3](https://github.com/solidusio/solidus_support/tree/v0.1.3) (2017-07-26)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.2...v0.1.3)

**Merged pull requests:**

- Add a basic spec\_helper for extensions to include [\#2](https://github.com/solidusio/solidus_support/pull/2) ([jhawthorn](https://github.com/jhawthorn))

## [v0.1.2](https://github.com/solidusio/solidus_support/tree/v0.1.2) (2017-07-24)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.1...v0.1.2)

**Merged pull requests:**

- Add SolidusSupport.payment\_source\_parent\_class [\#1](https://github.com/solidusio/solidus_support/pull/1) ([jordan-brough](https://github.com/jordan-brough))

## [v0.1.1](https://github.com/solidusio/solidus_support/tree/v0.1.1) (2017-05-03)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/v0.1.0...v0.1.1)

## [v0.1.0](https://github.com/solidusio/solidus_support/tree/v0.1.0) (2017-03-21)

[Full Changelog](https://github.com/solidusio/solidus_support/compare/b34d603b2b603e8799ce801913b577322bd39bdc...v0.1.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
