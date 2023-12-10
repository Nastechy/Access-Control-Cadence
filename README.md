#SomeContract Readme

This readme provides an explanation of the "SomeContract" smart contract, which is written in the Move programming language. It also includes comments about variable and function scopes within the contract.

Contract Overview
The "SomeContract" smart contract contains various elements, including a struct, a resource, and several functions. It showcases the use of different access modifiers to control the visibility and accessibility of contract components. Below is an overview of the key elements in this contract:

SomeStruct
SomeStruct is a struct defined within the contract, containing four variables and three functions.
The variables within SomeStruct are a, b, c, and d. They have different access modifiers and scopes, which are explained in the comments below.
The functions within SomeStruct include publicFunc, contractFunc, and privateFunc. These functions have various access modifiers and are callable from different areas.
SomeResource
SomeResource is a resource type defined within the contract, containing a single variable e and a function resourceFunc. The variable e has a specific access scope, and resourceFunc can be called from a specific area.
Functions
The contract defines three top-level functions:

createSomeResource: This function creates a new SomeResource resource and returns it.
questsAreFun: A simple function with a specific area for execution.
init: The constructor function initializes the contract and creates an instance of SomeStruct as testStruct.
Variable and Function Scopes
The comments at the end of the contract provide a breakdown of the variable and function scopes. Here's a summary:

Variables
a can be read and written from areas 1, 2, 3, and 4.
b can be read from areas 1, 2, 3, and 4, but can only be written from area 1.
c can be read from areas 1, 2, and 3, and written from area 1.
d can be read and written from area 1.
e can be read from areas 1, 2, 3, and 4, but can only be written from area 2.
Functions
publicFunc can be called from areas 1, 2, 3, and 4.
contractFunc can be called from areas 1, 2, and 3.
privateFunc can be called from area 1.
Areas
The comments also mention different areas within the contract:

Area 1: Refers to the main contract scope.
Area 2: Refers to the scope of SomeResource functions and variables.
Area 3: Represents a specific section or scope within functions.
Area 4: The main contract scope (same as Area 1).
These areas help understand where variables and functions can be accessed and utilized within the contract.

