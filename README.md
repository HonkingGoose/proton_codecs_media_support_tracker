![Prettier](https://github.com/HonkingGoose/proton_codecs_media_support_tracker/workflows/Prettier/badge.svg)

# Proton Codecs Media Support Tracker

## What this project covers

This repository contains the GitHub Flavoured Markdown tables for issue [#1464](https://github.com/ValveSoftware/Proton/issues/1464) at the upstream Proton project.
This repository does not contain any codecs or programs to help you play games with missing videos with Proton.

This project has no further affiliation with the upstream Proton project, and is not endorsed by Valve or Proton.

## How to contribute

This project accepts pull requests to update the tables with new findings regarding the codecs and media framework support.

Please do not open issues for things that belong to the upstream Proton project.

### How do I know what table I should edit?

This repository tracks games that have problems with the video playback.

In-game rendered cutscene problems are out of scope for this repository, please report those problems at the upstream Proton project.

The Proton log usually contains clues about what video framework the game uses.
The [Proton Wiki, missing cinematic/cutscenes](https://github.com/ValveSoftware/Proton/wiki/Checklist-Proton-bugs#missing-cinematiccutscenes) has more information on this.
Read this Wiki entry before starting your work.

### How do I work with GitHub Flavoured Markdown tables?

Read the [GitHub.com docs on organizing information with tables](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/organizing-information-with-tables)

### Steps to contribute

1. Read the Proton wiki entry linked above.
1. Check your game's Proton log for relevant clues.
1. Fork this repository.
1. Clone your fork to your local workstation.
1. Run `npm install` to install Prettier.
1. Create a new Git branch.
1. Go to the `tables` directory, it contains the Markdown tables for each media framework.
1. Open the table you want to edit in your text editor of choice.
1. Add a new table entry, or edit an existing entry, look at the previous entries for an example.
1. Save your work in the text editor.
1. Run `npm run prettier-fix` to run the Prettier formatter.
1. Commit your work with Git.
1. Push the branch to your fork.
1. Open a pull request and fill in the template.
