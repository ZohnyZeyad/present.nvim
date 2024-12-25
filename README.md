# `present.nvim`

This is a plugin for presenting markdown files.

# Features: Neovim Lua Execution

Can execute code in lua blocks, when you have them in a slide

```lua
print("Hello from Lua!")
```

# Features: Other Languages

Can execute code in Language blocks, when you have them in a slide.

You may need to configure this with `opts.executors`.
Currently it only supports Python and Javascript by default.

```python
print("Hello from Python!")
```

# Usage

```lua
require("present").start_presentation {}
```
Or use `:PresentStart` Command

Use `n`, and `p` to navigate markdown slides.
Use `X` to execute a code block in a slide.
Use `q` to close the presentation.
