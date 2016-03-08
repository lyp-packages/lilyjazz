# lilyjazz: LilyJazz font package for lilypond

This package provides the LilyJazz open-source font for lilypond.

Original code by Torsten Hämmerle and Abraham Lee. For more information on producing Jazz lead sheets with Lilypond, checkout Abraham's [blog post](http://leighverlag.blogspot.fr/2015/12/mimicking-real-book-look.html).

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

For more details see the included [example](https://github.com/noteflakes/lyp-lilyjazz/blob/master/test/test.ly).

Another example is a "real book" style setting of ["All Of Me"](https://github.com/noteflakes/lyp-lilyjazz/blob/master/test/allofme.ly).

## Compatibility with Lilypond versions

This font is known to work in Lilypond version 2.18.2 or later.