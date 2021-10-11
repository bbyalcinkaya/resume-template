# Resume Template
Resume template with colored and monochrome options.
## Features
### Colored or Monochrome
Set `\monochrome` flag to select monochrome.

```
\def\monochrome{0} % colored
\def\monochrome{1} % monochrome
```

Change `\cvHue` value between 1 and 240 in monochrome mode.

```
\def\cvHue{200} % purple
\def\cvHue{1} % red
```

### Two Columns
Wrap the sections with `\begin{multicols}{2}` and `\end{multicols}`.

## Example outputs
* [Colored - 1 column](example/resume.pdf)
* [Monochrome - Purple - partial 2 column](example/resume-monochrome_200.pdf): Hue = 200
* [Monochrome - Red - partial 2 column](example/resume-monochrome_1.pdf): Hue = 1
