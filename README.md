# Tiro Devanagari: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Tiro Devanagari](https://fonts.google.com/specimen/Tiro+Devanagari+Marathi/about?subset=devanagari).

Tiro Devanagari Marathi has its origins in a typeface designed for the Murty Classical Library of India book series, so is especially suited to traditional literary publishing but also made with the needs of today’s multiple print and screen media in mind. 

Designers: Tiro Typeworks, Principal design, John Hudson, Fiona Ross and Paul Hanslow


## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/tiro-devnagari-marathi-font).

TLRD:

Include fifthtry.github.io/tiro-devnagari-marathi-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/tiro-devnagari-marathi-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/tiro-devnagari-marathi-font/assets as tiro

;-- fpm.type.headline-small.font: $tiro.fonts.Tiro-Devanagari-Marathi
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `tiro-devnagari-marathi-font` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Tiro Devanagari Marathi Font is under [Open Font Licence](https://fonts.google.com/specimen/Tiro+Devanagari+Marathi/about?subset=devanagari), this FPM wrapper is also
under [Open Font License](LICENSE).




