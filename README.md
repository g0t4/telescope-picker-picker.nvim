# telescope‑picker‑picker.nvim

List and use all pickers, not just builtins

```vim
:Telescope picker_picker
```

---

## Installation

### Lazy.nvim

```lua
{
    "g0t4/telescope-picker-picker.nvim",
    enabled = true,
    event = { "VeryLazy" },
    opts = {},
    config = function()
        -- not required, but makes it possible to do `:Telescope p<TAB>` and see it in list of choices
        require("telescope").load_extension("picker_picker")
    end,
}
```
