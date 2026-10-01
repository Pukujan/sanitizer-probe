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

## B: single picture, mode fragments on the img only

<picture>
<source media="(max-width: 640px)" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" alt="light only" width="100%">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" alt="dark only" width="100%">
</picture>

## C: bare images, no picture

<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" alt="bare light" width="100%">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" alt="bare dark" width="100%">
