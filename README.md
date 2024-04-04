# SomeContract

## Description

This contract defines a `SomeContract` that contains a structure `SomeStruct` and a resource `SomeResource`.

## Structure

### SomeStruct

#### Variables

- `a` (String): Publicly settable variable.
- `b` (String): Public variable.
- `c` (String): Accessible only within the contract.
- `d` (String): Accessible only within the structure.

#### Functions

- `publicFunc()`: Public function.
- `contractFunc()`: Accessible only within the contract.
- `privateFunc()`: Accessible only within the structure.
- `structFunc()`: Public function within the structure.

### SomeResource

#### Variables

- `e` (Int): Public variable.

#### Functions

- `resourceFunc()`: Public function within the resource.

## Functions

- `createSomeResource()`: Creates a new instance of `SomeResource`.
- `questsAreFun()`: Function for handling quests.

## Initialization

- `init()`: Initializes the contract and sets initial values.
