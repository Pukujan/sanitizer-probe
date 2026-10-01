# Picture pair probe

## H: bare img with srcset and sizes, mode fragment

<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif#gh-light-mode-only" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-light.gif 400w, https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-light.gif 1000w" sizes="(max-width: 640px) 90vw, 838px" alt="srcset light" width="100%">
<img src="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif#gh-dark-mode-only" srcset="https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/narrow-dark.gif 400w, https://raw.githubusercontent.com/Pukujan/sanitizer-probe/main/a/wide-dark.gif 1000w" sizes="(max-width: 640px) 90vw, 838px" alt="srcset dark" width="100%">

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
