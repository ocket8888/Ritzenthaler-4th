# Contributing

## Building

The project has no build process (yet?), each ruleset is currently built separately. The process should be simple via `pdflatex`:

```bash
pdflatex [SOURCE FILE]
```

And things like [Overleaf](https://overleaf.com), MikTeX, and the like shouldn't have any issues.

## Coding standards
You really shouldn't need to do much in the way of formatting. The one thing I ask is do not do content updates at the same time as changing the presentation, i.e. "Now has blue border around the page and also some Croquet rule edits" is a bad pull request. Finally, I don't care too much about adding new dependencies, however please don't make the project only compilable via XeLaTeX or LuaTeX or some such. Just plain LaTeX should do fine.

## Images etc.
If you use external resources like a bibliography (and please do make any bibliographies external to the main files) or images, be sure to include the source. For example, if you made an `.svg` image but convert it to `.pdf` for inclusion in a `.tex` file, please include the `.svg` as well as/instead of the `.pdf`.
