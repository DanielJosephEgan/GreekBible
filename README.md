# Greek Bible Reader

An interactive Bible reader for learning Greek through Scripture.

Website: https://danieljosephegan.github.io/GreekBible/

## Features

- Class 4–8 vocabulary buttons cycle through Not started (English), Learning (blue Greek), and Known (green Greek).
- Words shared with a known class stay green. Turning a class off preserves selections supplied by other classes.
- Click English or blue words to mark them known; click green words to return them to English. Changes apply to matching Strong's identifiers throughout the reader.
- Verse percentages count known words, excluding words still being learned. Reset all clears class and individual word selections.
- A compact, sticky cheat sheet offers selectable Classes 4–8 and text-size controls. Selected classes and text size are remembered in this browser.
- Book and chapter dropdowns, dictionary forms, vocabulary sorting, and per-verse percentages.
- Douay-Rheims English reference with a hide option.

## Coverage

1,337 verses: the Gospel of John (all 21 chapters, 879 verses), 1–3 John, 1 Peter, 2 Peter chapter 1, Jude, and Revelation (Apocalypse) chapters 1–10.

The Gospel of John uses Douay-Rheims numbering. Greek-source John 6:51 is split into Douay-Rheims 6:51–52; subsequent verses in chapter 6 are shifted by one. Greek-source John 11:56–57 is combined under Douay-Rheims 11:56. Every Greek source token is retained once in its original order. John 5:4 is English-only with an explanatory note because it is absent from this Greek source; no vocabulary percentage is shown for that verse. Its English text remains available even with Hide Douay-Rheims enabled.

## Run and publish

Open index.html directly in a browser. No build process is required. The app's core functions work offline; optional Google fonts require internet access.

GitHub Pages serves the root of the main branch. Update index.html and push to main to publish changes.

Learned vocabulary is kept for the current page session only; refreshing or closing the page resets it.

## Credits

Greek word data: [sixcore-droid/interlinear-data](https://github.com/sixcore-droid/interlinear-data), licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
The data has been adapted with word-by-word English alignment and class vocabulary. English reference: Douay-Rheims Bible.

Gospel of John Greek tokens, morphology and contextual English glosses come from the supplied `john.json` in interlinear-data, derived from [Clear-Bible/macula-greek](https://github.com/Clear-Bible/macula-greek), CC BY 4.0. Glosses fall back to the source's word-level English field where necessary; the source's NET reference translation is not included. Gospel of John English reference: [GetBible Douay-Rheims](https://api.getbible.net/v2/douayrheims/43.json), public domain. Greek and Douay-Rheims readings can differ because they follow different textual traditions.
