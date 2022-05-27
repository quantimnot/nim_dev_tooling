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


### Compiler Debugging

- [ ] trigger debug logging and breakpoints when desired:
  - [ ] package is processed
  - [ ] module is processed
  - [ ] source line is processed
  - [ ] symbol is processed

- [ ] easier bisection
  - [ ] committed list of broken commits
  - [ ] committed list of special build requirements
  - [ ] cache builds
  - [ ] handle special build requirements for commit ranges
  - [ ] handle csources

- [ ] GitHub bot that auto bisects issues

## See Also

- https://github.com/nim-lang/RFCs/issues/300

