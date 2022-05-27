# Nim Developer Tooling

### IDE Support

- [ ] Nim LSP
- [ ] VSCode
- [ ] Emacs
- [ ] Vim

## Profiling



## Test Code Coverage

yes


## Linter

- [ ] differentiate between main and foreign packages
- [ ] provides a means to interactively and automatically fix problems
- [ ] can be extended with custom lint checks and solutions


## API Change Checker

Backwards compatibility is important. A tool that can detect when a public
API changes would be very helpful.

The types of changes that could be detected are:
- [ ] symbol is removed
- [ ] symbol is added
- [ ] enum is extended
- [ ] exception is added
- [ ] exception is removed


## Debugging

- [ ] GDB C demangling
- [ ] LLDB C demangling
- [ ] doesn't depend on Python (many Windows GDB installs lack its support)
- [ ] correct line info (stepping goes to the correct line)

