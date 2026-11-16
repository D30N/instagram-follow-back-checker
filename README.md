# Instagram Follow Back Checker

Upload your Instagram data ZIP and instantly see who you follow that does not follow you back.

Live: https://d30n.github.io/instagram-follow-back-checker/

## How to use

1. Open the page above.
2. Request your Instagram data as a ZIP in JSON format:
   Instagram app, Profile, menu, Settings, Accounts Centre, Your information and permissions, Download your information, Download or transfer information, pick your account, Some of your information, tick only Followers and following, Date range All time, Format JSON, Create files.
3. Open the link Instagram emails you and download the ZIP.
4. Drop that ZIP on the page. You can also drop the `followers_1.json` and `following.json` files directly.
5. See the list, search it, copy it, or download it as CSV or TXT.

## What it shows

- Followers, Following, mutual follows, and do-not-follow-back counts
- Do not follow you back: people you follow who do not follow you back
- Follow you, you do not follow: people who follow you that you do not follow back

Each name links to that Instagram profile.

## Language

The page has an English / മലയാളം switch at the top. The choice is remembered in the browser.

## Privacy

Everything runs in your browser. Your ZIP is read locally with JavaScript and is never uploaded to any server, saved, or shared. There is no login and no account. Close the page and the data is gone.

This tool is not affiliated with Instagram or Meta, and it never asks for your Instagram password. If a site asks for your login to show this list, do not use it.

## Files

- `index.html`: the whole tool, a single static page. It uses JSZip from a CDN to read ZIP files.

## Credit

[This app was made by Deon](https://deepakdeon.github.io).
