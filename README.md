# daily-tools-in-my-browser

A collection of HTML files that I use for my daily productivity.

These HTML files are intended to be placed on your local machine, and then bookmarked in a "Daily" bookmark folder. Middle-mouse clicking on a bookmark folder will open all the bookmarks inside of it. And that gives me an easy way to open up and do any daily routines that don't need to be part of my primary to-do list app.

Right now there are two tools:

## Daily Checklist

This is a simple browser-based checklist that doesn't need to be part of my main productivity tools. It does _not_ use cookies or local storage. So it forgets when you close the window. You configure the to-do list by making a copy of the `daily-checklist-settings.js.example` and rename it to `daily-checklist-settings.js`. It's a simle array. You can not do nested items.

## Markdown To-do List Splitter

I use a daily markdown worksheet (using Obsidian) for my daily planning. I leave completed items on the previous day and copy the pending items to the next day. This browser-based tool automates that. It will create a completed and pending to-do list from whatever you paste into the input box.

It will intelligently convert tasks to notes as necessary when parents are completed and children are not. It treats bulleted items as task notes, and group them so tasks have the same context and information as the original list.
