# parsons_dnd

Single-page drag & drop implementation of a Parsons Problem.

## Features :##
1. Touch events support. Works on touch screens on top of normal cursor drag n drop.
2. Toggle between instant feedback and button verification.
----
## How to use ##

- Save your code in the variable with the same name, split between blocks using `\sep`. Multiple line blocks use normal html convention with the `<br/>` tag.
    - Example:
        ```javascript
        var code = """
        first line of code;
        this block contains;<br/>
        multiple lines;\sep
        final block;
        """
- Add your disruptors in its respective variable. This uses the same approach as `code`
    - Example:
        ```javascript
        var disruptors = """
        block contains this<br/>
        lines multiple;\sep
        block final;
        """
- Toggle between instant feedback and button verification through the `useButton` boolean.

----

### Funcionalities ###
- [x] Dedicated variables for code and disruptors
- [x] Dedicated variable to switch between instant feedback and button verification
- [x] Support for "zoom touch" outside of list
- [ ] Indicator when a touch event is in progress
- [ ] Add extra mode without any verification (for Moodle or sth)
- [ ] Copy created code to clipboard
