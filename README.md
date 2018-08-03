# Cortoscript language support in Atom
Adds syntax highlighting for cortoscript in Atom.

## About
CortoScript is an object notation designed for supporting unsupervised M2M communication. CortoScript supports types, identifiers, units, context (hierarchies), relationships and time as first class citizens, which allows for communication between (sub)systems that is less ambiguous.

CortoScript example:

```
Drone my_drone = {lat: 37deg, long: 122deg, altitude: 30ft, speed: 20mph} {
    Rotor rotor_1 = {rpm: 4000rpm}
    Rotor rotor_2 = {rpm: 4000rpm}
}
```

For a full description of the language, see the CortoScript specification:
https://www.corto.io/doc/cortoscript.html

## Cortoscript repositories
The following repositories contain documentation and a reference implementation of cortoscript:

Cortoscript specification:
https://github.com/cortoproject/script-spec

Cortoscript grammar & generated parser:
https://github.com/cortoproject/script-parser

Cortoscript AST:
https://github.com/cortoproject/script-ast

Utility to print AST to console:
https://github.com/cortoproject/script-ast-print

Declare objects from AST in corto runtime:
https://github.com/cortoproject/script-declare
