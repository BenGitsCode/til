# Today I learned...

About an awesome way to render readme files locally, before pushing them to github.

From its [README](https://github.com/joeyespo/grip):

> "Grip is a command-line server application written in Python that uses the GitHub markdown API to render a local readme file. The styles come directly from GitHub, so you'll know exactly how it will appear. Changes you make to the Readme will be instantly reflected in the browser without requiring a page refresh."

## Installation

You can install using Python's [pip](https://github.com/pypa/pip) or using [HomeBrew](https://github.com/Homebrew) on macOS.

[How-to-install-grip](https://github.com/joeyespo/grip#installation)

1. Install with `pip`..👉   `$ pip install grip`
1. Install on OS X....👉   `$ brew install grip`

## Examples of use

Once you have it installed simply `$ grip` to serve the README of the current directory or `grip <filename>` to serve any other markdown files by name.

To learn about some additional options, such as specifying the port used, or how to use their API, see the [grip-documentation](https://github.com/joeyespo/grip)

That's all, now you'll never push broken links to GitHub ever again, right? 😏

[![grip-in-action](https://cl.ly/m09e/Image%202017-08-14%20at%201.50.18%20PM.png)](https://cl.ly/lzLo)


## Credit:

> **On GitHub attributed to [*@joeyespo*](https://github.com/joeyespo/) and can be found [here](https://github.com/joeyespo/grip)**
