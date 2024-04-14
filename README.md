![Version](https://img.shields.io/static/v1?label=nih-grants-voice-in&message=0.2&color=brightcolor)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



# Voice In commands related to NIH grants

## Introduction
This repo contains voice commands about NIH grants for the automated speech recognition software Voice In Plus.
Voice In Plus is a Google Chrome and MicroSoft Edge extension.

The utilization of these custom commands requires a subscription to Voice In Plus.
These commands can be used in the text area of most websites and webmail programs opened in Google Chrome.
They might be helpful when drafting e-mails about grant reviews on secured websites and when writing grant reviews.

## Usage
You can use the commands right away after they have been uploaded.
I toggle Voice In on and off by using a keyboard shortcut.
I then dictate the command.
See the Voice In plug-in documentation to learn how to configure keyboard shortcuts.

## Installation
Each command is paired with the inserted text on a single line in a comma-separated value file (nih-grant.csv).
Equations, code snippets, and so on that span multiple lines are placed inside double quotes.
Use the **Bulk Add** button in Voice In Plus to upload these commands into your collection of custom commands.
Existing voice commands will be overwritten, so there is no problem with duplicates when pasting a set of new commands in the `bulk add` window.

## Contents of the nih-grants.csv

- 60 expansions of acronyms


## Related repositories
See [Voice Computing section of landing page](https://github.com/MooersLab/MooersLab?tab=readme-ov-file#voice-computing).
You will want to include the library of contractions at a minimum to eliminate them from your formal prose.

## Rules for developing voice commands

### Pick word combinations rarely used in normal prose
The basic rule for developing a voice command is to pick a word combination that is very unlikely to be used in one's prose.
This choice can avoid the accidental insertion of an unintended set of words.

### Pick word combinations that do not contain other commands
If you pick a word combination with a subset of words already assigned to another command, the commands will collide, and you will not get the intended effect.
It is better to pick a synonym for the new command than include the old one.

### Use verbs are prefixes

- Use the verb "expand" to expand acronyms.


### Test the commands
Like other forms of computer code, test the Voice In commands to ensure you get the intended effect.
The speed with which you vocalize a command has a significant impact.
You may find that you have to verbalize the command at high speed to avoid inserting just the first word of the command rather than the entire command.

### Keep handy the URL to the site for uploading commands
I add commands to my account several times a day.
I keep handy a link to the site's URL for uploading commands into my account on my private, custom-built home page, index.html.
I keep the link to the command page on the top line next to my links to other frequently used links like that one to Canvas for my lectures, the project page on Overleaf, 750words.com, Outlook web mail, gmail, and my GitHub and Codeberg repos.

## Contributions are welcome
This project can benefit most NIH grant reviewers.
Make a pull request, post an issue, or send me an e-mail with additions in CSV format.

|Version      | Changes                                                                                                                                    | Date                 |
|:-----------:|:------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------:|
| Version 0.2 |  Added update table and corrected wording in README.md.                                                                                    | 2024 April 14        |

