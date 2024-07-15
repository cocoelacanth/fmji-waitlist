# Forumoji Waitlist

The following is a list of emojis that have been contributed to the Forumoji project, but have yet to be added to the [GitHub repository](https://github.com/vercte/forumoji) or uploaded to the official Cubeupload account.

As of **July 3rd, 2024,** the backlog is **empty!**

The "URL" column contains hyperlinks to each emoji on Cubeupload, enabling these emojis to be used on the Scratch Forums.

|Codepoint|Emoji|Name|URL|Contributor(s)|Date Contributed|
|:-------:|:---:|:---|:-:|:-------------|:---------------|
<!-- |`XXXXX`|![](emoji/15x15/xxxxx.png)|Name|[🔗](URL)|Author|Date| -->

<sup>* Updated design for an emoji already present in the main Forumoji repository. This emoji is not included in the waitlist `emoji.json`; its entry will need to be updated manually.</sup>

## Adding to Forumoji
Within this repository are some files that have been provided to simplify the process of adding the new emojis to the main repository.

Below is a list of important assets, as well as an explanation of how to implement each.

* `emoji.json` is a JSON object containing codepoints and authors for every emoji on this list, excluding updated designs for emojis that have been contributed before.
  * Append the contents of this file to `assets/emoji.json` on the [`main`](https://github.com/vercte/forumoji) branch
  * Copy the contents of the combined `assets/emoji.json` file into `assets/emoji.js` on the [`gh-pages`](https://github.com/vercte/forumoji/tree/gh-pages) branch
* `emoji/15x15` contains every emoji on this list in PNG format, ready to be dropped in to the main repository as-is.
  * Copy everything in this folder to `assets/emoji/15x15` into `assets/emoji/15x15` on the [`main`](https://github.com/vercte/forumoji) and [`gh-pages`](https://github.com/vercte/forumoji/tree/gh-pages) branches

Beyond just copying these files over, also take note of any emojis marked with an asterisk * in the waitlist above. These are updates to existing emojis, and adding these may involve updating the listed authors in `assets/emoji.json`.