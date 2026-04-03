# Waterfox / Firefox Ultra-Slim Tabs (18px)

A custom `userChrome.css` snippet that forcefully shrinks the modern Waterfox and Firefox tab bar down to a razor-thin 18px. Perfect for Linux users (like XFCE/Xubuntu) or anyone trying to maximize their vertical screen real estate.

<img width="1185" height="768" alt="Screenshot_2026-04-03_20-35-40" src="https://github.com/user-attachments/assets/c0a7b8b6-26fc-4ca0-adaf-c860c10ae008" />

## Features
* Forces a strict 18px maximum height on the tab bar.
* Kills all invisible layout padding and block margins.
* Dynamically resizes the font, favicons, and close buttons to prevent clipping.
* Keeps text perfectly vertically centered.

## Installation

**1. Enable Custom Stylesheets**
1. Open Waterfox/Firefox and go to `about:config` in the address bar.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`.
3. Ensure it is set to `true` (this is usually default in Waterfox).

**2. Locate Your Profile Directory**
1. Type `about:support` in the address bar.
2. Find the **Profile Directory** row and click **Open Directory**.
3. Inside your profile folder, create a new folder and name it exactly `chrome` (all lowercase).

**3. Add the Code**
1. Download the `userChrome.css` file from this repository.
2. Place it inside the `chrome` folder you just created.
3. Restart your browser. 

*(Note: If the changes do not appear immediately, go back to `about:support` and click **Clear startup cache...**)*
