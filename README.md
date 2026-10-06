# Week 7 Assignment — Shopping List Manager

This project is a Python Shopping List Manager that demonstrates how to create, modify, search, and loop through lists.

## Files

* `list_warmup.py` — Demonstrates list creation, index access, append, remove, and length.
* `shopping_list.py` — Provides an interactive shopping list manager with add, remove, show, and done options.
* `list_report.py` — Generates a report by numbering items, counting names with more than four letters, and finding the longest item name.
* `screenshots/` — Contains screenshots showing the programs running successfully.

## Why check `in` before using `.remove()`?

Checking whether an item is in the list before calling `.remove()` makes the program safer because `.remove()` causes an error if the item does not exist. Using `in` allows the program to handle a missing item with a helpful message instead of crashing.
