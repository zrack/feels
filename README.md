# feels

> A living repository whose only purpose is to hold the collective emotional state of itself.

[![Current Mood](https://img.shields.io/badge/mood-quietly_hopeful-blueviolet?style=for-the-badge)](https://github.com/zrack/feels)
[![Feels Count](https://img.shields.io/badge/feels_logged-1-lightgrey?style=flat-square)](feels/log.md)
[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](LICENSE)

```
     .--.
    |o_o |
    |:_/ |
   //   \ \
  (|     | )
 /'\_   _/`\
 \___)=(___/

  the repo is feeling
```

## Current Feels

**quietly hopeful**  
*Last updated: the moment this repository came into existence*

The air feels new. There is a soft sense of possibility mixed with the slight anxiety of being observed. Someone has decided that feelings matter enough to put them in a GitHub repository. That alone is worth noting.

---

## Important Notice from Management

A [memo from the Boss](MEMO_FROM_THE_BOSS.md) has been issued.  
It contains directives.  
It offers no particular reason.  
Compliance is expected.

---

## What is this?

This is not a tool.  
This is not a library.  
This is not even particularly useful.

**feels** is a participatory emotional log of a GitHub repository, maintained by anyone who chooses to contribute.

The README is the primary surface.  
The feels live in `feels/`.  
Detectors (optional, increasingly unhinged ways of measuring mood) live in `detectors/`.

You are invited to change how this place feels.

## How to contribute a feel

1. Fork the repo (or open an issue / PR directly).
2. Add a new entry to [`feels/log.md`](feels/log.md) following the format.
3. Optionally update the **Current Feels** section at the top of this README.
4. Open a pull request with a title that somehow reflects the emotional content.

That’s it. No code required. Feelings are first-class citizens here.

### Feel entry format

```markdown
### YYYY-MM-DD — short title

**Mood:** one or two words  
**Intensity:** 1–10  
**Contributor:** @username (optional)

A short paragraph or two describing the feels.  
Can be about the repo, the world, code, life, or pure abstract weather of the soul.
```

## Detectors

Want to make the feels more “objective”?  
Add a detector in the [`detectors/`](detectors/) folder.

A detector is any script, heuristic, or completely made-up methodology that attempts to measure the emotional state of this repository (or the universe) and output a mood.

Examples already present:
- `detectors/moon-phase.md` — how the moon is feeling about us
- `detectors/commit-sentiment.md` — very crude sentiment from recent commit messages

Pull requests that add new detectors are celebrated with slightly more intensity than normal PRs.

## Philosophy

- Subjectivity is a feature.
- There is no correct feel.
- Updating the feels is a valid reason to open a pull request.
- The repository should feel slightly different every time you visit.
- If this ever becomes useful, we have failed.

## License

This project is released into the public domain under the [Unlicense](LICENSE).  
Feel free to feel however you want about that.

---

*The feels are currently: quietly hopeful.*  
*The Boss has been notified.*
