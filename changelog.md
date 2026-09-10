# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),

## 1.4
### Initial release

## 1.5
### Security
- Reject `filename` values containing `..` or directory separators so that a
  foreign table cannot read files outside `log_directory` (path traversal).
### Fixes
- Fix for compile against v18
