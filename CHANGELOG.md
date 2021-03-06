# Change Log

All notable changes to the "aMi" extension will be documented in this file.

## [Unreleased]

- See [README](README.md)

## [0.5.1] 2020-07-xx

### Added

- Arrays and cell arrays drill down.

### Fixed

- Disabled exception and warning specific protocol. They are now treated as a
  normal breakpoint so that subsequent breakpoints do not erroneously show an
  exception status.
- Issue #51 no more splash at Matlab startup.

## [0.5.0] 2019-09-04

### Added

- Basic workspace explorer. Only scalars or char rows detailed; all others only
  display their class.

## [0.4.1] 2019-06-04

### Fixed

- Issue #44: Pointless "remote control" error message when starting Matlab.

## [0.4.0] 2019-05-10

### Added

- Add/remove stop on error/warning breakpoints.

### Fixed

- No more dangling Python process after detaching interactive debug session.

## [0.3.1] 2019-05-05

### Fixed

- Issue #33: Stack is returned in the right order.

## [0.3.0] 2019-05-05

### Added

- Attach/detach interactive debug session to Matlab.
- Add/remove breakpoints from editor.

## [0.2.0] 2019-04-07

### Added

- Execute code selection

## [0.1.1] 2019-04-06

### Updated

- Minor documentation edits.

## [0.1.0] 2019-04-06

### Added

- Run scripts from editor or file explorer.

## [0.0.0] 2019-04-01

### Added

- Matlab command window in a terminal.
