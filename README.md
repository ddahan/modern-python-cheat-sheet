# Python Modern Cheat Sheet

**[WORK IN PROGRESS]**

## Why another cheat sheet?

There exists many available Python cheet sheets on the web. But this one:
- Focuses exclusively on Modern Python (3.10+)
- Has strict type checking enabled
- Is fully integrated with VS Code and Jupyter, offering numerous advantages (see below)
- Is forkable, allowing you to customize it to reflect your current level of knowledge. Every cheat sheet should be a snapshot of one's personal knowledge at a given time.

## Why using VS Code and Jupyter for a cheat sheet?

- Why use anything else than your IDE to read and write code? You get same syntax colors, same shortcuts, auto complete, type inference, etc. You feel at home.
- Unlike (most) websites or books, you can customize code snippets and make them yours.
- Code snippets can be directly executed. Don't trust the code comments to see the program output.
- Possible 0-config by having an isolated installation in a dedicated Docker container (cf. below)


## How to use it yourself?
You can use this project as a foundation for your own personal cheat sheet. To do so:

- Fork this project
- Install it on your own machine using your preferred methods, or better yet, use the `.devcontainer.json` file to create a [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers). This approach provides a zero-configuration installation.

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

These projects have been referenced used to create this cheat sheet:

- [Intermediate Python](https://book.pythontips.com/en/latest/)
- [Mypy cheat sheet](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)
- [Python Cookbook Jupyter Notebook](https://github.com/acheamponge/Python-Cookbook-3rd-edition-JupyterNotebook-Code)
