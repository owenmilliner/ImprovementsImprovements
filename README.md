# Subtle Improvements: Issues

This repository is the public **issue tracker** for **Subtle Improvements** and its sister mod **Not So Subtle Improvements**, Minecraft mods for Fabric, Forge and NeoForge. Use it to report bugs, suggest improvements, give feedback or ask questions. It does not contain the mod's source code.

## About the mod

Subtle Improvements is a collection of small, high-quality quality-of-life improvements that make Minecraft feel like a slightly more polished version of itself. Every improvement is:

- **Optional**: each feature can be toggled and configured individually, in game, with `/subtleimprovements` (alias `/si`) or the settings screen.
- **Vanilla-friendly**: it should feel like something Mojang could have added, with no unfair advantages or automation.
- **Lightweight**: disabled features have effectively no runtime cost.

Examples include auto-replacing broken tools, sorting inventories, and shift + drag to quick-move many slots.

### Not So Subtle Improvements

A sister mod with the same focus on quality of life, for features that do change how the game plays, such as vein mining or an item magnet. Every feature is still optional. Suggestions that are too gameplay-changing for Subtle Improvements belong here.

### Improvements Core

Your mods list also shows **Improvements Core**. It comes bundled inside each mod, so there is nothing extra to install. It provides the settings screen, the settings keybind (default `\`) and each mod's commands (such as `/subtleimprovements`). Report problems with those here too, and pick "Improvements Core" when the form asks which mod.

## How to submit an issue

1. **Search first.** Check [open and closed issues](../../issues?q=is%3Aissue) in case it has already been reported. Add a 👍 or a comment to an existing issue instead of opening a new one.
2. **Open a new issue** via [New issue](../../issues/new/choose) and pick the template that fits:

   | Template | Use it for |
   | -------- | ---------- |
   | Bug report | Something isn't working as expected |
   | Suggestion | A new improvement, or a change to an existing one |
   | Feedback | General thoughts on the mod |
   | Question | Help using the mod or understanding a feature |

3. **Pick the mod.** Every form starts by asking which mod the issue is about. Choose "Not sure" if you can't tell.
4. **Fill in the details.** For bugs, include the mod version, Minecraft version, loader, other installed mods, steps to reproduce, and the relevant part of `latest.log` or the crash report.
5. **One topic per issue.** Separate issues are easier to track and close.

Suggestions for Subtle Improvements should be small, vanilla-friendly quality-of-life changes. Ideas that change gameplay, such as vein mining or auto-eating, go to Not So Subtle Improvements: pick it when the form asks which mod.

## Labels

Maintainers apply labels while triaging; you don't need to add any. Your template sets the type, and your "Which mod?" answer sets the mod.

| Label | Meaning |
| ----- | ------- |
| `bug` | Something isn't working as expected |
| `suggestion` | Idea for a new improvement or a change to an existing one |
| `feedback` | General thoughts on the mod |
| `question` | You need help or clarification |
| `fabric` / `forge` / `neoforge` | Applies to that loader's version |
| `project:si` | About Subtle Improvements (added from your "Which mod?" answer) |
| `project:nssi` | About Not So Subtle Improvements (added from your answer) |
| `project:core` | About Improvements Core: the settings screen, keybind or commands (added from your answer) |
| `needs-info` | Waiting on the reporter for more details |
| `in development` | Accepted and currently being worked on |
| `duplicate` | This has already been reported |

## What happens next

Issues are mirrored to the mod's private development repository so they can be planned and worked on. Status updates and questions will be posted here on your issue.

Please be kind and constructive. Thanks for helping make Subtle Improvements better!
