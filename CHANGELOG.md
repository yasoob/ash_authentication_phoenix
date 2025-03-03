# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](Https://conventionalcommits.org) for commit guidelines.

<!-- changelog -->

## [v1.8.4](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.8.3...v1.8.4) (2023-10-01)




### Improvements:

* optional support for routing to register & reset links (#281)

## [v1.8.3](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.8.2...v1.8.3) (2023-09-23)




### Bug Fixes:

* resettable is no longer a list

## [v1.8.2](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.8.1...v1.8.2) (2023-09-22)




### Bug Fixes:

* handle change from ash_authentication where resettable is no lonâ¦ (#279)

## [v1.8.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.8.0...v1.8.1) (2023-09-18)




### Improvements:

* submit form in-line when sign_in_tokens_enabled (#274)

* submit form in-line when sign_in_tokens_enabled

## [v1.8.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.7.3...v1.8.0) (2023-09-14)




### Features:

* change `ash_authentication_live_session` to use `assign_new` (#270)

## [v1.7.3](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.7.2...v1.7.3) (2023-08-09)




### Bug Fixes:

* Overrides in reset route (#250)

## [v1.7.2](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.7.1...v1.7.2) (2023-04-16)




### Improvements:

* Add OIDC and generic "lock" icons.

## [v1.7.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.7.0...v1.7.1) (2023-04-12)




### Bug Fixes:

* backwards compat with sign_in_tokens_enabled?

## [v1.7.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.6...v1.7.0) (2023-04-06)




### Features:

* support new sign in tokens feature on password strategy (#176)

## [v1.6.6](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.5...v1.6.6) (2023-03-31)




### Bug Fixes:

* better behavior when password registration disabled

* only show register page if register is enabled

* resolve issues w/ assigning socket & test helper flash

## [v1.6.5](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.4...v1.6.5) (2023-03-26)




### Bug Fixes:

* better behavior when password registration disabled

* only show register page if register is enabled

* resolve issues w/ assigning socket & test helper flash

## [v1.6.4](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.3...v1.6.4) (2023-03-14)




### Bug Fixes:

* always set `tenant` session

## [v1.6.3](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.2...v1.6.3) (2023-03-13)




### Bug Fixes:

* always set `tenant` session

## [v1.6.2](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.1...v1.6.2) (2023-03-06)




### Bug Fixes:

* add `phoenix_view` to dependencies. (#153)

## [v1.6.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.6.0...v1.6.1) (2023-03-01)




### Improvements:

* allow folks to disable togglers by setting their text to `nil`.

## [v1.6.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.5.1...v1.6.0) (2023-02-27)




### Features:

* Allow on_mount for reset_routes for browser testing (#139)

## [v1.5.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.5.0...v1.5.1) (2023-02-24)




### Improvements:

* configurable otp app (#135)

## [v1.5.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.8...v1.5.0) (2023-02-12)




### Features:

* MagicLink: Add the UI for requesting a magic link. (#121)

## [v1.4.8](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.7...v1.4.8) (2023-02-07)




### Improvements:

* Autofocus identity field in password component (#105)

## [v1.4.7](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.6...v1.4.7) (2023-01-30)




### Improvements:

* ensure horizontal rules get a unique id (#99)

## [v1.4.6](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.5...v1.4.6) (2023-01-29)




### Improvements:

* improve default theme on dark mode. (#87)

* Add override introspection and tidy up docs.

## [v1.4.5](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.4...v1.4.5) (2023-01-26)




### Improvements:

* remove readme contents, add tutorial (#81)

## [v1.4.4](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.3...v1.4.4) (2023-01-19)




### Improvements:

* make `ash_authentication_live_session` support opts (#74)

## [v1.4.3](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.2...v1.4.3) (2023-01-18)




### Improvements:

* remove spark doc index (#63)

## [v1.4.2](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.1...v1.4.2) (2023-01-13)




### Bug Fixes:

* set ash_authentication? context on forms (#56)

## [v1.4.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.4.0...v1.4.1) (2023-01-12)




### Improvements:

* Add Github icon. (#55)

## [v1.4.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.3.1...v1.4.0) (2023-01-12)




### Features:

* LiveSession: Add `ash_authentication_live_session` macro to router. (#54)

## [v1.3.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.3.0...v1.3.1) (2023-01-10)




### Bug Fixes:

* deps: Loosen version constraints on deps.

## [v1.3.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.2.0...v1.3.0) (2022-12-16)




### Features:

* Add Auth0 icon.

## [v1.2.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.1.0...v1.2.0) (2022-12-15)




### Features:

* PasswordReset: Add a generic password reset form (#37)

* PasswordReset: Add a generic password reset form

### Improvements:

* Input.submit: trim trailing "with password" from submit buttons.

## [v1.1.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.0.1...v1.1.0) (2022-12-15)




### Features:

* Overrides: Move overrides from application environment to the `sign_in_route` macro. (#36)

## [v1.0.1](https://github.com/team-alembic/ash_authentication_phoenix/compare/v1.0.0...v1.0.1) (2022-12-14)




### Improvements:

* Components.Banner: Allow image, text and hrefs to be disabled with `nil`. (#35)

## [v0.5.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v0.4.0...v0.5.0) (2022-11-14)




### Features:

* OAuth2: Add OAuth2 link component. (#12)

## [v0.4.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v0.3.0...v0.4.0) (2022-11-10)




### Features:

* Confirmation: Add confirmation support.

## [v0.3.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v0.2.0...v0.3.0) (2022-11-03)




### Features:

* PasswordReset: Add password reset support to the UI. (#10)

## [v0.2.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v0.1.0...v0.2.0) (2022-10-28)




### Features:

* UI refresh. (#3)

## [v0.1.0](https://github.com/team-alembic/ash_authentication_phoenix/compare/v0.1.0...v0.1.0) (2022-10-25)




### Features:

* Add support for PasswordAuthentication.
