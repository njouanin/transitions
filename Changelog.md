# Changelog

## 0.2.8 (August, 6, 2015)
- README improvements, added TOC, and typo fixes
- Condition checks now receive optional data
- Removed invasive basicConfig() call introduced with logging in 0.2.6

## 0.2.7 (July 27, 2015)
- Fixed import bug that prevented dependency installation at setup

## 0.2.6 (July 26, 2015)
- Added rudimentary logging for key transition and state change events
- Added generic before/after callbacks that apply to all state changes
- Ensured string type compatibility across Python 2 and 3

## 0.2.5 (May 4, 2015)
- Added ability to suppress invalid trigger calls
- Shorthand definition of transitions via lists

## 0.2.4 (March 11, 2015)
- Automatic detection of predefined state callbacks
- Fixed bug in automatic transition creation
- Added Changelog

## 0.2.3 (January 14, 2015)
- Added travis-ci support
- Cleaned up and PEP8fied code
- Added 'unless' argument to transitions that mirrors 'conditions'

## 0.2.2 (December 28, 2014)
- Python 2/3 compatibility
- Added automatic to_{state}() methods
- Added ability to easily add ordered transitions
