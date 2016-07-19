# JavaScript
## VS Code JavaScript Unit Test snippets 
-------------------
This extension contains code snippets for Unit Test use describe in JavaScript for [Vs Code][code] editor (supports both JavaScript and TypeScript).

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Import and export
| Trigger  | Content |
| -------: | ------- |
| `deb→`   | add describe `describe('{description}',()=>{});`|
| `ete→`   | add expect `expect({object}).toExist();` |
| `ene→`   | add expect `expect({object}).toNotExist()` |
| `etb→`   | add expect `expect({object}).toBe({value})` |
| `enb→`   | add expect `expect({object}).toNotBe({value})` |
| `etq→`   | add expect `expect({object}).toEqual({value})` |
| `enq→`   | add expect `expect({object}).toNotEqual({value})` |


[code]: https://code.visualstudio.com/
