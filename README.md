# Python Modern Cheat Sheet

**[WORK IN PROGRESS]**

## Why another cheat sheet?

There exists many available Python cheet sheats on the web. But this one:
- Deals with Modern Python (3.10+) only
- Has strict type checking enabled
- Is fully integrated with VS Code and Jupyter, which leads to many advantages (see below)
- Is forkable so that you can customise it and make it yours. Any cheat sheet should reflects personal knowledge at a current moment.

## Why using VS Code and Jupyter for a cheat sheet?

- Why use anything else than your IDE to read and write code ? (You get same syntax colors, same shortcuts, type inference, etc.). You feel at home.
- Unlike (most) websites or books, you can customize code snippets and make them yours.
- Code snippets can be directly executed. Don't rely on comments to see the program output.
- Possible 0-config by having an isolated installation in a dedicated Docker container (cf. below)


## How to use it yourself?
This project can be used as a base for your personal cheat sheet too. For this:

- Fork this project
- Install it or your own machine by your own means, or even better, use the `.devcontainer.json` file to create a [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers). This way, you'll have a 0-config installation.

## Roadmap

**Done**
- [x] Basics of language
- [x] Less basic techniques (unpacking, sets, ternary operator)
- [x] Collection module
- [x] Type hints basics
- [x] Iteration / Generation
- [x] Functional tools


**To Do**
- [ ] dicts
- [ ] OOP
- [ ] dataclasses
- [ ] Error handling
- [ ] Arithmetics
- [ ] More advanced type hints
- [ ] Some external libs (structlog, ...)

## Inspiration

These projects has been extensively used to create this cheat sheet:

- [Intermediate Python](https://book.pythontips.com/en/latest/)
- [Mypy cheat sheet](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)
- [Python Cookbook Jupyter Notebook](https://github.com/acheamponge/Python-Cookbook-3rd-edition-JupyterNotebook-Code)
