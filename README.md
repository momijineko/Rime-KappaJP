# Kappa Japanese Wubi Input Scheme for Rime

![GitHub tag (latest by date)](https://img.shields.io/github/v/tag/momijineko/Rime-KappaJP) ![GitHub](https://img.shields.io/github/license/momijineko/Rime-KappaJP)

English | [中文](https://github.com/momijineko/Rime-KappaJP/blob/master/README_zh.md) | [日本語](https://github.com/momijineko/Rime-KappaJP/blob/master/README_ja.md)

A Japanese input scheme based on Wubi86.

It’s a input scheme by `Kanji Chokusetsu Nyuryoku`<sup>[漢字直接入力 - Wikipedia](https://ja.wikipedia.org/wiki/漢字直接入力)</sup> to input Japanese.

## Declaration

- The original author of this scheme is [零尾河童](https://github.com/zerobikappa/rime-kappajp86), I’m just porting to the Rime input platform.
- This scheme borrows the OpenCC part of the [rime 訓讀み](https://github.com/sgalal/rime-kunyomi) scheme sgalal made.
- This scheme follows MIT license.

## Usage and precautions

Please read the [Wiki(only Chinese page now)](https://github.com/momijineko/Rime-KappaJP/wiki) before using it.

Copy the documents under the root directory of the repo into the user folder of RIME for deployment.

Opencc is used in this scheme to convert Hiragana / Katakana. Please put `hirakata.ocd` and  `hira2kata.json` in the `opencc` folder before use.

Before using, you need to add the following content under the patch item in `default.custom.yaml`.

```yaml
patch:
  ...
  "key_binder/bindings":
    #- {accept: comma, send: Page_Up, when: paging}
    #- {accept: period, send: Page_Down, when: has_menu}
```

Welcome everyone to maintain the dictionary of this scheme and submit PRs to me.

