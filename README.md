This config is meant to be used with F11 enabled all the time, which puts you on a custom zen mode experience in which you can only see:

- The full-width editor
- The status bar
- The breadcrumbs of the file that you are working on
- The tabs bar

## Required Extensions

- [VSCodeVim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [GitHub Copilot Chat](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot-chat)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Ayu Theme](https://marketplace.visualstudio.com/items?itemName=teabyii.ayu)

## Keybindings Summary

### Navigation

- `ctrl-h` / `ctrl-alt-left`: Move left
- `ctrl-l` / `ctrl-alt-right`: Move right
- `ctrl-k` / `ctrl-alt-up`: Move up
- `ctrl-j` / `ctrl-alt-down`: Move down
- `space ,`: Show all editors
- `space e`: Toggle sidebar & focus explorer
- `ctrl+space e`: Close sidebar and return to editor
- `space \`: Split editor
- `space -`: Split editor down
- `f11`: Toggle Zen Mode
- `ctrl-f11`: Toggle Full Screen

### Coding

- `space c a`: Code actions
- `space c r`: Rename symbol
- `space c s`: Go to symbol
- `space c f`: Find in file
- `space c shift-f`: Toggle search sidebar
- `ctrl+space c shift-f`: Toggle sidebar & focus on explorer
- `space b d`: Close active editor
- `space b o`: Close other editors
- `space b a`: Close all editors
- `space b l`: Next editor
- `space b h`: Previous editor
- `space space`: Quick open
- `;`: Show command palette
- `space g d`: Go to definition
- `space g r`: Go to references
- `space g i`: Go to implementation
- `space s g`: Find in files
- `ctrl-n`: Add selection to next find match
- `j` (Visual): Move line down
- `k` (Visual): Move line up
- `shift-j` (VisualLine): Move line down
- `shift-k` (VisualLine): Move line up

### File Explorer (These work when explorer is focused)

- `r`: Rename file
- `c`: Copy file
- `p`: Paste file
- `x`: Cut file
- `d`: Delete file
- `a`: New file
- `shift-a`: New folder
- `s`: Open to side
- `shift-s`: Split editor down, open & close others
- `enter`: Open/pass focus or expand folder

### Debug

- `space d a`: Start debug
- `space d t`: Stop debug
- `space d o`: Step over
- `space d b`: Toggle breakpoint
- `space d e`: Show debug hover
- `space d c`: Continue debug
- `ctrl+shift+delete`: Kill terminal

### Terminal

- `space t t`: Toggle terminal
- `ctrl+space t t`: Close terminal when terminal is active
- `space t n` / `ctrl+space t n`: New terminal
- `space t d` / `ctrl+space t d`: Kill terminal
- `space t j` / `ctrl+space t j`: Focus next terminal
- `space t k` / `ctrl+space t k`: Focus previous terminal
- `space t s` / `ctrl+space t s`: Split terminal

### Git

- `space g g`: Open/focus SCM panel
- `ctrl+space g g`: Toggle SCM sidebar
- `space g c`: Commit
- `space g p`: Push
- `space g shift+p`: Pull
- `space g s`: Stage
- `space g shift+s`: Sync
- `space g u`: Unstage
- `space g b`: Branch
- `space g o`: Checkout
- `space g f`: Fetch
- `space g m`: Merge
- `space g l`: View history

### AI / Copilot

- `space a a`: Open Copilot Chat
- `ctrl+space a a`: Close Copilot Chat panel when active
- `space a n` / `ctrl+space a n`: Open Copilot Chat with new Chat
- `space a i`: Inline chat
- `space a e`: Open edit session
- `space a c`: Generate code
- `space a f`: Fix code
- `space a x`: Explain code
- `space a d`: Generate docs
- `space a t`: Generate tests
