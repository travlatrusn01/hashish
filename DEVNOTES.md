# Developers' Notes

## Warnings and alerts

#### Key Generator

- When users select the (optional) **Pattern** option, warn them with a message that says it will significantly reduce the amount of password attempts, and that it should only be used if they are sure that this is your password's pattern.
- When users select a certain password length, warn them by saying how long it **could** take based on usage statistics.

## Exceptions

#### Key Generator

- **PatternMissingCharType** => Your pattern does not contain a #{chartype}.
