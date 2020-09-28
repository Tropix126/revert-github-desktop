# revert-github-desktop
reverts github's awful redesign for their desktop client

# Installation

1. Locate your github desktop program path. On windows it's
`C:\Users\{user}\AppData\Local\GitHubDesktop\app-2.x.x\resources\app`

2. Download the CSS file located in this repository.
3. Replace renderer.css in your program path with the one in this repo.
4. Relaunch Github desktop.

# Icons?

Github switched to octicons v2 with the latest update, which are rendered in HTML locally. There's not much I can do to revert them back.

# Why

New design looks horrible and is way to rounded. They quite literally changed 3 lines of code and called it a day without testing anything. On primer-based sites it looks decent, but desktop doesn't utilize primer. It simply doesn't fit the already existing design language.
