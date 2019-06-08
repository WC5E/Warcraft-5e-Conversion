# Warcraft: Heroes' Handbook

This project aims to create a set of Warcraft supplements for Dungeons & Dragons 5th Edition.

[Heroes' Handbook Kanban Board](https://github.com/Jihia/Warcraft-Heroes-Handbook/projects/2)

[Manual of Monsters Kanban Board](https://github.com/Jihia/Warcraft-Heroes-Handbook/projects/3)


## Branching Structure

This project uses a slightly different take on [feature branching](https://guides.github.com/introduction/flow/). Being an RPG book, the branches focus on where in the book changes are being made, and what changes they are. 

`<topic>/<branch-name>`

The `<topic>/` of the branch should be the section of the book affected. The `<branch-name>` should summarise the specific part being changed.

The following are good examples of branch names for the project:

* `race/orc-traits`

* `spell/mage-spell-list`

* `class/rebalance-warrior-features`

## Semantic Commit Messages

Commit messages and pull requests should try and follow a [Semantic Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.4/) structure.

Again since this project is not a development project, but version control for a series of books, we're going to adapt the principles of Semantic Commits and apply it in a way that makes sense for the project.

In short, prefix your commit messages and pull request with the type of work that has been done. Including (but not necessarily limited to):

* `style:` - Changes made to the stylesheet for the book.

* `art:` - Art has been added or removed.

* `format:` - Text, content, or art has been positioned/adjusted.

* `text:` - Changes made to how something was written.

* `errata:` - Changes made are [errata](https://en.wikipedia.org/wiki/Erratum) that impact the game.

* `docs:` - Changes made to documentation, like the README.

* `wip:` - New addition to, or changes in, a WIP folder.

* `move/remove:` - Content moved between files, or removed entirely.

## Warcraft: Heroes' Handbook

These documents have been set up for the project, outside of Github, to track various parts of the project. 

[Version Changelog](https://drive.google.com/open?id=1AtTF7o6sAZZLxA75oa-96ENNNBMAJ-z7m9Y93uk4b8A)

[Race Balancing](https://drive.google.com/open?id=1S-XKXMaiLtRLpeIg9t50PvvAfEajpq72MxjTqa9ZbaI)

[Available Spells for each Class' Spell List](https://drive.google.com/open?id=1bzXzGxXFdC3zUdm8_4aURXfftixsJTStRn49fAeSDgs)

[Future Plans](https://drive.google.com/open?id=1MXoKixt1elxs7Em_-nOrTiJ49ki8CcGaavYzBGM6jLs)

#### Adding material to the WIP folder

Changes, or entirely new content, can be added to the version control if wanted. Just like with the Manual of Monsters, add the WIP content to its own file under `WIP Heroes Handbook`.


## Warcraft: Manual of Monsters

Progress on the Manual of Monsters is kept in its own Drive spreadsheet. Creatures are put aside in chunks for smaller, reachable milestones and then signed off on when the stats have been set and agreed upon.

[Monster Planning Document](https://docs.google.com/spreadsheets/d/1gjxgzF93LLB3q_o7QYe9xynpxkaUrkorklA7YGHSJvA/edit?usp=sharing)


#### Add new creatures to the WIP folder

New creature statblocks for the Manual of Monsters are added to the book's WIP folder first, and then pulled from there into the book when a new release is being worked on.

That way we can scope the book into iterations, and extra statblocks can be done parallel with book formatting, without losing material between a hundred different GM Binder links.

[WIP Monster Folder](https://github.com/Jihia/Warcraft-Heroes-Handbook/tree/master/WIP%20Manual%20of%20Monsters)
