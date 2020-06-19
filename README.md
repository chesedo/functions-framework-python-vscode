# functions-framework-python VS Code debugging
Minimal VS Code setup needed for debugging using functions framework (python)

There are examples for both HTTP functions and background functions.

## Extensions
These examples require the [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) to be installed for VS Code.

Other helpful extensions are:
- [REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) for generating requests
- [Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring) to make docstrings easier
- [Spell Right](https://marketplace.visualstudio.com/items?itemName=ban.spellright) to check the spelling of said documentation

## Debugging
Open any of the example folders in VS Code - i.e. they need to be your root. A simple <kbd>F5</kbd> should start functions framework with the debugger attached to it. It should also stop at any breakpoints.