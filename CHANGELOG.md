<!-- markdownlint-disable MD024 -->

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Version 0.25.0 - 2026-03-30

### Added

- Toast to notify results for custom actions by @rusanpas in [PR #971](https://github.com/aminalaee/sqladmin/pull/971)
- ModelView.search_auto_submit option for list search by @Airumian in [PR #1003](https://github.com/aminalaee/sqladmin/pull/1003)
- Switch style for checkbox and fixed related bug by @maxim-f1 in [PR #975](https://github.com/aminalaee/sqladmin/pull/975)
- Template hooks to all filters for customizable UIs (dropdowns, sliders, etc.) by @fd-oncodna in [PR #970](https://github.com/aminalaee/sqladmin/pull/970)
- Extra blocks for templates allowing customization by @birddeveloper in [PR #952](https://github.com/aminalaee/sqladmin/pull/952)
- Support filtering Date and Datetime fields with "less than" and "greater than" operations by @caarmen in [PR #1010](https://github.com/aminalaee/sqladmin/pull/1010)

### Fixed

- Handling SQLAlchemy UUID fields correctly by @mmzeynalli in [PR #14](https://github.com/mmzeynalli/sqladmin-ng/pull/14)
- First exposed function is identity of view by @mmzeynalli in [PR #15](https://github.com/mmzeynalli/sqladmin-ng/pull/15)
- Showing exceptions happened during delete in list page by @mmzeynalli in [PR #13](https://github.com/mmzeynalli/sqladmin-ng/pull/13)
- Hiding "Save and continue editing" button in create page, if can_edit is `False` by @mmzeynalli in [PR #13](https://github.com/mmzeynalli/sqladmin-ng/pull/13)

### Changes

- Save values types as is if possible while JSON export
 by @DenisDudnik in [PR #865](https://github.com/aminalaee/sqladmin/pull/865)

- **Full Changelog**: [0.24.0...0.25.0](https://github.com/mmzeynalli/sqladmin/compare/0.24.0...0.25.0)

## Version 0.24.0 - 2026-03-29

- Forked from sqladmin v0.23.0. This project continues development due to inactivity in the original repository.

### Added

- Added support for newer Starlette versions (>=0.50) by @mmzeynalli

## Version 0.23.0 - 2026-02-04

### Added

- Highlight applied filters with background and clear option by @danmysak in [PR #964](https://github.com/aminalaee/sqladmin/pull/964)
- Implemented optional pretty CSV export by @TimofeiN in [PR #938](https://github.com/aminalaee/sqladmin/pull/938)

### Fixed

- fix: use children.extend in Menu.add by @wasinski in [PR #892](https://github.com/aminalaee/sqladmin/pull/892)
- fix: Support set-based relationships in list/detail views by @msukmanowsky in [PR #982](https://github.com/aminalaee/sqladmin/pull/982)
- Fixing an SQLAlchemy warning by @lorg in [PR #980](https://github.com/aminalaee/sqladmin/pull/980)
- Fix buttons width on details page by @MaximDementyev in [PR #978](https://github.com/aminalaee/sqladmin/pull/978)
- Migrate from hatchling to uv by @mmzeynalli in [PR #974](https://github.com/aminalaee/sqladmin/pull/974)
- Change PK column name to title in list/detail page by @wnowicki in [PR #977](https://github.com/aminalaee/sqladmin/pull/977)

### New Contributors

- @danmysak made their first contribution in [PR #964](https://github.com/aminalaee/sqladmin/pull/964)
- @TimofeiN made their first contribution in [PR #938](https://github.com/aminalaee/sqladmin/pull/938)
- @wasinski made their first contribution in [PR #892](https://github.com/aminalaee/sqladmin/pull/892)
- @msukmanowsky made their first contribution in [PR #982](https://github.com/aminalaee/sqladmin/pull/982)
- @MaximDementyev made their first contribution in [PR #978](https://github.com/aminalaee/sqladmin/pull/978)
- @mmzeynalli made their first contribution in [PR #974](https://github.com/aminalaee/sqladmin/pull/974)

Full Changelog: [0.22.0...0.23.0](https://github.com/aminalaee/sqladmin/compare/0.22.0...0.23.0)

## Version 0.22.0 - 2025-11-24

### Added

- Implement OperationColumnFilter to filter String, Numeric, and UUID Types by @chezou in [PR #945](https://github.com/aminalaee/sqladmin/pull/945)
- Support Python 3.14 by @aminalaee in [PR #963](https://github.com/aminalaee/sqladmin/pull/963)

### Fixed

- Fix filters inccorect records count by @birddevelper in [PR #954](https://github.com/aminalaee/sqladmin/pull/954)
- docs - update the example ColumnFilter by @proby-actvo in [PR #949](https://github.com/aminalaee/sqladmin/pull/949)
- Documentation improvements by @wnowicki in [PR #941](https://github.com/aminalaee/sqladmin/pull/941)
- Fix date and time type handling when used as primary key by @twoodwark in [PR #958](https://github.com/aminalaee/sqladmin/pull/958)

- - **Full Changelog**: [0.21.0...0.22.0](https://github.com/aminalaee/sqladmin/compare/0.21.0...0.22.0)

## Version 0.21.0 - 2025-07-02

### Added

- Add `category_icon` by @sheldygg in [PR #848](https://github.com/aminalaee/sqladmin/pull/848)
- Add model convertors docs by @Vasiliy566 in [PR #883](https://github.com/aminalaee/sqladmin/pull/883)
- Allow custom response in authentication logout by @joschnitzbauer in [PR #914](https://github.com/aminalaee/sqladmin/pull/914)
- ModelView @expose decorator support by @foarsitter in [PR #881](https://github.com/aminalaee/sqladmin/pull/881)
- Adding the ability to add filters to model views by @lorg in [PR #906](https://github.com/aminalaee/sqladmin/pull/906)
- Details page query by @wray27 in [PR #929](https://github.com/aminalaee/sqladmin/pull/929)
- export csv/json in `utf-8` by @alserious in [PR #911](https://github.com/aminalaee/sqladmin/pull/911)
- Indicate Required Fields with a Red Asterisk by @maxim-f1 in [PR #880](https://github.com/aminalaee/sqladmin/pull/880)

### Fixed

- Update hatch command in CONTRIBUTING.md by @foarsitter in [PR #882](https://github.com/aminalaee/sqladmin/pull/882)
- fix: CategoryMenu is_active logic by @retromechs in [PR #920](https://github.com/aminalaee/sqladmin/pull/920)
- Doc update - Related model name by @wnowicki in [PR #917](https://github.com/aminalaee/sqladmin/pull/917)
- docs: Added model context, fixed syntax by @sreyemnayr in [PR #930](https://github.com/aminalaee/sqladmin/pull/930)

- **Full Changelog**: [0.20.1...0.21.0](https://github.com/aminalaee/sqladmin/compare/0.20.1...0.21.0)

## Version 0.20.1 - 2024-10-28

### Fixed

- Fix export json related model by @Vasiliy566 in [PR #837](https://github.com/aminalaee/sqladmin/pull/837)
- Fix JSON export trailing comma by @jbrendel in [PR #843](https://github.com/aminalaee/sqladmin/pull/843)

- **Full Changelog**: [0.20.0...0.20.1](https://github.com/aminalaee/sqladmin/compare/0.20.0...0.20.1)

## Version 0.20.0 - 2024-10-17

### Added

- add json export format. by @Vasiliy566 in [PR #829](https://github.com/aminalaee/sqladmin/pull/829)

### Fixed

- clamp page if it exceeds the maximum page by @alex-lambdaloopers in [PR #814](https://github.com/aminalaee/sqladmin/pull/814)

## New Contributors

- @Vasiliy566 made their first contribution in [PR #829](https://github.com/aminalaee/sqladmin/pull/829)

- **Full Changelog**: [0.19.0...0.20.0](https://github.com/aminalaee/sqladmin/compare/0.19.0...0.20.0)

## Version 0.19.0 - 2024-09-06

### Added

- Add favicon by @sheldygg in [PR #787](https://github.com/aminalaee/sqladmin/pull/787)
- Add tabler icons by @r-m-n in [PR #795](https://github.com/aminalaee/sqladmin/pull/795)
- feat: use favicon_url instead of logo_url for favicon by @alex-lambdaloopers in [PR #800](https://github.com/aminalaee/sqladmin/pull/800)
- Allow multiple ajax sorts and changes to result size by @mfriedy in [PR #805](https://github.com/aminalaee/sqladmin/pull/805)

### Fixed

- Fix column_property by @aminalaee in [PR #791](https://github.com/aminalaee/sqladmin/pull/791)
- Fix page number issue when changing page size by @numberbee7070 in [PR #782](https://github.com/aminalaee/sqladmin/pull/782)
- Document update to resolve DeprecationWarning from Starlette (#809) by @a4rcvv in [PR #810](https://github.com/aminalaee/sqladmin/pull/810)
- Bug fix: unhandled exception during AjaxSelect load by @diskream in [PR #727](https://github.com/aminalaee/sqladmin/pull/727)

- **Full Changelog**: [0.18.0...0.19.0](https://github.com/aminalaee/sqladmin/compare/0.18.0...0.19.0)

## Version 0.18.0 - 2024-07-01

### Added

- Add `form_rules`, `form_create_rules`, `form_edit_rules` by @aminalaee in [PR #779](https://github.com/aminalaee/sqladmin/pull/779)
- Add more docs for overriding default tempates by @jonocodes in [PR #769](https://github.com/aminalaee/sqladmin/pull/769)

### Fixed

- Fix edit_form_query documentation example by @lukeclimen in [PR #777](https://github.com/aminalaee/sqladmin/pull/777)

- **Full Changelog**: [0.17.0...0.18.0](https://github.com/aminalaee/sqladmin/compare/0.17.0...0.18.0)

## Version 0.17.0 - 2024-05-13

### Added

- Add field description to Create/Edit templates by @ngaranko in [PR #722](https://github.com/aminalaee/sqladmin/pull/722)
- Add edit_form_query method by @lukeclimen in [PR #745](https://github.com/aminalaee/sqladmin/pull/745)
- Validate page and pageSize query parameters by @BhuwanPandey in [PR #752](https://github.com/aminalaee/sqladmin/pull/752)

### Fixed

- Hide save and add another button from edit.html if can_create is False by @MaximZemskov in [PR #742](https://github.com/aminalaee/sqladmin/pull/742)
- Fix list page sort symbol by @aminalaee in [PR #744](https://github.com/aminalaee/sqladmin/pull/744)
- Move template files from `templates` to `templates/sqladmin` by @hasansezertasan in [PR #748](https://github.com/aminalaee/sqladmin/pull/748)
- Fix `form_args` default by @aminalaee in [PR #756](https://github.com/aminalaee/sqladmin/pull/756)
- Fix getting column python type by @aminalaee in [PR #757](https://github.com/aminalaee/sqladmin/pull/757)
- Fix File and Image fields checkbox and input by @aminalaee in [PR #761](https://github.com/aminalaee/sqladmin/pull/761)
- Switch relationship loading to selectionload by @aminalaee in [PR #758](https://github.com/aminalaee/sqladmin/pull/758)
- Fix DELETE call query params by @aminalaee in [PR #763](https://github.com/aminalaee/sqladmin/pull/763)

- **Full Changelog**: [0.16.1...0.17.0](https://github.com/aminalaee/sqladmin/compare/0.16.1...0.17.0)

## Version 0.16.1 - 2024-02-20

### Fixed

- Re-add http_exception handler to Admin class in [PR #694](https://github.com/aminalaee/sqladmin/pull/694)
- Move non-field-specific errors to top of edit and create forms in [PR #707](https://github.com/aminalaee/sqladmin/pull/707)
- Fix sort by model attribute in [PR #713](https://github.com/aminalaee/sqladmin/pull/713)
- Fix Category not respecting is_visible and is_accessible in [PR #698](https://github.com/aminalaee/sqladmin/pull/698)

- **Full Changelog**: [0.16.0...0.16.1](https://github.com/aminalaee/sqladmin/compare/0.16.0...0.16.1)

## Version 0.16.0 - 2023-11-14

### Added

- Switch to async templates by @aminalaee in [PR #652](https://github.com/aminalaee/sqladmin/pull/652)
- Allow using related model fields in list/details page by @aminalaee in [PR #653](https://github.com/aminalaee/sqladmin/pull/653)
- Allow sort by related model field by @aminalaee in [PR #654](https://github.com/aminalaee/sqladmin/pull/654)
- Add search by related model field by @aminalaee in [PR #655](https://github.com/aminalaee/sqladmin/pull/655)
- Expose request to model events by @holdmybeer1min in [PR #660](https://github.com/aminalaee/sqladmin/pull/660)

### Fixed

- Allow model columns to bear the same name as reserved wtforms.BaseForm attributes by @brouberol in [PR #658](https://github.com/aminalaee/sqladmin/pull/658)
- Change pk converter in routes by @aminalaee in [PR #666](https://github.com/aminalaee/sqladmin/pull/666)
- Fix multiple PK model containing boolean values by @ncarvajalc in [PR #670](https://github.com/aminalaee/sqladmin/pull/670)
- Fix brand icon is not showing by @WiraDKP in [PR #665](https://github.com/aminalaee/sqladmin/pull/665)

- **Full Changelog**: [0.15.2...0.16.0](https://github.com/aminalaee/sqladmin/compare/0.15.2...0.16.0)

## Version 0.15.1 - 2023-10-02

### Fixed

- Avoid populating Select2 input with existing option by @Toshakins in [PR #626](https://github.com/aminalaee/sqladmin/pull/626)
- Fix ItemMenu sort issue by @aminalaee in [PR #631](https://github.com/aminalaee/sqladmin/pull/631)

### Added

- Add customized sort query signature (#624) by @YarLikviD in [PR #625](https://github.com/aminalaee/sqladmin/pull/625)

- **Full Changelog**: [0.15.0...0.15.1](https://github.com/aminalaee/sqladmin/compare/0.15.0...0.15.1)

## Version 0.15.0 - 2023-09-19

### Breaking Changes

- Update AuthenticationBackend signature by @aminalaee in [PR #581](https://github.com/aminalaee/sqladmin/pull/581)
- Change signature of `list_query` and `count_query` by @aminalaee in [PR #610](https://github.com/aminalaee/sqladmin/pull/610)

### Added

- Search in list when typing by @anton-petrov in [PR #592](https://github.com/aminalaee/sqladmin/pull/592)
- Add `category` config by @aminalaee in [PR #616](https://github.com/aminalaee/sqladmin/pull/616)
- Switch to HTML time input for Time field by @aminalaee in [PR #595](https://github.com/aminalaee/sqladmin/pull/595)
- Add modal confirmation for bulk delete by @aminalaee in [PR #612](https://github.com/aminalaee/sqladmin/pull/612)

### Fixed

- Fix 'itsdangerous' import error when not using Authentication Backend by @GriceTurrble in [PR #597](https://github.com/aminalaee/sqladmin/pull/597)
- Fix docs: Cookbook, Using a request object by @s1beria21 in [PR #575](https://github.com/aminalaee/sqladmin/pull/575)
- Fix delete error no rows selected by @aminalaee in [PR #591](https://github.com/aminalaee/sqladmin/pull/591)
- Fix typing of Admin session_maker by @sheldygg in [PR #604](https://github.com/aminalaee/sqladmin/pull/604)
- Fix broken link in doc by @YannickLeRoux in [PR #620](https://github.com/aminalaee/sqladmin/pull/620)

- **Full Changelog**: [0.14.1...0.15.0](https://github.com/aminalaee/sqladmin/compare/0.14.1...0.15.0)

## Version 0.14.1 - 2023-08-08

### Fixed

- Fix Detail page to not use label to get value in [PR #570](https://github.com/aminalaee/sqladmin/pull/570)

- **Full Changelog**: [0.14.0...0.14.1](https://github.com/aminalaee/sqladmin/compare/0.14.0...0.14.1)

## Version 0.14.0 - 2023-08-02

### Added

- Pass request to model view methods by @rossmacarthur in [PR #547](https://github.com/aminalaee/sqladmin/pull/547)
- Set `sessionmaker` on `BaseAdmin` by @rossmacarthur in [PR #542](https://github.com/aminalaee/sqladmin/pull/542)
- Allow custom properties by @aminalaee in [PR #544](https://github.com/aminalaee/sqladmin/pull/544)
- Change signature of delete_model by @aminalaee in [PR #550](https://github.com/aminalaee/sqladmin/pull/550)
- Support SQLAlchemy sessionmaker in Admin by @aminalaee in [PR #565](https://github.com/aminalaee/sqladmin/pull/565)

### Fixed

- Fix `expose` and `action` Auth backend not called by @aminalaee in [PR #561](https://github.com/aminalaee/sqladmin/pull/561)

- **Full Changelog**: [0.13.0...0.14.0](https://github.com/aminalaee/sqladmin/compare/0.13.0...0.14.0)

## Version 0.13.0 - 2023-06-30

### Fixed

- Remove httpx from requirements by @agn-7 in [PR #520](https://github.com/aminalaee/sqladmin/pull/520)
- Fix issue when search query contains special characters by @uriyyo in [PR #523](https://github.com/aminalaee/sqladmin/pull/523)
- Fix Ajax UUID by @aminalaee in [PR #525](https://github.com/aminalaee/sqladmin/pull/525)
- Fix search pagination by @aminalaee in [PR #528](https://github.com/aminalaee/sqladmin/pull/528)
- Drop Python3.7 by @aminalaee in [PR #530](https://github.com/aminalaee/sqladmin/pull/530)
- Fix Enum in detail page by @aminalaee in [PR #531](https://github.com/aminalaee/sqladmin/pull/531)
- Add `unique()` to query related models by @florianabel in [PR #535](https://github.com/aminalaee/sqladmin/pull/535)
- Add PosrgreSQL JSONB type support by @uriyyo in [PR #533](https://github.com/aminalaee/sqladmin/pull/533)

- **Full Changelog**: [0.12.0...0.13.0](https://github.com/aminalaee/sqladmin/compare/0.12.0...0.13.0)

## Version 0.12.0 - 2023-06-13

### Added

- Support `sqlalchemy.sql.sqltypes.Uuid` by @dexter-dopping-ekco in [PR #501](https://github.com/aminalaee/sqladmin/pull/501)
- Implement multi pk support by @dexter-dopping-ekco in [PR #507](https://github.com/aminalaee/sqladmin/pull/507)
- Support special `__all__` keyword by @aminalaee in [PR #511](https://github.com/aminalaee/sqladmin/pull/511)
- use @login_required for custom actions and views by @aminalaee in [PR #513](https://github.com/aminalaee/sqladmin/pull/513)

### Fixed

- Each `ModelView` can now have actions with the same name/slug by @murrple-1 in [PR #503](https://github.com/aminalaee/sqladmin/pull/503)
- Fix count query in search page by @aminalaee in [PR #506](https://github.com/aminalaee/sqladmin/pull/506)

- **Full Changelog**: [0.11.0...0.12.0](https://github.com/aminalaee/sqladmin/compare/0.11.0...0.12.0)

## Version 0.11.0 - 2023-05-23

### Added

- Add ability to specify custom actions by @murrple-1 in [PR #486](https://github.com/aminalaee/sqladmin/pull/486)
- Add `ChoiceType` by @aminalaee in [PR #482](https://github.com/aminalaee/sqladmin/pull/482)
- Add sqlalchemy_fields URLType converter by @aminalaee in [PR #493](https://github.com/aminalaee/sqladmin/pull/493)
- Upgrade fontawesome by @aminalaee in [PR #481](https://github.com/aminalaee/sqladmin/pull/481)

- **Full Changelog**: [0.10.3...0.11.0](https://github.com/aminalaee/sqladmin/compare/0.10.3...0.11.0)

## Version 0.10.3 - 2023-04-21

### Fixed

- Fix ImageType converter by @aminalaee in [PR #471](https://github.com/aminalaee/sqladmin/pull/471)
- reset UploadFile seek after reading by @murrple-1 in [PR #473](https://github.com/aminalaee/sqladmin/pull/473)
- Fix unnecessary joins in details and edit page by @aminalaee in [PR #476](https://github.com/aminalaee/sqladmin/pull/476)

- **Full Changelog**: [0.10.2...0.10.3](https://github.com/aminalaee/sqladmin/compare/0.10.2...0.10.3)

## Version 0.10.2 - 2023-04-15

### Fixed

- Fix nullable string fields by @aminalaee in [PR #465](https://github.com/aminalaee/sqladmin/pull/465)
- Fix Multiselect field saving only one value by @nik-joseph in [PR #463](https://github.com/aminalaee/sqladmin/pull/463)

- **Full Changelog**: [0.10.1...0.10.2](https://github.com/aminalaee/sqladmin/compare/0.10.1...0.10.2)

## Version 0.10.1 - 2023-03-25

### Fixed

- Fix PK getters for related objects by @timoniq in [PR #449](https://github.com/aminalaee/sqladmin/pull/449)

- **Full Changelog**: [0.10.0...0.10.1](https://github.com/aminalaee/sqladmin/compare/0.10.0...0.10.1)

## Version 0.10.0 - 2023-03-15

### Breaking changes

- Change AuthenticationBackend `authenticate` signature to support OAuth in [PR #440](https://github.com/aminalaee/sqladmin/pull/440)

### Added

- Add File field in [PR #424](https://github.com/aminalaee/sqladmin/pull/424)
- Support SQLALchemy Interval type in [PR #438](https://github.com/aminalaee/sqladmin/pull/438)

### Fixed

- Fix docstrings by @linomp in [PR #434](https://github.com/aminalaee/sqladmin/pull/434)
- Update to work with Starlette URL type in url_for by @aminalaee in [PR #444](https://github.com/aminalaee/sqladmin/pull/444)
- Fix nullable Integers to accept zero value by @ovginkel in [PR #445](https://github.com/aminalaee/sqladmin/pull/445)

- **Full Changelog**: [0.9.0...0.10.0](https://github.com/aminalaee/sqladmin/compare/0.9.0...0.10.0)

## Version 0.9.0 - 2023-02-07

### Added

- Support SQLAlchemy v2 in [PR #411](https://github.com/aminalaee/sqladmin/pull/411)
- Support PostgreSQL arrays in [PR #414](https://github.com/aminalaee/sqladmin/pull/414)
- Add custom form converters in [PR #399](https://github.com/aminalaee/sqladmin/pull/399)
- Support SQLAlchemy composite types in [PR #421](https://github.com/aminalaee/sqladmin/pull/421)
- Add sqlalchemy_utils `PhoneNumberType`, `ColorType` and `ArrowType` in [PR #422](https://github.com/aminalaee/sqladmin/pull/422)

### Fixed

- Fix re-rendering create/edit page with existing data in [PR #385](https://github.com/aminalaee/sqladmin/pull/385)
- Fix exclude columns breaking order in [PR #407](https://github.com/aminalaee/sqladmin/pull/407)
- Fix control relationships in list page in [PR #409](https://github.com/aminalaee/sqladmin/pull/409)
- Fix asyncpg BigInt query in [PR #416](https://github.com/aminalaee/sqladmin/pull/416)

- **Full Changelog**: [0.8.0...0.9.0](https://github.com/aminalaee/sqladmin/compare/0.8.0...0.9.0)

## Version 0.8.0 - 2022-11-22

### Added

- Add `save_as` option by @aminalaee in [PR #377](https://github.com/aminalaee/sqladmin/pull/377)
- Add `save_as_continue` option by @aminalaee in [PR #379](https://github.com/aminalaee/sqladmin/pull/379)
- Add extra Save buttons for Create/Edit page by @aminalaee in [PR #373](https://github.com/aminalaee/sqladmin/pull/373)
- Display errors in alert for create/edit page by @aminalaee in [PR #382](https://github.com/aminalaee/sqladmin/pull/382)

### Fixed

- Fix `_url_for` methods ignoring root_path by @aminalaee in [PR #371](https://github.com/aminalaee/sqladmin/pull/371)
- Fix export to use `list_query` option by @villqrd in [PR #381](https://github.com/aminalaee/sqladmin/pull/381)

- **Full Changelog**: [0.7.0...0.8.0](https://github.com/aminalaee/sqladmin/compare/0.7.0...0.8.0)

## Version 0.7.0 - 2022-11-03

### Added

- Add `on_model_change` and `after_model_change` methods by @dima23113 in [PR #342](https://github.com/aminalaee/sqladmin/pull/342)
- Add `on_model_delete` and `after_model_delete` methods by @aminalaee in [PR #343](https://github.com/aminalaee/sqladmin/pull/343)

### Fixed

- Fix search by uuid column by @aminalaee in [PR #366](https://github.com/aminalaee/sqladmin/pull/366)
- Update tests after starlette upgrade by @aminalaee in [PR #344](https://github.com/aminalaee/sqladmin/pull/344)
- Remove hard-coded related model limit by @aminalaee in [PR #354](https://github.com/aminalaee/sqladmin/pull/354)
- Improve items list UI by @ischaojie in [PR #349](https://github.com/aminalaee/sqladmin/pull/349)
- Make navbar work on small screens by @aminalaee in [PR #362](https://github.com/aminalaee/sqladmin/pull/362)

### Internal

- Add mypy check with config no_implicit_optional by @ischaojie in [PR #360](https://github.com/aminalaee/sqladmin/pull/360)
- Support test-suite py311 by @ischaojie in [PR #365](https://github.com/aminalaee/sqladmin/pull/365)
- Add py.typed for the package to ship its typing information by @franciscorode in [PR #346](https://github.com/aminalaee/sqladmin/pull/346)

- **Full Changelog**: [0.6.1...0.7.0](https://github.com/aminalaee/sqladmin/compare/0.6.1...0.7.0)

## Version 0.6.1 - 2022-09-25

### Fixed

- Fix Boolean field for both nullable and non-nullable cases in [PR #336](https://github.com/aminalaee/sqladmin/pull/336)
- Fix Flatpickr not respecting readonly inputs in [PR #336](https://github.com/aminalaee/sqladmin/pull/336)
- Disable batch delete when can_delete permission is not provided in [PR #335](https://github.com/aminalaee/sqladmin/pull/335)

- **Full Changelog**: [0.6.0...0.6.1](https://github.com/aminalaee/sqladmin/compare/0.6.0...0.6.1)

## Version 0.6.0 - 2022-09-19

### Added

- Add bulk delete action by @aminalaee in [PR #317](https://github.com/aminalaee/sqladmin/pull/317)

### Fixed

- Handle null values when column is nullable by @aminalaee in [PR #323](https://github.com/aminalaee/sqladmin/pull/323)
- Switch Boolean field to select field by @aminalaee in [PR #321](https://github.com/aminalaee/sqladmin/pull/321)

### Internal

- Fix form_ajax_refs example in documentation by @GitBib in [PR #311](https://github.com/aminalaee/sqladmin/pull/311)
- Remove watch in mkdocstrings mkdocs's config by @ischaojie in [PR #306](https://github.com/aminalaee/sqladmin/pull/306)

- **Full Changelog**: [0.5.0...0.6.0](https://github.com/aminalaee/sqladmin/compare/0.5.0...0.6.0)

## Version 0.5.0 - 2022-09-06

### Added

- Add `remote_ajax_refs` in [PR #292](https://github.com/aminalaee/sqladmin/pull/292)

### Internal

- Avoid select query with ajax_form_refs in [PR #300](https://github.com/aminalaee/sqladmin/pull/300)
- Add docs for form_ajax_refs in [PR #302](https://github.com/aminalaee/sqladmin/pull/302)

- **Full Changelog**: [0.4.0...0.5.0](https://github.com/aminalaee/sqladmin/compare/0.4.0...0.5.0)

## Version 0.4.0 - 2022-08-31

### Added

- Add Date and DateTime pickers using Fatpickr in [PR #288](https://github.com/aminalaee/sqladmin/pull/288)
- Add Time picker using Flatpickr in [PR #294](https://github.com/aminalaee/sqladmin/pull/294)

### Internal

- Remove MomentJS in [PR #289](https://github.com/aminalaee/sqladmin/pull/289)
- Remove Select2 widgets in [PR #293](https://github.com/aminalaee/sqladmin/pull/293)

- **Full Changelog**: [0.3.0...0.4.0](https://github.com/aminalaee/sqladmin/compare/0.3.0...0.4.0)

## Version 0.3.0 - 2022-08-26

### Added

- Add `AuthenticationBackend` in [PR #277](https://github.com/aminalaee/sqladmin/pull/277)
- Update Authentication docs in [PR #278](https://github.com/aminalaee/sqladmin/pull/278)

- **Full Changelog**: [0.2.1...0.3.0](https://github.com/aminalaee/sqladmin/compare/0.2.1...0.3.0)

## Version 0.2.1 - 2022-08-04

### Fixed

- Fix `middlewares` and `ENGINE_TYPE` types in [PR #266](https://github.com/aminalaee/sqladmin/pull/266)
- Fix middlewares not being applied in [PR #267](https://github.com/aminalaee/sqladmin/pull/267) and [PR #271](https://github.com/aminalaee/sqladmin/pull/271)

- **Full Changelog**: [0.2.0...0.2.1](https://github.com/aminalaee/sqladmin/compare/0.2.0...0.2.1)

## Version 0.2.0 - 2022-08-01

### Added

- Add `list_query`, `count_query` and `search_query` options in [PR #243](https://github.com/aminalaee/sqladmin/pull/243)
- Add `BaseView` for custom pages in [PR #244](https://github.com/aminalaee/sqladmin/pull/244)
- Add `expose` for BaseView in [PR #251](https://github.com/aminalaee/sqladmin/pull/251)
- Rename `ModelAdmin` to `ModelView` in [PR #249](https://github.com/aminalaee/sqladmin/pull/249)

- **Full Changelog**: [0.1.12...0.2.0](https://github.com/aminalaee/sqladmin/compare/0.1.12...0.2.0)

## Version 0.1.12 - 2022-07-13

### Added

- Add time field converter by @ischaojie in [PR #214](https://github.com/aminalaee/sqladmin/pull/214)
- Add Edit button for "Details" page by @cuamckuu in [PR #222](https://github.com/aminalaee/sqladmin/pull/222)
- Add column_type_formatters by @aminalaee in [PR #239](https://github.com/aminalaee/sqladmin/pull/239)

### Fixed

- Fix lazy subuqery in list query by @aminalaee in [PR #212](https://github.com/aminalaee/sqladmin/pull/212)
- Fix missing browser tab title by @cuamckuu in [PR #229](https://github.com/aminalaee/sqladmin/pull/229)
- Remove sourceMappingURL in JS files by @aminalaee in [PR #231](https://github.com/aminalaee/sqladmin/pull/231)

- **Full Changelog**: [0.1.11...0.1.12](https://github.com/aminalaee/sqladmin/compare/0.1.11...0.1.12)

## Version 0.1.11 - 2022-06-23

### Added

- Add `form_include_pk` option by @aminalaee in [PR #207](https://github.com/aminalaee/sqladmin/pull/207)

### Fixed

- Fix handling of iterable fields by @okapies in [PR #204](https://github.com/aminalaee/sqladmin/pull/204)
- Fix nullable Enum form by @aminalaee in [PR #205](https://github.com/aminalaee/sqladmin/pull/205)

- **Full Changelog**: [0.1.10...0.1.11](https://github.com/aminalaee/sqladmin/compare/0.1.10...0.1.11)

## Version 0.1.10 - 2022-06-21

### Added

- Add support for one-to-one relationship by @okapies in [PR #182](https://github.com/aminalaee/sqladmin/pull/182)
- Add support for UUIDType from sqlalchemy_utils by @okapies in [PR #183](https://github.com/aminalaee/sqladmin/pull/183)
- Add sqlalchemy_utils URL, Currency and  Timezone by @aminalaee in [PR #185](https://github.com/aminalaee/sqladmin/pull/185)
- Add form_widget_args by @aminalaee in [PR #188](https://github.com/aminalaee/sqladmin/pull/188)
- Add column_default_sort by @aminalaee in [PR #191](https://github.com/aminalaee/sqladmin/pull/191)

### Fixed

- Fix link relationship to details page when null by @aminalaee in [PR #174](https://github.com/aminalaee/sqladmin/pull/174)
- docs: fix typos by @pgrimaud in [PR #161](https://github.com/aminalaee/sqladmin/pull/161)
- Allow QuerySelectField override object_list with form_args by @aminalaee in [PR #171](https://github.com/aminalaee/sqladmin/pull/171)
- Fix form fields order when specifying columns by @okapies in [PR #184](https://github.com/aminalaee/sqladmin/pull/184)
- Fix ModelConverter when `impl` is not callable by @aminalaee in [PR #186](https://github.com/aminalaee/sqladmin/pull/186)

- **Full Changelog**: [0.1.9...0.1.10](https://github.com/aminalaee/sqladmin/compare/0.1.9...0.1.10)

## Version 0.1.9 - 2022-05-27

### Added

- Add column_formatters by @skarrok in [PR #140](https://github.com/aminalaee/sqladmin/pull/140)
- Add column_formatters_detail by @aminalaee in [PR #141](https://github.com/aminalaee/sqladmin/pull/141)
- Handling for sqlalchemy_utils EmailType and IPAddressType by @colin99d in [PR #150](https://github.com/aminalaee/sqladmin/pull/150)
- Link relationships to detail page by @aminalaee in [PR #153](https://github.com/aminalaee/sqladmin/pull/153)

### Fixed

- Function signature typing, and renames by @dwreeves in [PR #116](https://github.com/aminalaee/sqladmin/pull/116)
- Fix SQLModel UUID type by @aminalaee in [PR #158](https://github.com/aminalaee/sqladmin/pull/158)

- **Full Changelog**: [0.1.8...0.1.9](https://github.com/aminalaee/sqladmin/compare/0.1.8...0.1.9)

## Version 0.1.8 - 2022-04-19

### Added

- Add csv export support by @dwreeves in [PR #101](https://github.com/aminalaee/sqladmin/pull/101)
- Expose Starlette middlewares and debug to the Admin by @tr11 in [PR #114](https://github.com/aminalaee/sqladmin/pull/114)

### Fixed

- Fix Export unlimited rows by @aminalaee in [PR #107](https://github.com/aminalaee/sqladmin/pull/107)
- Add form and export options docs by @aminalaee in [PR #110](https://github.com/aminalaee/sqladmin/pull/110)
- fix docstring issues by adding an explicit handler by @dwreeves in [PR #106](https://github.com/aminalaee/sqladmin/pull/106)
- Fix get_model_attr with column labels by @aminalaee in [PR #128](https://github.com/aminalaee/sqladmin/pull/128)
- Delay call to `self.get_converter` to use `form_overrides` by @lovetoburnswhen in [PR #129](https://github.com/aminalaee/sqladmin/pull/129)

- **Full Changelog**: [0.1.7...0.1.8](https://github.com/aminalaee/sqladmin/compare/0.1.7...0.1.8)

## Version 0.1.7 - 2022-03-22

### Added

- Add SQLModel support by @aminalaee in PR #[94](https://github.com/aminalaee/sqladmin/pull/94)
- Add form-specific functionality to ModelAdmin by @dwreeves in PR #[97](https://github.com/aminalaee/sqladmin/pull/97)
- Add `UUID` field converter by @aminalaee in PR #[82](https://github.com/aminalaee/sqladmin/pull/82)
- Add PostgreSQL `INET` and `MACADDR` converters by @aminalaee in PR #[83](https://github.com/aminalaee/sqladmin/pull/83)

### Fixed

- Fix Boolean field checkbox UI by @aminalaee in PR #[88](https://github.com/aminalaee/sqladmin/pull/88)
- Fix PostgreSQL UUID PrimaryKey by @aminalaee in PR #[92](https://github.com/aminalaee/sqladmin/pull/92)
- Fix Source Code Link by @baurt in PR #[95](https://github.com/aminalaee/sqladmin/pull/95)

- **Full Changelog**: [0.1.6...0.1.7](https://github.com/aminalaee/sqladmin/compare/0.1.6...0.1.7)

## Version 0.1.6 - 2022-03-09

### Added

- FontAwesome6 icons in PR #[78](https://github.com/aminalaee/sqladmin/pull/78)
- Add `column_sortable_list` in PR #[65](https://github.com/aminalaee/sqladmin/pull/65)
- Add JSON column converters in PR #[74](https://github.com/aminalaee/sqladmin/pull/74)

### Fixed

- Fix URL search regex in PR #[67](https://github.com/aminalaee/sqladmin/pull/67)
- Fix Enum in Edit page in PR #[71](https://github.com/aminalaee/sqladmin/pull/71)

- **Full Changelog**: [0.1.5...0.1.6](https://github.com/aminalaee/sqladmin/compare/0.1.5...0.1.6)

## Version 0.1.5 - 2022-02-24

### Added

- Authentication in [PR #37](https://github.com/aminalaee/sqladmin/pull/37)
- Add Edit view page in [PR #60](https://github.com/aminalaee/sqladmin/pull/60)
- Add `column_searchable_list` in [PR #61](https://github.com/aminalaee/sqladmin/pull/61)

### Internal

- Cleanup DB queries in [PR #51](https://github.com/aminalaee/sqladmin/pull/54)

- **Full Changelog**: [0.1.4...0.1.5](https://github.com/aminalaee/sqladmin/compare/0.1.4...0.1.5)

## Version 0.1.4 - 2022-02-16

### Added

- Allow templates to be configured in [PR #52](https://github.com/aminalaee/sqladmin/pull/52)
- Add page size option links in [PR #34](https://github.com/aminalaee/sqladmin/pull/34)

### Fixed

- Improve pagination in [PR #36](https://github.com/aminalaee/sqladmin/pull/36)

### Internal

- Instantiate ModelAdmin internally to avoid class methods in [PR #31](https://github.com/aminalaee/sqladmin/pull/31)

- **Full Changelog**: [0.1.3...0.1.4](https://github.com/aminalaee/sqladmin/compare/0.1.3...0.1.4)

## Version 0.1.3 - 2022-01-24

### Added

- Add `title` and `logo` options in [PR #20](https://github.com/aminalaee/sqladmin/pull/20)
- Adding `order_by` to list pagination query in [PR #25](https://github.com/aminalaee/sqladmin/pull/25)
- Allow Relationship properties in list and detail views in [PR #22](https://github.com/aminalaee/sqladmin/pull/22)

- **Full Changelog**: [0.1.2...0.1.3](https://github.com/aminalaee/sqladmin/compare/0.1.2...0.1.3)
