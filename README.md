<img src="https://github.com/ddahan/modern-python-cheat-sheet/blob/main/resources/logo/logo.png?raw=true"
     alt="Logo"
     style="float: left; margin-right: 10px;" 
     />


<p style="text-align: center; font-size: 20px">
Work in progress ...
</p>

## Why another cheat sheet?

There exists many available Python cheat sheets on the web. But this one:
- Focuses exclusively on **modern Python** (3.11+)
- Is for **intermediate level** (don't expect "what is a loop" section)
- Has **strict type** checking enabled
- Is fully integrated with **VS Code and Jupyter** (see below the advantages)
- Is forkable, allowing you to customize it to reflect your current level of knowledge (every cheat sheet should be a snapshot of one's personal knowledge at a given time).

## Why using VS Code and Jupyter for a cheat sheet?

- Why would you use anything else than your IDE to read and write code? You get same syntax colors, same shortcuts, auto complete, type inference, linting, auto-formatting, debugging, etc.
- Unlike (most) websites or books, you can customize code snippets and make them yours, after having forked the project.
- Code snippets can be directly executed. Don't trust the code comments to know the program output.
- Possible 0-config by having an isolated installation in a dedicated Docker container (cf. below). It includes linting and type checking with Pylance, and auto-formatting with Black.


## How to use it yourself?

You can use this project as a foundation for your own personal cheat sheet. To do so:

- Fork this project
- Install it on your own machine using your preferred methods, or better yet, use the `.devcontainer.json` file to create a [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers). This approach provides a zero-configuration installation.

If you don't want to install the project, you can just read the notebooks on github.com

## Contribution

Since a cheat sheet is personal first, I don't expect new content to be proposed. However, if you find a mistake, something obviously missing, or anything than can help others, feel free to open an issue or a PR.

## Roadmap

**To check for content**
- *See each sections for content to fill (in the title, or in TODO file)*
- [ ] See [Python Cookbook Jupyter Notebook](https://github.com/acheamponge/Python-Cookbook-3rd-edition-JupyterNotebook-Code)
- [ ] See [30 Helpful Python Snippets](https://morioh.com/a/271bc88c0100/30-helpful-python-snippets-you-should-learn-today)
- [ ] See [The complet guide to Python](https://www.youtube.com/watch?v=mDKM-JtUhhc)
- [ ] See [Nooby habits](https://www.youtube.com/watch?v=qUeud6DvOWI)

**To Do (features)**
- [ ] Clean "don't do this" syntax
- [ ] Add screen presentation
- [ ] Add internal cross references (for example for "comprehensions" because they can be at multiple places in the sheet)
- [ ] Add a TOC to this file for easier access to sections
- [ ] Use Ruff instead of Pylance (as soon as it's [compatible with Junyper](https://github.com/astral-sh/ruff/issues/5188))
- [ ] Fix issue which require a reload after first devcontainer installation

## Inspiration

When not using chatGPT, these projects have been referenced to create this cheat sheet:

- [Intermediate Python](https://book.pythontips.com/en/latest/)
- [Mypy cheat sheet](https://mypy.readthedocs.io/en/stable/cheat_sheet_py3.html)
- [25 nooby Python habits you need to ditch](https://www.youtube.com/watch?v=qUeud6DvOWI)  [+ this one](https://www.youtube.com/watch?v=E8NijUYfyus)
