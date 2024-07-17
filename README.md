# Forumoji Waitlist

The following is a list of emojis that have been contributed to the Forumoji project, but have yet to be added to the [GitHub repository](https://github.com/vercte/forumoji) or uploaded to the official Cubeupload account.

As of **July 16th, 2024,** the backlog contains **5 emojis,** dating back to **July 4th, 2024.**

The "URL" column contains hyperlinks to each emoji on Cubeupload, enabling these emojis to be used on the Scratch Forums.

|Codepoint|Emoji|Name|URL|Contributor(s)|Date Contributed|
|:-------:|:---:|:---|:-:|:-------------|:---------------|
|`1F98F`|![](emoji/15x15/1f98f.png)|Rhinoceros|[🔗](https://u.cubeupload.com/popularknight/pixilframe027.png)|floppasyay|2024-07-16|
|`1F995`|![](emoji/15x15/1f995.png)|Sauropod|[🔗](https://u.cubeupload.com/popularknight/pixilframe028.png)|floppasyay|2024-07-16|
|`1F52F`|![](emoji/15x15/1f52f.png)|Dotted Six-Pointed Star|[🔗](https://u.cubeupload.com/Octostomp/U1F52F.png)|co0lcr34t10ns|2024-07-15|
|`1F4BB`|![](emoji/15x15/1f4bb.png)|Laptop *|[🔗](https://u.cubeupload.com/CocoTheMii/1f4bb.png)|mybearworld|2024-07-04|
|`1F5A5`|![](emoji/15x15/1f5a5.png)|Desktop Computer *|[🔗](https://u.cubeupload.com/CocoTheMii/1f5a5.png)|mybearworld|2024-07-04|
<!-- |`XXXXX`|![](emoji/15x15/xxxxx.png)|Name|[🔗](URL)|Author|YYYY-MM-DD| -->

<sup>* Updated design for an emoji already present in the main Forumoji repository. This emoji is not included in the waitlist `emoji.json`; if the new emoji has a different author than the old one, its entry will need to be updated manually.</sup>

## Adding to Forumoji
Within this repository are some files that have been provided to simplify the process of adding the new emojis to the main repository.

Below is a list of important assets, as well as an explanation of how to implement each.

* `emoji.json` is a JSON object containing codepoints and authors for every emoji on this list, excluding updated designs for emojis that have been contributed before.
  * Append the contents of this file to `assets/emoji.json` on the [`main`](https://github.com/vercte/forumoji) branch
  * Copy the contents of the combined `assets/emoji.json` file into `assets/emoji.js` on the [`gh-pages`](https://github.com/vercte/forumoji/tree/gh-pages) branch
* `emoji/15x15` contains every emoji on this list in PNG format, ready to be dropped in to the main repository as-is.
  * Copy everything in this folder to `assets/emoji/15x15` into `assets/emoji/15x15` on the [`main`](https://github.com/vercte/forumoji) and [`gh-pages`](https://github.com/vercte/forumoji/tree/gh-pages) branches

Beyond just copying these files over, also take note of any emojis marked with an asterisk * in the waitlist above. These are updates to existing emojis, and adding these may involve updating the listed authors in `assets/emoji.json`.
