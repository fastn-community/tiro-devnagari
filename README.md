# Tiro Devanagari: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Tiro Devanagari](https://fonts.google.com/specimen/Tiro+Devanagari+Marathi/about?subset=devanagari).

Tiro Devanagari Marathi has its origins in a typeface designed for the Murty Classical Library of India book series, so is especially suited to traditional literary publishing but also made with the needs of today’s multiple print and screen media in mind. The Tiro Devanagari design applies a contemporary approach to the traditional styling of 19th and 20th Century metal types exemplified in those of the renowned Nirnaya Sagar Press, and is characterised by broader proportions, more generous counters, and strong diagonal strokes and terminals. The Marathi font favours traditional, vertical forms of many conjuncts as still found in Marathi literary publishing. For the Open Font License release, Tiro Devanagari Marathi has been extended to support additional characters, and features a new italic companion. Each font also includes a Latin subset including diacritics for transcription of Indian languages.

Tiro Devanagari Marathi was designed by John Hudson and Fiona Ross. The italic was adapted by Paul Hanslow.

To contribute, see [github.com/TiroTypeworks/Indigo](https://github.com/TiroTypeworks/Indigo).

To learn more, read [Modern Tiro Indic collection for classical South Asian texts](https://design.google/library/new-Indic-fonts/).

Designers: 

Tiro Typeworks, Principal design

Tiro Typeworks is a small type foundry specialising in custom fonts for multilingual publishing and computing. Tiro’s clients include Adobe, Apple, Brill, Google, Harvard University Press, Microsoft, the STI Pub consortium, and other specialist publishers and scholarly organisations.

John Hudson

John Hudson is a Canadian type designer and font maker, and co-founder of Tiro Typeworks (1994).

Fiona Ross

Fiona Ross specializes in type design primarily for Arabic, South Asian, and Thai scripts. She works as a consultant, type designer, author, and Professor in Type Design (part-time) at the University of Reading (UK). Fiona has received the SoTA Typography Award (2014) and the Type Director’s Club Medal (2018). [Academic Profile](http://www.reading.ac.uk/typography/about/Staff_list/f-g-e-ross.aspx)

Paul Hanslow

Paul Hanslow is an Australian born typeface designer, currently working for Tiro Typeworks in Vancouver, Canada.

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/arya-font).

TLRD:

Include fifthtry.github.io/tiro-devnagari-marathi-font package into `FPM.ftd` file:

```ftd
-- fpm.dependency: fifthtry.github.io/tiro-devnagari-marathi-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
-- import: fifthtry.github.io/tiro-devnagari-marathi-font as tiro

-- fpm.type.headline-small.font: $tiro.fonts.Tiro
```

Now if in any file you do:

```ftd
-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `tiro-devnagari-marathi-font` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Arya Font is under [Open Font Licence](https://fonts.google.com/specimen/Tiro+Devanagari+Marathi/about?subset=devanagari), this FPM wrapper is also
under [Open Font License](LICENSE).




