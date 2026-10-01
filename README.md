# Picture pair probe

## A: two picture elements, mode fragments

<picture>
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" alt="light" width="100%">
</picture>
<picture>
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-dark.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" alt="dark" width="100%">
</picture>

## C: bare images, no picture

<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" alt="bare light" width="100%">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" alt="bare dark" width="100%">

## D: single picture, prefers-color-scheme dark source

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif">
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif" alt="scheme" width="100%">
</picture>

## E: single picture, dark source with combined media

<picture>
<source media="(prefers-color-scheme: dark) and (max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-dark.gif">
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif">
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif" alt="scheme pair" width="100%">
</picture>
