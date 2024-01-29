# blueprints.vim

Interact with your local Sublayer Blueprints server to store code blueprints and
generate new variations.

## Installation

Requires a [Sublayer blueprints](https://github.com/sublayerapp/blueprints) server running locally on port 3000.

If using [pathogen.vim](https://github.com/tpope/vim-pathogen):

```
cd ~/.vim/bundle
git clone git://github.com/sublayerapp/blueprints.vim.git
```

## Usage

Make sure your blueprints server is running on http://localhost:3000

To store a chunk of code as a blueprint, highlight it, and while in visual mode use:
`leader-1`

To generate a variation on an existing blueprint, write a description of the
code you need, highlight it, and while in visual mode use:
`leader-0`
