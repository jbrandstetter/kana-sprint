# Kana Sprint

Timed hiragana/katakana drill, a local take on gokana.com. Set a timer, answer as many kana as you can,
and get statistics at the end. Kana you miss or answer slowly come back more often (per-kana
accuracy + speed → mastery → selection weight; misses return a few cards later in the same round).

Play: https://jbrandstetter.github.io/kana-sprint/

- Single `index.html`, no dependencies, no build. Open the file directly or serve the folder.
- Progress lives in the browser's localStorage (per device). Use Export/Import to move it.
- iPhone: open the URL in Safari → Share → Add to Home Screen. Works offline after the first load.
