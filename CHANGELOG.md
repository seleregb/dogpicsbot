# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.5.3] - 2021-02-20

### Changed

- Fixed a regression bug in which Telegram supergrous were not being considered as groups, but as personal chats instead.

## [1.5.2] - 2021-01-23

### Changed

- Fixed a regression bug in which certain dog triggers were not matching as a prefix (e.g. "perro" was not being matched properly, but "perr" was).

## [1.5.1] - 2020-10-30

### Changed

- Fixed the way message words are compared to trigger words in order to reduce false positives. Contribution by [@german1608](https://github.com/german1608).
- Updated package dependencies, particularly to fix a security vulnerability by an old version of `cryptography`.

## [1.5.0] - 2020-10-10

### Added

- The bot is now also triggered by messages that might have a sad sentiment, and are replied to with a dog picture. Contribution by [@baspalinckx](https://github.com/baspalinckx)

## [1.4.2] - 2020-09-03

### Changed

- Reduced the amount of comparisons done while parsing each message by making sure only the radix of similar words is checked for appearance.

## [1.4.1] - 2020-08-23

### Changed

- Refactored use of the Random Fox API.
- Added support for two other dog trigger words (in Spanish).

## [1.4.0] - 2020-08-23

### Added

- Easter egg! The bot now supports _fox_ triggers and sends a fox image accordingly.

### Changed

- Added yet more support for dog / dog-related emoji.
- Relocated dog triggers for improved extensibility and readability.

## [1.3.1] - 2020-08-23

### Added

- The bot now randomly selects a "dog sound" (barking) phrase as the pics caption.
- A few more trigger words were added in order to automatically send a dog pic.

## [1.3.0] - 2020-01-27

### Added

- The bot is now able to detect and reply to certain dog breeds with a picture of that specific breed.

## [1.2.0] - 2020-01-19

### Added

- The bot is now able to detect and reply to dog-related stickers.

### Changed

- The bot now recognizes more trigger words, as well as dog-related emoji.
- Project dependencies have been updated.

## [1.1.0] - 2020-01-14

### Added

- The bot is now able to reply to certain trigger words in group chats, sending dog pictures.

## [1.0.2] - 2019-07-21

### Added

- [CHANGELOG.md](CHANGELOG.md) file to track changes between versions.
- List of planned features, soon to be developed, in [README.md](README.md) file.

### Removed

- Heroku config files (runtime.txt and Procfile)

## [1.0.1] - 2019-07-20

### Added

- [LICENSE](LICENSE) file.

### Fixed

- Medium-impact typo on the help message shown on bot startup or through the /help command.

## [1.0.0] - 2019-07-20

### Added

- Initial release of the Dog Pics Telegram bot.
