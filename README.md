# Picture pair probe

## F: anchor-wrapped picture with mode fragment

<a href="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only">
<picture>
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif" alt="anchor light" width="100%">
</picture>
</a>
<a href="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only">
<picture>
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-dark.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif" alt="anchor dark" width="100%">
</picture>
</a>

## G: single picture, prefers-color-scheme plus phone

<picture>
<source media="(prefers-color-scheme: dark) and (max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-dark.gif">
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif">
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif" alt="scheme pair" width="100%">
</picture>

## C: bare images, no picture

<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" alt="bare light" width="100%">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" alt="bare dark" width="100%">
