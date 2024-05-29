Checker.ts

custom way to check and narrow variables in typescript

if value is present `Optional.of(value).ifPresent(it => do something` 

if value is not present then other value  `Optional.of(value).orElse(other value)`

map value if present `Optional.of(value).map(mapping function)`

throw trace if not present `Optional.of(value).orElseThrow(error | error message)` 