# Mount & Blade II: Bannerlord mod encyclopedia

> 🇷🇺 По-русски: [`README.ru.md`](README.ru.md) · What changed: [`CHANGELOG.en.md`](CHANGELOG.en.md)

A reference for the game's mods: where to download one, whether it will run on your
version, what it needs and what it will clash with.

This is not a catalogue. There are plenty of catalogues, and they all show what the mod
author wrote. Here compatibility is **checked by reading the files themselves**, and
whatever cannot be checked is called out as unknown: **"not checked" is not the same as
"does not work"**.

## Getting started

Unpack the folder anywhere and run `RickEncyclopedia.exe`.

There is nothing to install; the program changes nothing in the system and writes
nothing to the registry. Everything it owns lives beside it, in the `EncData` folder.
To remove it, delete the folder.

## What is in it

**Search across nine thousand mods**, filtered by game branch, category, language and
demand. The mod itself comes first, not the things built on top of it: the name you
typed rises to the top, and it is recognised however you write it — "Banner Kings"
finds "BannerKings", and "RBM" leads to "(RBM) Realistic Battle Mod" rather than to
patches for it. The results say what each row is: **★ original** — the mod itself, the
one translations and rebuilds come from; **rebuild** — a re-upload or continuation of
somebody else's mod; **translation** — a translation and nothing more.

**Search in Russian.** Mods are named in English, but you can look for them in your
own words: "беременность", "гарнизон", "караван", "осада" all find the mods they
describe, because the descriptions are ours and written in Russian. Word endings do
not matter: "европа", "европы" and "европе" give the same results. Typed with the
wrong keyboard layout ("рфкьщтн") or spelled by ear ("хармони", "краш")? The
encyclopedia works it out and says above the list what it actually searched for.

**You can see what a mod actually is.** Every card carries a label: translation,
add-on, compatibility patch, rebuild, library, tool, asset pack. A standalone mod
carries none. The label is not guessed from the name: it is derived from the contents of
the archive and from what the mod declares in the game — the tooltip says what proves it.

**"What there is for this mod".** Type a name and a breakdown appears above the
results: the mod itself, its translations, add-ons, compatibility patches, rebuilds.
Click a group and only it remains. Open a translation and the card tells you which mod
it was made for.

**The mod card** is the heart of it. It shows:

* **which game versions the mod will run on**, and what proves it: a scan of the mod's
  references into the game's code, the author's word at publication, or nothing at all;
* **dependencies** — what has to be installed alongside, and the difference between a
  requirement and a load-order preference;
* **conflicts** — which mods contend for the same game records or patch the same places
  in the code;
* **where to download** — every known page for the mod, on every site;
* **what the mod is based on**, when it is a translation, a fork or a re-release: the
  original's name, a link to its card and a short description — so that "an updated
  version of the original" means something to a reader who never heard of the original;
* **a description in five languages** — Russian, English, Turkish and two Chinese.

**Cards open beside each other**, up to ten at once: put a mod and its dependency side
by side, or compare an original with its translation.

**Steam Workshop collections**, with their contents analysed and rated: what will fail
to install, what will clash, and which game version the set was built for.

**Favourites** — your own shortlist instead of a text file beside the keyboard. The
star on a card sets a mod aside; you can add a note ("install after RBM", "breaks
sieges"), pick the game versions and mark it as already installed. Versions are chosen
with buttons — several at once if you like — and the colour of each says at once
whether a build exists for it or the mod will not start there at all.

Better still, the shortlist is analysed as a set: which game version the whole thing
fits, which of its mods clash with one another, what is missing. The finished list
saves to a file the launcher installs in one go.

## If a card says something untrue

Press the **pencil** on the card next to the star — or in the mod window header. Write
what exactly is wrong: the wrong author, somebody else's cover art, the wrong section,
the wrong original. Text is optional.

Messages accumulate in `report.json` next to the program; nothing is sent anywhere by
itself — forward the file when it fills up. Your text is saved together with the whole
card, which is enough to find the cause and to check whether other mods share the error.

On a mod you have already written about the **pencil is lit**, and pressing it again puts
your previous text back into the field — amend it and save. One mod keeps one message, the
latest: there is no need to write the same thing several times over.

⚠️ This is the most useful thing you can report: **where something written about a mod is
untrue** matters more than any inconvenience.

## What the verdicts mean

⚠️ The one thing worth understanding about this reference: **an absence of information
is not a negative answer.** An empty cell means "not checked", not "does not work".

The scan's wording is "no obstacle found", not "guaranteed to work". Matching references
prove the mod will not fall over on a missing piece of the game; but the meaning of a
surviving piece may have changed, and some of the techniques mods use are invisible to
the scan entirely. Where we do not know, it says so.

Beside every arguable claim sits an **ⓘ** button: it explains where the conclusion came
from and how firm it is. A guess is never dressed up as a fact.

## Updates

The program updates itself. When an update is found, an **"UPDATE AVAILABLE"** badge
lights up in the header; the window opens when you click it, never on its own.

The program and the mod database update **separately**: a change in the program does not
force a re-download of the database, and a database update does not force a re-download
of the program. What changed is visible before anything is downloaded.

## If something is wrong

Run it like this:

```
RickEncyclopedia.exe --check-updates
```

You get a report of what is visible on your side and what our server answers. Send it
along with the `EncData\update.log` file.

The most useful things to report:

* **where something written about a mod is untrue** — that matters more than any
  inconvenience;
* what is unclear without explanation;
* where the program stays silent instead of saying what went wrong.

## What to expect from the beta

The data is gathered by crawling the sites and reading the builds. Some of it is
incomplete, and the cards say so plainly. The scan's verdict does not cover every game
branch: where we hold no snapshot of the game, only the authors' claims remain — and
they are marked as the authors' claims.
