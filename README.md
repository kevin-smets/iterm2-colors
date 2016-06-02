# iterm2-colors

iTerm2 colors as JSON, Sass, Scss, Stylus and Less

## Install

```
npm i -S iterm2-colors
```

or (probably) as dev dependency:

```
npm i -D iterm2-colors
```

## Abstract / Functional?

The files are split into two folders: abstract and functional.

In the `abstract` folder, variable names are as defined in the itermcolor files, E.g. ansi-0-color, ansi-8-color, cursor-color.

In the `functional` folder, the variable names are declared as they are defined in the preference pane of iTerm2. E.g. black-normal, cyan-highlight, cursor-color. I know, these are not really functional, but hey, no need to mess with this 'set in stone' standard :).

## Bugs?

Bugs should be logged over at [kevin-smets/iterm2-colors-converter](https://github.com/kevin-smets/iterm2-colors-converter)

## Source

These files are a straight conversion from [mbadolato/iTerm2-Color-Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes). All themes and their screenshots can be found there.
