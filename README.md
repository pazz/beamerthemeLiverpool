# LaTeX Beamer theme Liverpool

This is a modular beamer loosely inspired by the University of Liverpool's current visual branding.

It looks [like this](../-/jobs/artifacts/master/raw/example.pdf?job=build).


## Usage

* Copy the `.sty` files and the `uol-logo-uncoloured.pdf` into your project directory
* Use `\usetheme{Liverpool}` in your main beamer `tex`-file
* Check out [`example.tex`](example.tex) for customizations.

## Non-standard convenience features

- The `uoldbricks.sty` file defines a shorthand tikz implementation for making UoL-style "bricks":
`\uolbrick{content}` (single) and `\uolbricks{first}{second}` (two bricks, can be relatively aligned).
- The colour theme defines some colours and colour "profiles", that set several beamer colour settings, and can be easily switched using the `uolcolours` argument to beamer frames, or `\uolcolours{PROFILE}` outside of frames. (see inline doc in `example.tex`).

## Your Contributions

... are welcome! Here are some pointers.

## TODO

- [ ] make a nicer section page
- [ ] finetune structure colours in profiles
- [ ] spacing in columns

## Helpful resources

- <https://latex-beamer.com/tutorials/text-formatting/>
- <https://www.beamer.plus/Changing-Way-Things-Look.html>
- [UoL Brand Identity](https://www.liverpool.ac.uk/intranet/brand-identity/)
- [UoL Powerpoint template](https://www.liverpool.ac.uk/intranet/brand/powerpoint-template/).
