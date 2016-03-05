# lilyjazz: LilyJazz font package for lilypond

This package provides the LilyJazz open-source font for lilypond.

Original code by Torsten Hämmerle.

## Installation

Install using [lyp](https://github.com/noteflakes/lyp):

```bash
$ lyp install lilyjazz
```

## Usage

```lilypond
\require "lilyjazz"

\layout {
  \context {
    \Score \jazzOn
  }
}

\markup { \override #'(font-name . "LilyJAZZ Text") "Some markup" }

```

For more details see the included [example](https://github.com/noteflakes/lyp-lilyjazz/blob/master/test.ly).

## Compatibility with Lilypond versions

This font is known to work in Lilypond version 2.18.2 or later.