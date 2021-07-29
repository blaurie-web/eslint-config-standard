# eslint-config-standard

This is my eslint config. It is meant to help catch egregious errors that a
compiled language would catch. In general, you should be allowed to write the
code you want and need.

# Also exports:

@blaurie:eslint-config-standard/strict  -- Strict Setting is set to Error
@blaurie:eslint-config-standard/style   -- My style guide.


# Usage

In package.json, add a section with the options you want:

```json
"eslintConfig": {
    ... ,
    "extends": [
        "@blaurie/eslint-config-standard",
        "@blaurie/eslint-config-standard/style"
    ]
}
```