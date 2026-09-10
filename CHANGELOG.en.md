# What's new in the Encyclopedia

> Plain language: what changed and why.
>
> Entries are grouped by release. Everything accumulates under "Unpublished"; when a
> release goes out, the section is closed with a version and a date, and a new one
> starts above it.

## Unpublished

## 1.0.1 — 10.09.2026

### "Features" in the left panel

A fifth filter group, with checkboxes: in-game settings (MCM), hotkeys, multiplayer, no
new campaign needed (author's word), open source, no libraries needed, has a gallery.
Several checkboxes combine with "and": tick "MCM" and "no new campaign" and you get mods
that have both. Counters follow the current selection, like the categories do.

### Three hints on first launch

Above the results, a short note is shown once: what the two roots at the top are, what a
mod card answers, and where to search. "Got it" removes it for good.

### Text size

Settings now have "Text size": 90 %, 100 %, 115 %, 130 %. Applies immediately, to all
windows.

### Small things in the results and the card

Covers in the grid show a "▣ 6" badge for mods whose gallery has something to look at.
Groups in the left panel collapse with a click on the header, and remember it. `Ctrl+W`
closes a mod card.

### The window remembers where and how it was closed

Size, position and "maximized" are restored on the next launch. If the monitor the window
was on has been unplugged, it opens centred rather than off-screen. For the launcher, a
`--family 1.4` start key was added: the card and the results open straight on the
player's profile line.

### Under a red verdict — where to go

If a mod will not start on your line, or is doubtful, and it has a rework that does work on
that line by code analysis, the card says so directly: "A rework works on 1.4: Noble Titles
Plus" — with a link. Translations do not count as successors, and an author's word
"works" is not proof enough to send you to another mod.

### Above the dependency list — how much you will need in total

One line above the list: "You will need 4 in total: Harmony, ButterLib, UIExtenderEx, Mod
Configuration Menu — 41 MB". Requirements of requirements are counted too, for the chosen
game line; what the encyclopedia does not have is named separately; the size covers only
what has a file for that line.

### The card shows what this mod is most often installed with

Below "More by this author" there is now "Most often installed together": up to seven
mods that sit next to this one in Steam Workshop collections, with the number of
collections for each. The header says how many collections hold the mod itself. Scaffolding
present in nearly every collection (Harmony, ButterLib, MCM, UIExtenderEx) is left out —
it says nothing. The block only appears where there are enough collections.

### The encyclopedia opens on your game version

Only when there is a single game on disk. Several copies found — the line is not picked
automatically: the note lists the versions found and asks you to choose. "No libraries
needed" no longer lists the libraries themselves (Harmony, ButterLib, MCM). The "▣ 6"
badge on a cover has a tooltip: that many screenshots in the card's gallery.

#### As first designed


Every launch used to start on "any version", and the line had to be picked again.
The encyclopedia now finds the installed game itself — through the launcher, if it
sits next to it, or through Steam — and opens on its line, with a note "Found
Bannerlord 1.4.7 — showing mods for the 1.4 line. Change". The line you pick is
remembered; in Settings you choose what to do at startup: take it from the installed
game, use the last chosen one, or always "any".


### Mod translations now have their own pages

The Russian translation of Realistic Battle Mod is on Nexus and has been downloaded
seven thousand times — yet the encyclopedia did not have it. Nor 330 others:
translations into Russian, Turkish, Chinese, Polish and Ukrainian, plus third-party
fixes that keep mods running on newer game versions. They were in the database, but
without a card of their own. You could not find them by search, open them, or download
them.

The reason is simple and annoying. A translation almost always arrives as an overlay:
the archive holds a folder named after the mod being translated, and the files go inside
it. The encyclopedia read that folder name and concluded "this is the same mod" — after
which the translation dissolved into the original's card as a single service line. Each
such work now has its own card: its own title, author, download count, cover, a
description in six languages and, above all, its own download button.

### 150 cards are no longer nameless

The flip side of the same mistake. A mod that IS itself a translation or a fix — say
"MCMv3 Русский" with 35,818 downloads — stood empty in the encyclopedia: a folder name
instead of a title, no author, no cover, no numbers. The rule "a translation page does
not describe the mod" also hit mods for which such a page is the only one they have, and
their own. The encyclopedia now tells the two cases apart.

### Translations say which language, and what they go on top of

A translation card now carries its language and the mod its files go into. Neither is
guessed from the title: both are read from the archive itself.

### A mod's card no longer wears the face of its continuation

Popular Nexus mods have third-party continuations next to them — "Harmony Updated v1.4.6",
"Agriculture Estate Updated", "Updated DismembermentPlus". The encyclopedia treated the word
"Updated" as noise, and when the continuation had more downloads, the mod's card took its
author, cover and numbers: Harmony showed 18,993 downloads instead of 6,322,047,
Dismemberment Plus 1,919 instead of 1,469,832. A continuation is now a separate work with
its own card, and the mod shows its own page. 35 cards got their face back; 87
continuations got cards.

### Parts of one mod are called by their own names

A large mod often ships as several folders — core, map, an RBM patch — and all of them bore
the mod's name: four "Realm of Thrones" cards in a row, the RBM patch of Open Source Armory
was simply "Open Source Armory". A part now takes its name from its own manifest: "Open
Source Armory: RBM Patch", "ROT-Dragon", "HandleEncounterPatch". 272 cards renamed.

### Translations that edit game data keep the "translation" label

The Russian localisation of Realm of Thrones and the Polish translation of the game write
translated names straight into troop and settlement records — and by the number of such
records the encyclopedia decided it was a standalone mod and filed it under "Troops". When
both the model and the name say "translation", game records no longer override them.

### A mod's description comes from its own page, not from its translation's page

The description of "Auto Resolve Rebalanced" (301,445 downloads) retold the page
"Auto Resolve Rebalanced Ru 1.34.1 (Vortex support)" — and the mod was listed as a
translation of itself. Foreign-page filtering now shares one rule with the build itself;
262 descriptions rewritten.

### A patch's requirement is not the mod's requirement

"Horse Caparisons" "required" RBM — the line came from a third-party compatibility patch
page, "Horse Caparisons fix 1.2.12 and RBM". A page about someone else's work on a mod no
longer contributes requirements to the mod.

### Some Steam Workshop mods can also be downloaded from Nexus

Some mods listed a single address — the Steam Workshop, which requires being signed in
to Steam. Where the very same archive was also found on Nexus, a second address has been
added to the card. The match is made on file contents, not on names: "Improved Garrisons
RUS" from the Workshop and "Russian Translation Improved Garrisons" from Nexus are named
alike but are two different works by two different people.

## 1.0.0.1 — 08.09.2026

### Our mod's cover is back in the update

The update package shipped a month-old set of covers — from a folder that stopped being
refreshed on 7 August. It looked fine from the outside: covers are there, 879 of them,
everything in place. But none of the newer ones were included, and the cover of our own
mod "Voices of Calradia" never reached anyone: it showed up in the test build and
disappeared after updating from the server.

## 1.0.0 — 08.09.2026

### Cards no longer show another mod's numbers and author

A mod can have several pages: its own, and one whose archive merely carries it along with
a dozen others. Eight cards were taking the author, cover and download count from the
second kind. `Danger's Recruiter` showed 135,458 downloads and the author "Ralf Keller" —
both belong to a different mod, "Ralf's Recruiter"; the mod itself has 25,174 and the
author Danger. `DiplomacyFixes` showed the two million downloads of `Diplomacy`. And
`Anno Domini 1259` had the opposite problem: 2,171 instead of its own 101,843, because
the numbers came from a small patch's page.

### A requirement with the author's typo no longer leads nowhere

`UIExtenderEx` — a library half the catalogue rests on — listed "Bannerlord.ButterLub"
among its requirements. No such mod exists; the author missed a letter. The line sat
dead: nothing to click. Such typos are now recognised and lead where they should — 34
lines in all, including the familiar Armory/Armoury split.

### Advice like "load Ambush above Ambush" is gone

A load-order hint arrived from the mod's page with its beginning lost: the author wrote
"Harmony above Training Tweak", and the card kept only "above Training Tweak" — telling
the reader to put the mod above itself. Fifteen such lines are removed. Useful hints
stayed: "load at the very bottom of the list" points at a place and works without a
second mod.

### "The author abandoned it" — only when they actually said so

`Swadian Armoury` (747,781 downloads) carried the "abandoned" mark because of the phrase
"updates are a bit slow since I am a solo dev". That is an apology for the pace, not a
departure. The mark was likewise removed from a mod that is "under a remake" and one that
is "still evolving".

### "Requires StoryMode" no longer leads to an unrelated mod

`StoryMode`, `CustomBattle` and `Multiplayer` are parts of the game itself — nothing to
download. But mods on Nexus claimed those same names, and seven "requires" lines pointed
at an unrelated mod's card, such as "She will always be your brother". A game module's
name is now proof enough on its own, no page needed.

### The "abandoned" mark comes only from the mod's own page

`NPC Revamp`'s card lives on the page for version 10.0, yet the verdict "I will remove
this page" arrived from the old 9.0 page. Same for a tattoo mod: the card is version 1.2,
while "currently a prototype" came from the 1.0 page. Sixteen such marks are gone: words
about abandonment belong to the work where they were said.

### Smaller things

* An add-on is no longer listed as a condition for the mod it was made for: `BRE Core`
  required two of its own add-ons, which exclude each other. Such lines are now marked
  "optional" — the link stays, the untruth goes.
* "Required files" and "Four Prerequisites" no longer appear among requirements: those
  are headings from a description, not mods.
* Author lines reading "-" and "unknown" are cleared — better empty than untrue.

### The card says WHERE the mod will break, not just that it will

The reference used to answer "is there a problem or not". People read that as "the mod
won't start" — while a mod usually does start, plays for hours and crashes in one
particular place.

Now every finding says **when the game will get to it**: "won't start", "will break
loading a save", "crashes in battle", "crashes on the campaign map", "crashes when
leaving the game", "crashes once the game reaches this part of the mod". For mods that
hook into the game's code, the hook point is named — the very action in the game where
it all falls apart.

To make this possible every assembly in the catalogue had to be analysed again — forty
thousand files — recording exactly where in the code each finding sits.

### "This mod needs five more" — where nothing is needed

`Realistic Battle Mod` — over two million downloads — listed five armour packs and their
patches as required, each with 27 thousand. Taken at face value, the mod failed to start
for 98.8% of the people who installed it. It starts.

The fault was not invention but address. Requirements are read not only from a mod's own
settings but from its page too — authors write in words what the settings never say. And a
foreign page was attached to this mod: a large pack that ships `Realistic Battle Mod`
inside itself. Its "install these mods in their needed versions" became the requirements of
the mod it carries.

Neighbours had it worse and plainer: `Serve as Soldier` required Serve as Soldier, `Hot
Butter` required Hot Butter. A mod required itself.

Words from a page are now credited to the mod **the page is about**. 1,115 such lines were
removed across the reference.

### A card no longer passes off someone else's work as its own

The reference builds a card from several pages at once, and a foreign page slipped in
easily: a submod, a patch and a translation all carry the name of the mod they were made
for. Five separate faults came from that, all found in one evening.

**A mod carried someone else's name.** The Japanese conversion `Shokuho` — two hundred
thousand downloads — was listed as "Shokuho - Unique Lords and Ladies (obsolete)", and its
"Author's word" tab said "this mod is no longer needed". Both the name and that sentence
came from the page of a small add-on that installs inside `Shokuho`'s own folder. The rule
treated a card as nameless when its name matched its folder — while that match was exactly
the proof the name was right. Fixed for 61 mods; the 89 good renames such as "AutoBlocker"
→ "Auto Blocker" stay.

**The author's word was about a different mod.** The card promises the reader "taken from
the mod's own page" — and for every sixth line that was untrue. Words now come only from
the page that gave the card its name and cover.

**Part of the game opened as somebody's mod.** For mods that need `StoryMode` or
`CustomBattle` — these are the game's own modules, nothing to download — the line was
clickable and opened a Nexus mod that replaces those modules. **1,482** lines did that.
The same fault was fixed in folder lookup: asked "whose `SandBox` is this?", the reference
answered "Aserai Unit Buff", and whole-game translations were shown as translations of
that foreign mod.

**One mod stood in the reference twice.** "Bannerlord Coop" appeared as two news entries
in a row, in different sections, with one cover. The stronger of the two cards lost:
the choice went by one platform's counter, and both share it — the page is the same. Demand
across all platforms decides now.

**A "works" verdict given without checking.** When all of a mod's code went to one card,
the second looked like a mod with no code at all and was granted "works on every version"
for free. Removed from 31 cards.

A catalogue-wide sweep now guards against all five, across all ten thousand cards.

### Captions under mod names — now for English readers too

Under a mod's English name sits a short caption in the reader's language. There was
deliberately no English one: the mod's name is already English, and a second identical line
adds nothing.

But twenty-seven mods carry names that are not written in Latin script — Chinese, Russian,
Ukrainian — and an English reader saw unfamiliar characters with nothing underneath. They
have a caption now.

### A mod is no longer blamed for files the game never opens

Our biggest mistake of the week, and the owner found it: we listed `Empires of Europe
1700` as "won't start", while people play it — it only crashes on the way out.

It turned out the reference judged a mod by EVERY file in its folder. The game does not.
Each mod carries a list of what to run, and the game opens only that: it creates the
object and sends it the events — "the mod has loaded", "the game has started", "the game
is closing". Everything else in the folder merely sits there and comes into play only if
something calls it.

`Empires of Europe 1700` names nine files out of fourteen. The verdict came from two of
the others — foreign mods packed into the bundle and not named in the list. We were
promising a crash in an event those files will never receive.

To avoid repeating the mistake, the list was read from the game's own code rather than
by eye, across all its versions. Which turned up something else: there are two kinds of
entry, not one — some files the game loads but sends no events to. That difference is
exactly what decides whether a crash "at startup" can be promised at all.

54,141 mod descriptions were read and 44,486 declared files found. The "won't start"
verdict has been lifted from 178 cards across every game version. The evidence itself
stays visible, labelled "the game does not start this part on its own" — because "the
game does not open it" is still not the same as "harmless": a neighbouring file may call
it.

### Explanations of findings now speak every language of the reference

The "what this part of the game is" explanation used to ship in Russian only: the
translations were made but never carried into the delivery — that step was simply
missing. All six languages are in place now.

It also turned out the explanations were often not found at all. The cause was not a
shortage of them but that a finding names a part of the game differently from our
reference: sometimes by a method instead of its class, sometimes by an old name — half
of those classes moved inside the game back in 2020. The explanation now sits under
every spelling it may be asked by, and is found on the first try. 928 parts of the game
are described, up from 704.

### Plain words for what is missing

The details used to say "missing `TaleWorlds.Core.CultureCode`". Clear to a programmer,
not to anyone else.

Now an explanation in ordinary words stands next to it: what this piece of the game is
and what it is responsible for. The explanations come from analysing the game itself —
every version of it, not just the latest: what the current game no longer has could not
be described from it, and that is exactly what most findings are about.

### The launcher finds mods that are named differently on disk again

A mod can have three different names, and they need not match: the folder name, the name
the mod announces to the game, and the human title in its own settings. For `Empires of
Europe 1700` the folder is called "Europe 1700" with a space, while the reference records
the mod as "Europe1700".

The launcher asked the reference "do you know this mod?" using one spelling and looked for
the answer under another — and found nothing. The install button was simply missing, in
seven places at once: the mod list, the pack window, the updates list, "our mods", the log
and two reports.

The delivery now carries a list of every spelling: 26,289 names — how the mod calls its
folder, how it announces itself to the game, and what it calls itself. Any of them works.

### "Won't start" is now said only when it is true

The reference handed out sentences far too easily. Code analysis answers the question
"when will the game notice the code is gone" — at class load or at the call — and we
passed that answer off as "the mod does not work". The difference is huge: the game
looks for what is missing **at the moment it gets there**, so a mod can load, play for
hours and crash in one single place.

The worst of it was this: **a mod was sentenced for someone else's file**. Authors of
large packs bundle whole third-party mods and libraries, and for `Empires of Europe
1700` twelve of fifteen files are clean, while "won't start" rested on one field inside
a bundled `CustomSpawns` — which is replaced by its fresh version in one move. The owner
plays that mod.

What changed:

* **a field of a type the game no longer has** is no longer a sentence but "uncertain";
* **a third-party file in the bundle** no longer sinks the whole mod: we say "uncertain"
  and name the culprit, which has a card of its own;
* in exchange, there is now a reason to say "won't start" **with confidence**: the mod
  patches a game method this version does not have. Such mods never reach the main menu,
  and we now see them — 76 cards on game 1.4;
* a missing class now comes with a hint about **where it went**: more than a thousand
  names in our evidence were not deleted but renamed back in 2020–2021. Instead of
  "reaches for something that isn't there" a person reads "it appears this is now called
  such-and-such", and it is immediately clear the mod was built for a very old game.

### Game version 1.5.2 added

Compatibility on branch 1.5 was judged by 1.5.1. Now 1.5.2 is captured and analysed —
337,500 elements of game code — and the branch answers for the version people play on.

### The card now also says what a live person saw

Code analysis answers "what does the mod reach for", not "can you actually play it".
That difference is not small: the game resolves missing code **at the moment of the
call**, so a mod with missing pieces loads, plays for hours and crashes exactly where it
finally gets there. For `Empires of Europe 1700` on game 1.4 we said "won't start" —
while people play it, and it only crashes on exit.

We added a list where the owner writes down what was checked by hand: whether the mod is
playable, and if it breaks, where. **Such a record overrides our analysis**: the game
version row takes its answer and its colour, and our verdict moves to the second line as
the explanation of the cause. The date of the check and who made it stand next to it.

The first two records are about that same `Empires of Europe 1700`: on game 1.4 it is
playable but crashes on exit; on game 1.2 the menu loads but starting a new game crashes.
The second one flatly contradicts our analysis, which considered branch 1.2 working — and
it is right to contradict it: what actually happened is what should be shown.

### "Voices of Calradia" is now in the reference

Our new mod — a Russian voiceover for Bannerlord's native lines — now has its own card
in the catalogue: cover, description in all six languages of the reference, and a link
to the Steam Workshop.

Until now our own cards were the launcher and the reference itself, and those are
programs, not mods. A mod is asked something else — will it run on my game version, and
what does it need alongside. So our cards learned to name game branches (1.2 — 1.5 here:
the mod is data only, so there is no code in it to break when the game changes) and to
show the game's own modules the mod must be placed below in the load order.

The cover travels inside the delivery as a ready file, the same way the launcher's does:
the picture is always there, even when the site is unreachable.

### The card names the build worth installing again

A "works" line sometimes came with an empty version field: the reference knew the mod
worked on that game version but would not say which build to take. The fault was our
own build step — it picked the newest checked build without looking at whether that
build had a version number. Whenever the newest one turned out to be unnamed (the
number could not be read from the site), it wiped the number already in place.

Because of this the launcher could not hold a person back from a bad update: `Harmony`
on game 1.2 said "works" but named no build, so the newest one on the site was offered
— and that one needs a newer game.

Now the number is taken only from builds that have one, together with that build's
date. Four hundred more lines name a version.

An empty field still happens — where no checked build has a readable number at all.
That is an honest "we do not know", not "anything will do".

### The card no longer contradicts itself

A game-version row promised "questionable", and unfolding the list showed the very
same mod version marked "won't start". Two answers to one question: the row's
verdict came from the overall analysis, the file's verdict from the specific
unpacked build.

Now, if the version we suggest is in the list, the row takes its verdict: we
recommend that file, so we answer for it. And if the suggested version isn't in
the list, the row promises no more than the list shows.

The wording is fixed too: "none of the versions start" now appears only when the
checked versions really don't start. That red line used to show up over lists
where every version was "questionable" or "works with caveats".

### "Author's word" instead of "How to install"

The tab is renamed — it holds more than installation: load order, known issues,
hotkeys, bundled languages.

The layout follows suit: labels in a narrow left column, the answer on the right
with the author's own words beneath it — visible at once, no expanders. Fifteen
bordered tiles read as fifteen separate things rather than one body of facts. The
author's words are now clickable themselves: a click opens the mod page, and the
separate "Open the page on Nexus" line under every entry is gone.

### Required and optional are told apart

Dependency sections used to blur into one list. Now a section is set off by a rule
and by space, and whatever the mod cannot run without carries a coloured stripe on
the left: "must be installed" is visible without reading the caption.

### Version rows stopped jumping

The mod-version and verdict columns share one width across all rows: a branch
without a version used to collapse its column, and the coloured badge slid left —
a staircase instead of a straight column.

### Version checks are honest now

A large mod ships more than one folder — Realm of Thrones ships four. The code
lives in one of them, while the card in the guide was tied to another, so checks
of the newest build never reached it. The result: we unpacked Realm of Thrones
8.1.2 (August 2026) and confirmed it runs on 1.4.5, 1.4.7 and 1.4.8 — and the card
still said "won't start", because it only saw builds from 2022. 132 of the 209
large mods were affected.

The check now belongs to the mod as a whole, the way people download it.

### Checked versions: working ones first

Clicking a game version opens the list of mod versions we checked and what came
out. It used to be sorted by date, so a broken version often stood first. Now the
ones that work are on top — that is what people came for.

One more fix: the list dropped old versions even when those are exactly the ones
that work. A release date says nothing about compatibility — a mod built for 1.2
often runs fine on 1.5, and our check sees that.

### A living mod no longer looks abandoned

* "The author says the mod is abandoned" sometimes sat under the phrase "under
  active development": the description parser confused one for the other. 47 such
  verdicts removed.
* The update date came from the wrong page: "Empires of Europe 1100" looked
  abandoned since January 2023, while its page was updated in August 2026.
* No more pairs of lines cancelling each other out: "a new campaign is required"
  next to "safe to add to a running save".

### Small things that were an eyesore

* A mod no longer requires itself ("Serve as Soldier requires Serve as soldier").
* A requirement named after the mod rather than its folder is now clickable: the
  line "needs Detailed Character Creation" leads to the card.
* A mod no longer argues with itself: conflicts with its own earlier version and
  with a patch made for it are gone.
* A mod card no longer carries someone else's name: "Bannerlord Total War Fantasy"
  showed up as "Detailed Character Creation" — that was the name of a folder
  inside its archive.


### The card now tells you what to do with a mod

The guide answered "will this mod run", and said nothing about the rest. Yet the
author's own page holds far more: whether a new campaign is needed, where the mod
must sit in the load order, whether it can be removed mid-playthrough, what it is
known to break. All of it sat there in English, ten screens deep, and nobody read
it.

Now we read it — across every site at once: Nexus, the Steam Workshop, README
files and release notes on GitHub, ModDB. And we lay it out in two places.

**Before you install.** Beside our own verdict there is now a short list of the
things that change your decision: a new campaign is required, old files must be
deleted first, the mod only works in the campaign, it behaves differently on Xbox
or Game Pass, it does nothing on its own and exists only for other mods.

**How to install.** A new tab with the details: whether files need unblocking
after extraction, how early to load it, how it is configured, which key opens it,
what the author admits is broken, what you must not do in game, whether removing
it breaks the save, which languages ship inside.

Under each line stand the author's own words. This is his word, not our check,
and it says so.

### You can see where a requirement comes from

Requirements used to come from one place only — the mod's own manifest file. For
AD1259 that file is empty, while the page lists eight required mods, Realistic
Battle Mod among them; without it the game crashes on entering the campaign every
time. The guide said nothing.

There are three sources now: the mod's file, the "Required items" mark in the
Steam Workshop, and the author's words on the page. Requirements went from 6,342
to **10,149**.

Each one now says where it came from. What we read ourselves carries no note —
that is the guide's ordinary answer; what we repeat after somebody is marked:
"stated by the author on the mod page", "marked by the author in the Steam
Workshop".

### A file is no longer offered for a mod it does not contain

One page often carries several different mods. "Templar Armor" has three, each in
its own file: 90, 93 and 209 megabytes. Every card used to offer every file on
the page — you picked one mod and downloaded another, three times heavier. Fixed
for 487 cards.

### A mod the author walked away from

If the author said he no longer develops the mod, the card now says so. His
guesses that it "probably does not work" are not shown: whether it works is
answered by the version bar, and that comes from reading the files.

### More archives read

We take code and manifests out of an archive, but data files were only taken from
one expected folder. Translations and item packs put theirs elsewhere — straight
into another mod's folder — so such mods looked empty to the guide: they were
downloaded again on every pass and yielded nothing every time. There were fifteen
hundred such archives.

### "How to install" now speaks your language

The tab answers "what to click", "where to put it", "what it costs you" — and it
answered in English: the kind of note was translated, the note itself was not.
For a reader without English the tab said nothing at all.

The notes are now translated too, into all six languages of the Encyclopedia.
The author's own words are still there, folded under the translation as "the
author's own words on Nexus" — open and check any time.

The tab also became readable: the kind of note on top in small type, the answer
itself in large. It used to be the other way round.

### Dependencies: what to install, and what is merely load order

A mod declares two different lists: what it needs, and what it wants to load
after. The Encyclopedia merged them and labelled the result "requires". That was
a lie: "Crash Doctor" showed seventeen "dependencies" while requiring none of
them — all seventeen were load-order wishes.

The list is now split: "you need to install", "if you have these — load after
them", "parts of the game itself". And a plain line on top says how many hard
requirements there actually are.

### Requirements from the mod page stop getting lost

Authors list the required mods on their page. We recognised each one by its
link — and half the list vanished: "Anno Domini 1259" kept nine of thirteen.
Several rows in a row often share one link, and half the mentions have no link
at all.

Mods are now recognised by name, with the link as a hint. **3,320 links** were
recovered: 1,741 hard requirements, 1,169 optional, 399 incompatibilities. When
we have no card for a mod, the requirement is still shown — as a line without a
link: knowing it is needed matters more than being able to click it.

Third-party launchers were removed from requirements: that is a way to install,
not a mod the game needs.

### The answer right under the title

The card now opens with a row of short badges: does the mod work on your branch
of the game, how many mods you still need, can it be added mid-playthrough, does
removing it break the save. That used to take three tabs.

### Tabs grouped by four questions

There are ten of them and all are needed. You now pick the question first —
"about", "compatibility", "inside", "where to get it" — and only the tabs that
answer it are shown. A tab with a severe conflict or an author's warning carries
a mark.

### Cards no longer freeze on huge mods

Overhauls have up to two thousand conflicts with other mods, and the card drew
them all at once — the window froze for a minute. It now shows the first two
hundred, the heaviest ones, with a "show the rest" button underneath.

### You can see what a mod comes with and what it carries

Many mods ship inside someone else's archive and are not downloaded separately.
Only the database knew that. The card now has two lines — "comes bundled with…"
and "ships bundled inside…" — both clickable.

### Database version and date in plain sight

The bottom line of the main window now says which database is installed and when
it was built. The program and the data update separately, and without this line
there was no way to tell how fresh the catalogue is.

### Updates stop offering an older summary

The "What's new" window compared its summary with the server copy by checksum
only — and always found an "update", offering to replace a fresh summary with an
older one. The comparison now goes by release number.

### An "About the game" section: how many mods per version

The game ships in versions, and the first question before a playthrough is which
version to play so that mods work. Steam lists the versions; nobody puts a number
next to them.

The Encyclopedia now has an "About the game" section. It lists the versions of
Mount & Blade II: Bannerlord, the release date of each and, above all, how many
mods we know of for it. Below is the full list of Steam branches, service ones
included: 47 of them, each with the date it was last built. The section speaks all
six languages of the Encyclopedia.

### Fifteen hundred mods stopped being nameless

We read a mod's service file as text in one single encoding. Authors write in
several: Chinese, Turkish, older Russian ones. Foreign bytes quietly turned into
garbage, and the mod stayed nameless, versionless and without requirements - with
no error at all, the file "read fine".

The encoding is now detected. **8,014 files** came back.

### Four times as many conflicts between mods spotted

Mods change the game on the fly by hooking into its code. When two of them hook
the same place, they clash and the game behaves unpredictably. We used to see
12,269 such pairs; now it is **53,538** - the analysis now finds hooks written
inside the code itself, not only those declared up front.

## 0.9.4.3 — 26.08.2026

### You can now see which part of a mod breaks the game

The card used to list what a mod was missing: a long list of names from the
game's code. It never answered the real question — what to do about it.

Now the guilty part is named: "Breaks it: CustomSpawns — this game version has no
CultureCode". A large mod may have a dozen such parts, one of them breaks, and it
often turns out to be someone else's mod bundled in by the author — while a
fresher version of that mod works fine.

### The check now notices missing functions

We used to compare a mod against the game by the names of its parts. If the
developers removed a whole part, that was visible. If they removed a single
function inside it, the mod would load, run, and crash later — whenever that
function was finally needed. The guide said nothing.

Functions are now compared too: we re-read all 16,913 libraries in the catalogue
and collected two and a half million calls. For 959 mods the breakage is visible
**only** this way — by part names they looked healthy.

### Less lying in the "works" verdict

Three cases where we wrongly said a mod would run:

* a mod is made of several libraries, one breaks and the rest are fine — that
  used to be enough for "no obstacles found". The game loads all of them;
* the author accidentally bundled copies of the game's own files, and we judged
  the mod by those, though the game uses its own;
* the mod calls a library that this game version does not ship at all — meaning
  it brings its own, so there is nothing to blame it for.

### The author's word is no longer a verdict

Authors state on their page which game version they built for. That is useful to
know, but it is not a check: a five-year-old mod may still be tagged "for 1.5"
long after it stopped launching there.

Such a tag used to be painted green, on par with our own analysis. Now we say
"not checked" — which does not mean "does not work", it means we have not got to
that file yet. The file and its version stay in the card.

### No more handing an old game version a newer file

Libraries like Harmony ship a separate build per game branch: 1.2 needs one, 1.3
and above another. We were offering players on 1.2 a file with "Game 1.4.6"
right in its name — and the game complained, rightly.

A file built for a newer game version is no longer offered for an older one. The
other way round is fine: a build for 1.3 usually runs on 1.5.

### More files actually read

We read mod archives piecemeal straight from the site: only the code and the
manifest, no need to download the whole thing. But a file whose contents list we
had looked at — without managing to fetch the code itself — counted as read, and
never returned to the queue. There were 3,697 of those, and 2,491 had code inside.

Fixed. This round we finished reading 1,656 archives — the ones whose cards were
showing an unverified author's tag.

Because of this, 1,125 mods received a more cautious rating. They were breaking
before as well — we simply were not saying so.

## 0.9.3 — 25.08.2026

### You can see what is inside a file

A mod often arrives as one archive containing several folders: three for "Realm of
Thrones", nine for "More Troops Mod", thirty-six for one Chinese pack. All of them
must be installed or the mod will not work — and until now the only way to find out
was to unpack the file.

The file list now says what is inside each one: "3 folders inside: ROT-Content,
ROT-Map, Bannerlord.GeneralModdingPatches". The full list is under the cursor.

### A warning: this file or that one, not both

Some mods have several files marked as main by the author, while in fact they are
variants of the same thing: "Diplomacy (e1.5.8)" and "Diplomacy (v1.0.x–v1.2.x)".
People saw two equally important files and could not tell whether to take both.

Such files are now marked "one of several options". The mark is not a guess: we
opened both archives and found the same mod inside.

### "Nothing to download" instead of an empty page

294 mods are published as source code only — the author never built a ready file.
The guide used to send people to the project page, where they looked for a download
button that was not there.

The "Where to download" section now says so plainly: there is no ready file, the
mod would have to be built by hand.

### Mod names now in your language too

Almost every mod has an English name: `Improved Garrisons`, `Banks of Calradia`,
`Distinguished Service`. For anyone who does not read English the catalogue was a
wall of Latin script — the only way to tell what a mod did was to open its card.

Now the translated name sits under the original in small type. The name itself
stays large and where it was — that is how the mod is recognised and searched for
online — while the translation sits below it, small and dimmed: readable, but not
competing for attention. The mod window shows it too.

Translated into all six languages of the guide, and search uses it: type
"garrisons" in your own language and mods about garrisons come up, whatever they
are called.


### Search now speaks every language

The guide is translated into six languages, but search only understood English and
Russian: French "russe", Turkish "çeviri", Chinese "汉化" found nothing at all.
Search now covers all six — type in your own language.

### Which game version — no more guesswork

The guide reads the game version from the file name, and on ModDB that produced
errors: a mod has its own version number, and it looks exactly the same.
"Shokuho 1.0.0.10" was declared to work on game version 1.0, "CrashDoctor 1.7.4"
on 1.7. Six of seven such rows were wrong.

A game version now counts only when it is named next to a word about the game
("Bannerlord 1.2.11", "for 1.3.15"), the branch actually exists, and the file is
not older than the latest release. If nothing is said, the card stays silent
rather than inventing: "not checked" is more honest than a guessed "works".

The Old Realms is fixed to 1.3 along the way — it used to show 1.2, taken from a
patch from the year before last.

### More pictures on the cards

Nexus mods had a single cover image in the guide, while the site itself carries
plenty of screenshots. None of the ways we can ask return them — but authors paste
the same shots into the mod description. That is where we took them from: two and
a half thousand frames, and eighteen hundred mods no longer have a gallery of one.

### Translated mods: a hundred cards came back

We recognise a translation by the language at the end of its name — "RTS Camera
Russian", "MCM 中文". But translators often write the folder name without a
separator: `BannerKingsCNs`, `PlayerSettlementRU`, `FriendsWithBenefits.RU`. Those
mods were not counted as translations, so the guide wrongly decided their own page
did not belong to them: the card was left with no name, no description and no link
to download from. There were a hundred and ten. They are back now — with a name, a
description and an address.

### Links that led nowhere

Eighteen mods from ModDB carried the address of a GitHub page that does not exist.
The culprit was our own fallback: "unknown site — assume GitHub". An unknown site
now yields no link at all: better none than a promise that will not open.

### "Works" now also tells you what the mod risks

The card used to answer with a single word — "works" — and the explanation said
"everything the mod accesses is in place". Yet a mod can ship a dozen libraries, and
a couple of them may reach for things a newer game version has removed. The mod
started, part of it quietly failed, and the launcher — which checks the files on your
own disk — warned about incompatibility. The reference and the launcher appeared to
contradict each other.

Now the explanation behind "works" lists exactly what is missing and what will fail
because of it. No more contradiction: both programs say the same thing.

### Big mods are no longer left unexamined

Multi-gigabyte overhauls — Realm of Thrones, Shokuho, Empires of Europe, Westeros
Armory and some fifty more — never reached our analysis: the downloader had a 600 MB
ceiling. For the largest mods the reference knew only what the author claimed. Those
mods are now downloaded and unpacked in full, and their game version is read from the
file itself.

### A mod's files can now be opened

The Files tab shows which releases a mod has — the main one, patches, older
versions. There was nothing to open there: the list gave names and sizes and
nothing else. The file name is now a link to its page on the site it comes from.

### Mods from ModDB are no longer empty cards

ModDB hosts large overhauls that never reach Nexus: "Shokuhō", "Bannerlord Coop",
"Tales from the Age of Men", "The Long Night". Their cards opened empty — no list
of releases, no line about the game version, no demand figure. Now:

* **the game version is visible.** Authors put it in the file name ("Realm of
  Thrones 7.1 for Bannerlord 1.3.15"), and where they did not, they say it in the
  description or in a reply to players in the comments. That is where we read it;
* **demand is counted from page visits.** ModDB does not count downloads at all,
  so every mod from that site sat at the very bottom of any sorting — "Shokuhō"
  with its million and a half visits included;
* **the mod's releases are listed.** "Tales from the Age of Men" has eleven, the
  latest from 12 February; the Files tab used to show none at all;
* **ModDB links are dropped wherever the mod also lives on Nexus or the Workshop.**
  Downloading works there, while a ModDB file has to be fetched by hand through a
  browser. Where ModDB is the only place, the link and the release list stay.

### Fewer duplicate mods in the list

"Shokuhō" and "Shokuho", "Craft & Conquer" and "CraftAndConquer",
"Mount&Warcraft; Reborn" and "MountAndWarcraftReborn", "The Wheel of Time mod" and
"Wheel of Time Mod" — the same mod appeared as two rows because one name carries an
ampersand, another a macron, a third an extra word "mod". Such pairs are now one card.

The reverse was fixed too: strangers were evicted from families. "Simple Bank" was
listed as a variant of "Birke Mod", "Economy+" as a variant of "EconomyOverhaul" —
the author had shipped two of his mods in one archive and they stuck together.

### "Made for…" now points at the mod itself, not at one of its folders

Large mods come in several parts. "Realm of Thrones" has five, and add-ons for it
pointed at a part — "add-on for ROT-Content". That row could not be opened: a part
has no card of its own, so the reader hit a dead end. The row now names the mod
itself: "add-on for Realm of Thrones". 346 rows were corrected.

### Reworks no longer call themselves standalone mods

"Noble Titles Plus", "Dismemberment Plus", "Children Grow Faster Redux" and 65 more
called themselves standalone in one line of the card and reworks of someone else's
mod in the next. The card argued with itself. What is proven now wins: if a mod
reworks someone else's work, that is what it says.

### Translations can now be found by their language

Some translators drop their files into a folder that belongs to another language —
a Turkish translation on top of the English strings, for instance. Such a mod was
listed as English, and anyone filtering translations by language never found it.
Six Turkish, eight Spanish, one Czech and one Brazilian translation were lost this
way. The language is now also read from the mod's name, while whatever the archive
contains stays as it is.

### Three more mods stopped showing up twice

"RTS Camera", "Detailed Character Creation" and "Bannerlord Coop" each appeared as
two rows: a large mod ships several folders, and some of them carry the mod's own
name. Such folders are now gathered into one card. "Auto Sort Modlist" and "Bannerlord
Mod Template Creator" were merged too — they live on two sites at once and had been
counted as different mods.

## 0.9.2 — 21.08.2026

### For your game version — the actual mod file

Pick your game version on the left and the card answers straight away: "Your game is
1.2 → install mod version 1.5.7", with a "works" badge beside it and an "Open file"
button. The link goes to that very file, not to a page holding fifty others.

This matters most if you stayed on an older game version: many mods have their latest
build made for 1.4, which simply will not start on 1.2 — but the file you need is
still there. The encyclopedia now finds it. There are **27,963 such links, up from
693**.

Every row also shows the mod's own version, which was never displayed before.

### A "Not recommended" banner

Some mods now carry a large red warning on their card: we do not advise installing
this one, and it says why. We only write what we checked ourselves.

### The author's name is now a link

Click the author's name and you'll see the rest of their mods — their own work first,
translations after. If an author has only translations, the list says so. The same
person often publishes under several nicknames; those names are brought together.

### One mod, one card

The very first thing you used to see was two identical "Harmony" cards in a row.
"Camel Armor", "Dramalord", "Female Troops" and a couple of dozen more doubled up the
same way. Such cards are now merged: the rest appear inside as other variants of the
same mod. **Duplicates are down to 10 from 27**, and no record was lost.

### Mod history in your language

About half the lines in a mod's history arrived in hieroglyphs: with a Russian
interface you could find Chinese or Turkish text there. Fixed.

### Clearer answers on whether a mod works

Game version **1.4.8** has been analysed — everything that worked on 1.4.7 works on
it too, but now that is checked rather than assumed.

Naval mods were only partly checked: "Shipmaster Reworked", "Live Tides", "Training
Battles" and other War Sails mods could reach for something your game version does not
have, and the encyclopedia would not see it. The whole catalogue was re-checked.

Another **379 mods** gained or corrected a game-version mark — some of them now
honestly say "works on your 1.2" where before we only had the author's word. And 625
files had false marks removed, where the mod's own version number was being read as a
game version.

### "Add-on" — and now it says to what

It used to look like this: a card was labelled "Add-on" or "Patch", and nowhere did it
say which mod that referred to. There were 460 such cards. All were sorted out: for 48
the mod itself turned up and can be opened straight from the card; for another 304 the
mod is known by name, so that is what it says, and you can search for it. On 44 the
label was simply wrong — "WeaponGapFix", "TimeFixer" and the like fix a bug in the
game itself, not somebody else's mod.

### The encyclopedia is a third lighter

The database went from 310 down to **216 megabytes** — almost a hundred off. Nothing
was lost: the same mods, the same conflicts, the same descriptions in six languages.
Downloading and updating is noticeably faster.

### The encyclopedia starts even with no database

Before, when the database file was not where it should be, the encyclopedia showed an
error and closed — what to do next was left to you. Now it opens and offers to
download the database itself: one window, one button. And if the file is there but
cannot be read, it offers to fetch the database again. Your favourites and settings
survive that.

### Updating finally works the way it should

Three things that could leave an update half-done, or not started at all.

The "What's new" window showed raw markers instead of text. It now reads as text.

If one part of an update failed to download, everything was cancelled — including a
database that had already arrived. Now whatever did arrive is installed, the part that
failed is named in the list, and it comes with the next check.

The "What's new" summary could not be updated while the encyclopedia was open. The
installer now waits for every window to close and checks that the files really landed.

And if an update did fail and you pressed "Retry", the bar no longer jumps straight to
a hundred percent.

### Small things you can see

Markup that leaked in from author pages has been stripped from descriptions: "hold the
`[b]Q[/b]` key" now reads "hold the Q key".

116 mods got back descriptions that were missing — French suffered most. On 52 mods
the caption under the cover was English instead of Turkish. In English, French and
Turkish, words ran together at phrase joins. All fixed.

Service parts of the launcher itself have been removed from the catalogue — they are
not mods and have no business there.

## 0.8.5 — 18.08.2026

### Donations added

You can now support the encyclopedia: a "♥ Donate" chip in the header and a link at the bottom open a window with a choice — pay by card on a normal page or through Telegram, plus a copyable address. Donating unlocks nothing: every feature is and stays free.

### Subcategories: finding a mod is easier

Every section now has a second level. "Troops" used to be a wall of a thousand mods;
now you can narrow it to "Mercenaries", "Female units", "New factions" and so on.
Subcategories show both in the left menu (they expand under the section) and as chips
above the list. "All" still shows the whole section — nothing is hidden. Translations
are split by language: Russian, Chinese, Turkish, other.

### Clearer which game versions a mod is built for

The versions section of a mod card was redesigned. It used to be a table with empty
cells and technical wording. Now each game branch is its own row: a colour-coded
"works / partial / uncertain / won't run" badge, a plain-language explanation beside
it, and a "Details" button that opens the full breakdown of what and why.

### Clearer whether a mod runs on your version

The version bar is more honest now. A mod used to be marked "won't run" even when it works
fine. Now we tell apart: red — will not start; amber — one feature may fail, or uncertain;
green — no obstacles. False "reds" dropped fivefold.

### Almost everything analysed

We looked inside thousands of mods: 87% now show which game versions they were built for —
up from under half.

### Looked inside the Nexus mods

We downloaded and unpacked the mod archives from Nexus — for each you can see what it
changes in the game, which version it targets and what it conflicts with. Descriptions
and cards in every language.

### What a mod does even without a description

If the author wrote nothing, the card now shows what is inside: "Adds: 260 — settlements,
13 — troops." That spot used to hold a note saying there was no description.

### You can see when a mod has two cards

Some mods are published under two names — Harmony, for one. Both cards stay (the launcher
recognises a mod by its folder name), but each now points at the other.

### The full language list

A card now shows both the languages inside the mod and those a separate translation mod
covers. "Serve as Soldier" used to list Russian alone, though it has twelve translations.
Languages also stopped appearing twice in search: "KOR" and "KR" were two rows of Korean.

### Clear when a description covers the whole mod

Big mods are published as several parts on one page. The description of such a part now
says that the text is about the whole mod, not just that piece.

### Real names instead of placeholders

A few mods carried a name from the modder's starter template — "My Example Mod". The name
now comes from the mod's own page.

### You can see what an add-on is for

Cards marked "Add-on", "Rework" or "Translation" now always say what they belong to.
If the mod itself is not in the encyclopedia, the card says so — this spot used to be
empty, leaving no way to tell what was meant.

### The database is protected

The encyclopedia's files can no longer be opened by outside programs: the
catalogue, its add-ons and the summary are encrypted. Nothing changes for you —
it opens and works as before.

### "Why this section" is now in your language

Hover over a mod's section and you get a short explanation of why it sits there.
It used to be Russian only; now it is translated into every language.

### Switching the language redraws the cards at once

You switched the language and the cards stayed in the old one: the list was the
same, so the grid was never redrawn. The whole result is rebuilt now, whichever
language you read in.

### French

The encyclopedia now speaks French too — pick it where you pick the other
languages. Mod descriptions and history are being translated gradually; where
French is not ready yet, the card shows English.

### Mod history stopped losing entries

For 240 mods part of the history was missing: if the translation lagged behind by
even one entry, the rest vanished from the list. 355 entries came back, the newest
ones among them.

### No more repeats in a mod's history

A single date used to carry ten identical lines — "Fully translated.", "Internal
changes." — which is what happened when one release arrived as several files. Only
one line stays now, the one that carries the version number.

### "What's new" arrives with the catalogue

The summary used to update only together with the program itself: the catalogue
grew, but the window still showed last week. Now it arrives as its own small file.

### The language chip is about your language

Cards showed an "RU" chip even when the encyclopedia was in English. It now shows
your language — "TR", "简中" — and only when the mod files really carry that
translation.

### Mod history now says what came out

For mods whose author keeps no changelog, the history is now built from file
releases: "File "Bannerlord Coop Campaign v0.2.1 Client" was released" plus the
date. That covers 5,480 mods — they used to show only "the mod was updated".

### A translation no longer has a "Translations and variants" tab

You open a translation and it offers you a list of translations — with itself in
it. Translations no longer carry that tab: the original is shown separately as
"based on", and that is enough. Affects 2,543 entries.

### "Our projects" section

A separate entry now sits at the very top of the section list — the things we make:
the RickLauncher, Crash Doctor, RTS Camera Universal, the Russian translation of
The Old Realms and Lore-Hardcore. Their normal section stays as it was: a mod is
both in "Interface" and in "Our projects".

### How much of what is in the catalogue

A breakdown now sits under the header — mods, translations, add-ons, tools — and
the tooltip explains why the list holds fewer cards than mods: translations and
variants of a mod are folded into its original.

### The database updates in small files

Every catalogue update used to pull the whole 190 MB database. It is downloaded
once now, and changes arrive as small add-ons — the latest one is 26 MB, not 190.

### A mod was updated — and the card now says so

The summary said "updated by the author", yet the card said nothing about it: the
"History" tab was hidden whenever the author kept no changelog. The tab is there
now and tells what is known — when the mod was updated and on which site. It also
points to where authors sometimes write the details.

### Full mod names in the "What's new" window

A long mod name was cut off with an ellipsis even though there was room below it —
the row is as tall as the cover anyway. The name now wraps onto a second line,
just like the description beside it. The window itself is a tenth wider.

### Switching the language now switches everything at once

You switched the language and the cards stayed in the old one until the list was
reloaded. Everything switches together now: the cards in the catalogue, open mod
windows, the packs window, the "what's new" summary, the breakdown by kind and the
footer.

The same goes for the first choice: an answer given while the encyclopedia was
still starting up used to reach only half the window.

### The language is asked once, on the first run

The encyclopedia opens in English and asks straight away which language you want
to read it in. The question is not a separate window: the encyclopedia itself dims
and the choice stands bright in the middle of it. Language names are written in
those languages — "Русский", "Türkçe", "简体中文".

Your answer is remembered and you will not be asked again. Changed your mind? The
language is still in Settings.

It used to be guessed from your Windows language, and it guessed wrong both ways.

### Words no longer run together

"42 mods are available for itfrom 43" — the translation had lost the spaces where
the encyclopedia joins phrases together. All languages were checked at once:
**1,084 such places**, none left. The phrases themselves were reworded too.

### Russian no longer leaks into the other languages

You picked English, Turkish or Chinese — and the update window, the tooltips, file
sizes and dates stayed Russian anyway. Everything is translated now: window titles,
buttons, field hints, update progress ("downloading", "checking signature"), error
messages, number suffixes and month names in dates.

Numbers became local too: where Russian writes "6,2 млн", English now writes
"6.2M", and digit separators follow the language you picked.

### Word endings no longer trip up the search

"европ" found Empires of Europe 1100, but "европа" did not — same word. The
ending no longer matters: "европа", "европы" and "европе" now give the same
results. Same for "торговля", "экономика", "лошади" — those used to return two
or three mods instead of a hundred.

### Finds what is called by another word

Type "краш" and Crash Doctor shows up, even though its description says
"вылеты" (crashes). When your words find very little, the encyclopedia adds what
you were most likely looking for and says so above the list: "also searched for
'cras'". Whatever your own words found stays where it was.

## 0.7.1 — 13.08.2026

### Search understands Russian

Type "беременность", "гарнизон", "караван", "вылеты" and you get the mods about
them. Russian words used to find nothing at all: mods are named in English and
we only searched the English text. Search now looks at our Russian descriptions
as well.

### Forgot to switch the keyboard layout? No problem

Type "рфкьщтн" instead of "harmony", or "Ифттук Лштпы" instead of "Banner
Kings", and the encyclopedia works out what you meant. A line above the list
says what it actually searched for.

It also understands names spelled by ear: "хармони", "баннер кингс", "диплома".

This only happens when what you typed found nothing: what you wrote always
matters more than our guess about it.

### The section tooltip explains again instead of shrugging

Hovering over a mod's section showed "category not determined" — on every mod,
even where the section had been worked out and explained. The real explanation
is back: "a tool that fixes crashes and cleans save files".

## 0.7.0 — 12.08.2026

### Mods sorted into sections again

A mod's section is no longer picked by searching for words in its description —
the whole entry is read instead, and all nine and a half thousand mods have been
gone through this way. Every third one was in the wrong place.

The worst case was `Crash Doctor`: it fixes crashes and cleans save files, yet
it was filed under "Translations" because of the line "EN/RU/中文/TR" in its
description. It sat there alongside `Aggregated Income`, `No Fog Of War` and a
mod that adds a Chinese spear.

"Miscellaneous", where everything unclear used to end up, shrank fourfold —
from 773 mods to 178.

### You can see why a mod is in its section

Point at the section name in an entry and a short explanation appears: "a tool
that fixes crashes and cleans save files", "translates the Improved Garrisons
interface into Russian".

### Translations now say what they translate, and into which language

A translation used to be just "a translation". Now it says which mod it
translates and into what language — and there are nearly two and a half thousand
of them in the encyclopedia.

### "Where to download": each site has its own demand figure

Every row used to show the same number — the Nexus download count, credited to
GitHub and ModDB as well, where the mod is taken far less often. Now each site
shows its own: downloads for Nexus, subscriptions for Steam, page visits for
ModDB (it does not publish download counts at all).

### The mod's version instead of a date

For mods whose author tags releases by day ("2026-07-28"), that date was shown
in the version column. It now shows the real version number — the same one the
launcher displays.

## 0.6.1 — 11.08.2026

### The "What's new" window is no longer empty

The catalogue summary never actually reached you: it was built on our side but did
not make it into the update, so the window opened blank. It now comes with the
program — in all five languages.

## 0.6.0 — 11.08.2026

### The whole encyclopedia now speaks your language

Pick a language and the entire window changes at once: the list of sections on the
left, the captions above the mod list, the dropdowns at the top, the search hint,
the tabs inside a mod's card ("Description", "History", "Files"), the captions in
favorites and in packs.

Half the captions used to stay in Russian, and the list on the left did not change
at all until you restarted the program. Over a thousand captions are translated
now — nearly everything you see on screen.

The "What's new" window speaks your language too: both the release headlines and
the lines about what happened to each mod. They used to be Russian only.

The short line under a cover — the one that says what a mod does — was often
missing in English, Turkish and Chinese: a Russian line stood there instead. It is
now there for almost every mod in all five languages. The same goes for a mod's
change history.

The long caption under the heading no longer breaks off mid-word: if it does not
fit the window, it wraps onto a second line.

You can still add your own language yourself — in the `Lang` folder next to the
encyclopedia.

### A mod's card now shows only the tabs that have something in them

There used to be nine tabs on every mod, and for most mods half of them were
empty: you click "Conflicts", "Contents", "Translations and variants" and each
time you read that there is nothing. Only the filled ones are shown now — three or
four on a simple mod, seven or eight on a big one.

When data appears, so does the tab: this is checked every time you open a card.

### Covers for the most popular mods now ship with the program

Every cover used to be fetched from the internet while you scrolled, so on a slow
connection the first screens stayed blank for a while. Covers for the thousand
most-downloaded mods now sit in the encyclopedia's own folder and appear at once.
The rest load as before and are kept on your machine, so the second time they show
up instantly.

### Stray asterisks removed from descriptions

Descriptions sometimes read "fixes \*\*Armour\*\*" — asterisks used to highlight a
name. Some places stripped them, others did not. They are gone everywhere now.

### Fifteen mods found their sections

Fifteen mods belonged to no section on the left: they showed up in the full list,
but pick a section and they were nowhere. They are in the right place now.

For another 149 mods the section in the list and the section on the card disagreed:
a mod sat under "Translations" but its card read "Interface". Both match now.

### A mod's change history — a new tab

Open a mod: next to "Description" there is now **History**. Versions run from the
newest to the very first: when it came out and what changed in it.

We retell it in our own words and keep it short — what a player will notice: new
content, fixed crashes, changes to difficulty, support for a new game version. If a
mod has four hundred versions, you get all four hundred.

### "What's new" — what changed in the encyclopedia itself

A button in the header next to Favorites. It shows which mods appeared, which got
updates, what now works on a new game version, what authors took down. Click a line
and the mod's card opens.

This is about mods. What changed in the program itself is still in the update window.

### Cards in the list: clear from three lines

Descriptions in the list used to break off mid-word for almost every mod. Scroll
through a hundred and you understood none of them until you opened one.

- **Three lines instead of two**, in a larger font.
- **List descriptions have all been rewritten.** Short and to the point: what the
  mod gives the player. The clutter is gone — the mod's own name (it is written
  above anyway) and the words "for Mount & Blade II: Bannerlord" (the whole
  encyclopedia is about this game).
- The full description is still there: hover over the text to see all of it.

### Three things at the bottom of a card instead of six

There used to be up to six badges at once, and the row read like a dashboard. What
is left is what you choose by:

- **what this mod is to the one you are looking for** — "★ original", "overhaul",
  "add-on", "patch" or "translation";
- **RU** — whether the mod includes Russian;
- **how many people downloaded it**.

The "☣ virus" and "taken down" warnings stayed: you should know that before you
install. The rest moved into the mod window, where there is room to explain it.

### The list no longer huddles in the middle

On a wide window there were empty margins on both sides. The row now uses the full
width, so a wide window fits more cards. Covers are not stretched or squashed by it.

## 0.5.0 — 9 August 2026

### A "report a problem" button — the pencil on a card

Found something untrue on a card? Press the **pencil** next to the star (there is one in
the mod window header too). A window opens: write what exactly is wrong and press Save.
Text is optional.

- 📝 Messages accumulate in **one file**, `report.json`, next to the program. Nothing is
  sent anywhere by itself — you forward the file yourself when it fills up.
- 🔍 Along with your text, the **whole card** is saved: where every field came from, what
  proves the mod's kind, which pages it has and in what role, its links, game branches,
  family and languages. Plus **where you were looking from** — the query and the filters.
- 🩺 That is enough to find the cause and, more importantly, to check whether **other mods
  have the same error**: one report almost always means dozens of the same kind.
- ✍️ **One mod, one message.** A successful save is no longer announced — the window just
  closes. The pencil on a mod you have already written about is **lit**, and pressing it
  again puts your previous text back into the field: amend it and save. The entry replaces
  the old one, so you never write about the same thing four times over.

### What the first reports already turned up

- 📥 **A stranger's link under "where to download".** The Russian translation of The Old
  Realms listed the page of an entirely different mod — the link had been matched by name
  alone. Such links are gone: "where to download" is a promise that you press it and get
  **this** mod.
- 📚 **"Add-on for Harmony" — on Harmony itself.** The four most-downloaded libraries in
  the reference — Harmony, MCM, ButterLib, UIExtenderEx — claimed to extend somebody
  else's mod. The cause: a large bundle ships its own copy of the library, and we took the
  copy's manifest for the library's own. A library is now neither a derivative nor a base:
  "add-on for Harmony" is true of every mod with code and therefore says nothing.
- 🇮🇹 **"Rumour Has It" is not an Italian translation.** The last word of the name was read
  as a language code, so a standalone mod landed under "Translations" and lost its
  original-work badge.
- 🗂 **Fifteen unrelated translations in one "family".** A translation named after nothing
  but its language ("Russian Translation Improved Garrisons") lost everything except the
  word "Russian" once the name was cleaned — and such translations piled into a shared
  family. Results show one card per family, so the rest were not shown at all.
- 📊 **Demand now counts every platform, not just Nexus.** A Workshop-only mod showed nothing
  and ranked below a mod with three downloads: "The Old Realms — Russian translation" with
  13,358 subscribers looked like nobody wanted it. There are **782** such mods. The card now
  shows the combined figure, the tooltip breaks it down, and the "where to download" list gives
  every platform its own "demand" column — downloads for Nexus, subscriptions for Steam. They
  cannot be added into a "number of people", and the card says so plainly: one player may well
  have both downloaded and subscribed.
- 🆔 **A mod's ID is visible and copyable.** The mod window header shows its identifier
  (`TOR_Environment`); clicking copies it. The same is on a card in the results via the right
  mouse button: "copy mod ID", "copy name". A name does not identify a mod — the catalogue has
  twenty-five pairs of identical names — but an ID always does.
- 🏷 **"Where to download" no longer confuses a mod's own page with a bundle that ships it.**
  555 links now carry the role "included in a bundle", and a card takes its author and cover
  art from its own page: "Danger's Recruiter" was showing the author of "Ralf's Recruiter",
  and "Detailed Character Creation" the cover art of "Body Sliders".
- 🧾 **The "Translations" section and the "translation" label now always agree.** Filtering by
  the section used to show mods that are not translations, and a translation could not be
  found in its own section.
- ⭐ **The "★ original" badge now listens to the mod's passport.** Twenty-seven cards carried
  it while the reference itself called them a translation, an add-on or a patch.
- 👑 **A family where everyone was a translation.** "Aggregated Income" (119,593
  downloads), "Crash Doctor" and "Castle Conscription" were translations of themselves:
  the site's "Translations" section is used by ordinary mods too. Such a family had no
  head left, and a Turkish localisation came first in results instead of the mod.


### The encyclopedia now knows WHAT a mod is

The section on a site is picked by the author from a list, and it lies: a mod that
reworks combat sits under "Translations", and half the catalogue under "Misc". Every
card now carries a **passport**, derived from evidence rather than from words.

- 🪪 **What the thing is.** The card carries a label: **translation**, **add-on**,
  **compatibility patch**, **rebuild**, **library**, **tool**, **assets**. A
  standalone mod carries none — that is just an ordinary card. The tooltip says what
  proves it: "the archive contains only language files", "requires another mod", "code
  only, declares no game records of its own".
- 📚 **Sections recomputed from archive contents.** Not from the name and not from the
  author's word, but from what the mod declares in the game: items → "Armour and
  weapons", troops → "Troops", settlements → "Settlements and sieges". **2,052
  sections** were rewritten.
- 🔢 **9,463 cards** classified: 5,707 standalone mods, 2,172 translations, 914
  add-ons, 327 rebuilds, 111 tools, 101 patches, 64 asset packs, 21 libraries. 46
  remain undetermined.

### "What there is for this mod" — in one strip

Type a mod's name and a breakdown appears above the results: **the mod itself ·
translations 20 · add-ons 30 · patches 2 · rebuilds 9 · other builds 5 · the rest 6**.
Clicking keeps only that group; clicking again clears it.

- 🔗 **Links are computed from files, not from names.** A translation writes its files
  into the folder of the mod it translates — that is how we know which one. 3,238 links
  across 2,681 cards.
- ↔️ **Navigation both ways.** Open a translation and the card says which mod it is for,
  with a link. Open the mod and you see everything made for it.
- ⚠️ Inside the breakdown, cards are listed **individually**: family folding is off
  there, otherwise twenty translations would collapse into a single "+22" row.

### Search finally shows the mod itself, not the things built on top of it

Searching for the name of a big mod returned fifty cards, and the mod itself was
nowhere near the top. There were three separate causes.

- 🔎 **While searching, the order comes from the match, not from popularity.**
  For "Realm of Thrones" the first card was the submod "New Villages for Realm of
  Thrones" — with 30,703 downloads it genuinely beat everything around it. Now an
  exact name match rises to the top, and popularity decides only where there is no
  exact match. The new order is called **"by match"** and comes first in the list.
  While the search box is empty it behaves exactly like "by demand", so the
  catalogue looks the way it did before.
- 🔎 **A name is recognised however it is typed.** "Banner Kings" and
  "BannerKings" are the same name: a space no longer stops a match from counting as
  exact. Mods known by a short name are found too — "RBM" now leads to "(RBM)
  Realistic Battle Mod Bannerlord" instead of to patches for it.
- 🔎 **A mod is also found by the name of its page on a site.** A mod has one name
  on its card, but several pages, and those pages are named differently.

### Six mods are back in the encyclopedia — including the two biggest

**Realm of Thrones** (1,438,766 downloads) and **CA - Eagle Rising - Rise of an
Empire** (871,654) were missing entirely. In their place sat nameless folders from
their archives — no description, no cover art, no numbers.

The reason: a big mod consists of several folders, and none of them carries its
name — for Realm of Thrones they are `ROT-Core`, `ROT-Content`, `ROT-Dragon` and
`ROT_Map`. The rule "a page that merely carries a mod inside its archive gives it
neither a name nor numbers" fired against the mod itself: its own page counted as
somebody else's bundle.

- 📇 **The mod has one card again** — with author, description, cover art and
  numbers, and the folders of its archive are shown inside it as parts.
- 🌐 **Translations moved back to the original.** Seventeen translations of Realm
  of Thrones had been attached to the patch "Realm of Thrones 6.0 - RBM Patch": the
  head of a family was picked by download count, and the original had none at all.
  The family is now built around the mod: 23 entries in one card instead of five
  separate piles.
- 📇 **A second card for the same mod from another site is no longer created.** A
  ModDB page with no download counter at all, named exactly like the mod, is a
  second trace of that mod — not a second mod.

### The results now say what each row is

Fifty rows for one query all looked alike: the mod itself, patches for it, submods and
translations. Cards are labelled now.

- ⭐ **"★ original"** — the mod itself, the one translations, forks and rebuilds come
  from. The tooltip says how many there are.
- 🔁 **"rebuild"** — a re-upload, continuation or extended version of somebody else's
  mod. The tooltip names whose.
- 🌐 **"translation"** — as before.

### One mod, one card

The encyclopedia was creating two cards for one mod and never noticed.

- 📇 **One mod page means one mod.** "Bandit Militias" and `BanditMilitias` — 192,713
  downloads each, the same page; `Bannerlord.NoFogOfWar` and `NoFogOfWar` — the same
  story. Such cards are merged, and the second one opens inside the first. Merging
  requires two proofs — a shared page **and** agreeing names: the page alone is not
  enough, because a page can be attached to a mod by mistake.
- 📇 **A family has one head, and it is the mod itself.** "Economy+" and
  `Bannerlord.EconomyOverhaul` are one mod with the same 25,528 downloads, and the
  results showed it under the name of its folder. On equal demand the card with a
  human name wins.
- 📇 **A mod's folders no longer walk around as separate rows.** `BLTAdoptAHero`,
  `LOTRLOME_Armory`, `Alliance.Editor` are parts of mods, yet they looked like
  separate things with no name, no description and no cover art.

### Smaller things the review turned up

- 📥 **"Where to download" no longer loses sites.** Realm of Thrones was left with a
  single link — Nexus — even though the mod is also published on ModDB: after the
  family merge that page became kin, and the download location vanished from the card.
  Variants' pages are shown now, one row per address. Translations and forks are not:
  they distribute their own work, not this mod.
- 🏷 **The label row no longer runs into the download count.** The "original" label and
  the kin count are one label now, and in a crowded row the label shrinks to a bare
  "★" — the tooltip stays complete either way.

### Another 74 mods came back — and a million and a half downloads with them

The same trouble as Realm of Thrones, from the other end: **a mod's own page counted as
somebody else's if it was named "Fix" or "Patch"**. That is how "Character Reload Fix"
(714,180 downloads), "Pregnancy Control Continued" and "RTS Camera support continued"
disappeared — a mod whose job is fixing another mod names its page exactly like that. A
page now counts as somebody else's only if somebody else actually claims it.

Along the way, **a submod stopped counting as a translation** — because of one word in a
list of markers it lost its name, its description and its cover art.

### Folders are no longer nameless rows

**436 cards were named after a module folder** — `BLTAdoptAHero`, `LOTRLOME_Armory`,
`Alliance.Editor`. The name now comes from the mod's own page, and the folder merges into
its card by the ordinary rules. 328 remain, and there is nothing to fix there: the page
name *is* the folder name — that is what the author called it.

### A version strip for mods without a `Module.Id`

The strip was empty for **all 5,345 Nexus cards** known only by their page: branch data
was collected only for modules we had taken apart. That read as "no version fits", while
it meant "we did not look". The branch now comes from what the author wrote on the
uploaded file, and it is marked as **the author's word**, not as something we verified.

### The "original" label no longer goes to just anything

The first version of the label treated the head of a family as the original — and the
head of its own family can be a patch that happens to have a translation. The label was
worn by "Diplomacy (Fork)", "The Old Realms - Music Submod", "Blood and Smoke - RBM
Patch". It now goes to nothing whose name gives away derivative work, nothing from the
"Translations" section, and nothing known to be a rebuild of, or an add-on to, another
mod. Forms like "(Forked)" glued to a bracket are recognised too.

### "Add-on" and "rebuild" are different labels

A rebuild is installed **instead of** the original, an add-on **alongside** it, and one
caption cannot say both. The encyclopedia now asks about each separately, and the card
carries whichever label is true. The mod an add-on is made for lights up as
**★ original**.

### A check that did not exist before

There is now a command answering the blunt question: **does the encyclopedia find a
mod when you ask for it by name?** Every mod's name is fed to the search, and we look
at whether that mod comes first. This is what found everything above: of 2,397 mods
with 2,000+ downloads, 84 did not come first; after the fixes, 3 — and all three turned
out to be genuinely different mods sharing a name.

## 0.4.2 — 07.08.2026

### Cover art: some machines had none at all

We tracked down the case where the catalogue stays a wall of letters even though
the internet works fine. The cause was an unexpected one, and the encyclopedia was
not to blame.

**The site serves cover art as WebP** — from links that end in `.png` and `.jpeg`.
Every third picture arrives that way. Windows 11 understands WebP out of the box;
earlier and trimmed-down builds only do if a separate extension is installed. Where
it is not, no picture appeared at all: the files downloaded correctly — 224 MB of
them on one machine — and every single one was discarded as an unknown format.

- 🖼 **The encyclopedia no longer depends on the Windows codecs.** When the system
  cannot cope, it decodes the picture itself. As a bonus it understands WebP
  everywhere, including machines where Windows has never heard of it.
- 🩺 **A check at startup.** A test image built into the program is decoded first;
  if that fails both through the system and on our own, a **"NO COVER ART"** badge
  lights up in the header with an explanation, instead of a silent empty catalogue.
- 🔎 **The `--check-images` report now names what actually arrived** — judged by the
  file's first bytes rather than its name. "The system does not understand this
  format" and "the site sent something that is not a picture" used to look like the
  same single error while needing completely different fixes; that is exactly where
  the previous investigation stalled.

### The window no longer greets you with emptiness

The database weighs a hundred and fifty megabytes, and the first page takes a second
or two to assemble. The window used to be open and empty for all of it: filter bars
with no values, a grid with no cards. A loading screen with a progress indicator now
covers that moment and says what is being done — an empty window reads as "broken",
not as "coming right up".

### Favourites

You can now set mods aside for yourself. Until today a shortlist had to live in
your head or in a text file: the encyclopedia could show nine thousand other
people's mods and none of your own.

- ⭐ **A star on the card.** Click it in the catalogue or in the mod window's
  title bar (Ctrl+D) and the mod is yours. A marked star burns gold, an unmarked
  one stays grey and dim: you can tell at a glance, and the artwork stays readable.
- 📝 **A note per mod.** "Install after RBM", "breaks sieges", "wait for the next
  release" — the things you will not remember six months from now. The panel for
  it opens the moment you click the star, rather than hiding somewhere else.
  Searching your favourites searches the notes too.
- 🎮 **Game version as buttons, not a dropdown — and you can pick several.** A mod
  usually runs on three or four branches, and forcing a single choice throws away
  exactly what you meant to record. The colour tells you what to expect before you
  choose: solid green — the author released a build for that branch, green outline —
  nothing blocks the mod but there is no build to download, red — proven not to
  start there. The same colours as the version strip in the catalogue. The line
  below the buttons breaks the choice down: "won't start on 1.2 · builds exist for
  1.4, 1.3".
- 🗂 **"What about it".** Want it, already installed, later, didn't work out. A
  shortlist is built over weeks and installed in batches; "already installed"
  separates what is done from what is planned, and "didn't work out" keeps the
  note about why.
- 🔍 **Filtering inside favourites** — by section (Troops, Combat, Overhauls), by
  game version and by state. Sections are counted from the favourites
  themselves: no "Graphics and sound · 0" in a list of twelve mods.
- ⚖️ **Set review.** Above the list sits the reason favourites exist at all:
  which game version the whole set fits best, which pairs clash and over what,
  which required mods are absent, which ones the site's antivirus flags. The ⓘ
  button opens the detail. The same reasoning the encyclopedia applies to other
  people's collections, applied to yours.
- 📦 **Favourites → a file for the launcher.** "Save .rickpack" turns your
  shortlist into a pack the launcher installs in one go. How many mods were left
  out, and why, is stated plainly.
- 💾 **Export and import** — carry your favourites to another machine or keep a
  spare copy. An imported list is merged into yours rather than replacing it:
  your own notes are never overwritten.
- 🕳 **A mod vanishing from the encyclopedia does not erase your entry.** When an
  author pulls a page, the row is labelled "no longer in the encyclopedia" — but
  the mark and the note stay. Only you can delete them.

Favourites live outside the database, in your own user folder, and survive every
encyclopedia update. The file is written so that a sudden power cut cannot lose
it, and a copy of the previous state is always kept beside it.

## 0.4.1 — 07.08.2026

### Cover art in the catalogue

The main thing in this release. For some readers the catalogue opened empty — letters
instead of covers — and stayed that way until the program was closed.

- 🔁 **A cover that fails once is no longer lost for good.** The catalogue asks for
  sixty pictures in the first second after launch, while the machine's network is still
  coming up. That burst used to be remembered as "no picture" for the rest of the
  session, even when everything was reachable a second later. Loading is now retried,
  and a failure is forgotten after a minute.
- ⬛ **A missing screenshot no longer leaves a black square.** The frame appears
  together with the picture rather than before it, so it promises nothing it cannot
  show.
- 🩺 **If there are still no covers**, start the encyclopedia with `--check-images`. It
  names the step that actually failed and writes a report next to the database — send
  that line to support instead of describing the problem in words.

### Where download links lead

- 🔀 **A translation is no longer passed off as the mod itself.** For 89 mods the "Where
  to download" tab listed other people's pages. `Fourberie` had three in a row: the
  first link led to a Russian translation, the second to the mod, the third to a Russian
  fork — with nothing to tell them apart. Such pages now sit in the "Translations and
  builds" tab, where they belong.
- 🏷️ **You can see the page title, not just its number.** Instead of "mod no. 10130" the
  row reads "Fourberie RU"; the number stays below in small type, because that is how a
  page is found after its author renames it.

### Descriptions and the mod card

- ✍️ **254 descriptions rewritten.** They retold the last paragraph of the author's page
  — requirements and hotkeys — instead of saying what the mod does at all. A check for
  such fragments is now part of building the encyclopedia.
- 🈯 **Every entry type in the "Contents" tab is spelled out.** `crafting_piece` now
  reads as what it is. The English name stays beside it: that is what you search for in
  the mod's own files.
- 🕯️ **"The author has not released updates for 0 years" is gone.** A span of silence is
  named only when it is the actual reason.

## 0.4.0 — 06.08.2026

First build for testers.

### A reference, not a catalogue

- 🔎 **Nine thousand mods**, filtered by game branch, category, language and demand.
- ✅ **Compatibility is checked by reading the files themselves**, not taken from the
  authors' word. Beside every arguable claim sits an ⓘ button: where the conclusion came
  from and how firm it is.
- ⚠️ **"Not checked" is never passed off as "does not work".** An empty cell means an
  absence of information, and it says so.
- 🧩 **Dependencies, conflicts and contents**: what to install alongside, which mods
  contend for the same game records, and what the mod adds to the game.
- 🌍 **Descriptions in five languages** — Russian, English, Turkish and two Chinese.

### Cards open side by side

- 🪟 **Up to ten cards at once.** Put a mod and its dependency next to each other, or
  compare an original with its translation. Following a link opens a new window instead
  of closing the current one.
- 🔗 **You can see what a mod is based on.** A translation, fork or re-release carries
  its original above the description: name, a link to its card and a short summary — so
  that "an updated version of the original" means something to someone who never heard
  of the original.
- 🚪 **A link promises a jump only where there is somewhere to go.** Where there isn't, a
  tooltip says why: a module of the game itself, a withdrawn mod, a page never found.

### Mod collections

- 📦 **Steam Workshop sets are analysed**: what will fail to install, what will clash,
  and which game version the set was built for.
- 🎯 **The set's target version is derived from its contents** — the site itself never
  publishes it.

### It updates itself

- 🔄 **The program and the database update separately.** A change in the program does not
  force a database re-download, and the other way round.
- ✨ **Nothing pops up over what you are reading**: an update announces itself with a
  badge in the header, and the window opens when you click it.
- 📜 **You see what changed before downloading.**
- 🚀 **Downloads use several connections** — the database arrives in about a minute
  instead of eight. Interrupted, it resumes where it stopped instead of starting over.
