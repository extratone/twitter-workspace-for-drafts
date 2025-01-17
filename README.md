# Drafts Twitter Client
While not a full-fleged Twitter client when it comes to interacting and reading tweets, Drafts text manipulation capabilities have many advantages. When it comes to the drafting of new tweets, Drafts can shine with features like automatic replacement of common abbreviations, or creating a long Twitter thread in one go (Tweet Storm).

<img src="https://github.com/chrisgrieser/twitter-workspace-for-drafts/blob/main/Draft%20+%20Twitter.png?raw=true" alt="Icon for Drafts Twitter Client" width=15% height=15%>

**Composing**
- Compose tweets with Twitter Syntax Highlighting (@mentions, #hashtags, ...).
- Send tweets directly from Drafts.
- Automatically attach a hashtag when sending. Useful when tweeting repeatedly from a certain event
- `Tweet Storm`: Send a longer text automatically as a Twitter thread.
- On iOS, easily quickly insert `#` and `@`.

**Overcome the 280-character-limit**
- Visually indicate character limit.
- Insert common abbreviations (e.g. `with` ➞  `w/`) to stay under the character limit. Currently only for [English and German](https://github.com/chrisgrieser/twitter-workspace-for-drafts/blob/main/shorten_list.csv), but you can suggest  additions in other languages. Feel free to create an [issue](https://github.com/chrisgrieser/twitter-workspace-for-drafts/issues) or make a pull request.
-  `Emojify`: Save even more characters by replacing your text with various emojis (e.g. `dog` ➞ `🐶`). Define your own emoji replacement.
-  Automatically suggest splits for the Tweet Storm.

**Download Tweets**
- Download faved tweets of any user.
- Download Twitter search results.
- View and print them in Markdown.

**Use with Drafts**
- Tweets sent from Drafts are naturally archived in Drafts. This makes them easily searchable and allows you to run other Drafts acitons on them.
- Call the Workspace via `Load Twitter Workspace` action to automatically apply the tags, syntax and visual needed for this workspace.
- _Advanced Users:_ Call the `Load Twitter Workspace` action via URL Scheme to trigger Drafts with the Twitter Workspace from anywhere, e.g. with Alfred or Keyboard Maestro and the following URL Scheme `drafts://x-callback-url/runaction?&action=Load%20Twitter%20Workspace`

<img src="https://i.imgur.com/xSYEbKe.gif" alt="Showcase: Shorten Text" width=50% height=50%>

---

## Setup
- If you are not familiar with using Drafts to send tweets, read [the primer in the Drafts Forum](https://forums.getdrafts.com/t/using-twitter-with-drafts/109).
- Install the [Workspace](https://actions.getdrafts.com/w/1mN).
- Install the [Action-Group](https://actions.getdrafts.com/g/1mP).
- Install the [Syntax](https://actions.getdrafts.com/s/1mM).
- I recommend installing all three, as they are made to work well with each other.
- Optionally you can also  download the [Alfred Workflow for the Twitter Workspace](https://github.com/chrisgrieser/twitter-workspace-for-drafts/blob/main/Twitter%20for%20Drafts.alfredworkflow?raw=true) to begin tweeting from anywhere.
- _Theme:_ I recommend [Northern Light](https://actions.getdrafts.com/t/1jC) and [Northern Dark](https://actions.getdrafts.com/t/1jD) by kimonostereo as they match Twitter's aesthetic. 

## Credits
- The syntax is derived from [nahumck's Tweet Syntax](https://actions.getdrafts.com/s/1iw) and adapted to work with the actions of this Workspace.
- Numerous actions (Tweet Storm, Downloading Favs, Emojify, ...) are adapted versions from [agiletortoise](https://agiletortoise.com/)'s actions.
- This Workspace has otherwise been created by [Chris Grieser](https://chris-grieser.de/)
- ...and of course you can follow me on Twitter 😉️ [@pseudo_meta](https://twitter.com/pseudo_meta)
