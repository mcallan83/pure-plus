# Pure-Plus (Pure Forked)

I created this fork of [Pure](https://github.com/sindresorhus/pure) to allow for custom colors to be used for each part of the Pure prompt. Typical use cases for changing the colors could include:

- You don't like the defaults
- Some of the defaults look funny with your color scheme
- You want the ability to have different colors in different environments so easily spot if you are on development or production

The original repo, along with documentation can be found at [https://github.com/sindresorhus/pure](https://github.com/sindresorhus/pure). I will make every effort possible to keep this fork up-to-date with Pure.

## Usage

Set any of the following variables in your `.zshrc` or elsewhere before Pure loads. Only variables that you want to change need to be set, as the rest will fall back to defaults. 

```
export PURE_COLOR_PATH=blue
export PURE_COLOR_GIT=242
export PURE_COLOR_GIT_DELAYED=red
export PURE_COLOR_GIT_ARROWS=cyan
export PURE_COLOR_EXECUTION_TIME=yellow
export PURE_COLOR_USERNAME=242
export PURE_COLOR_USERNAME_ROOT=red
export PURE_COLOR_PROMPT_SYMBOL=magenta
export PURE_COLOR_PROMPT_SYMBOL_ERROR=red
```
