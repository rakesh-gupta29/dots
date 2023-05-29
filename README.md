# Hugo Blog

HUGO is a highly performant, configurable and easy to use static website generator written in [Go](https://go.dev).

## What is this

This is a static blog created using the HUGO static website generator:- mini project which is still under development.

Such an application is easy to build and host on any enterprise level hosting like AWS clodufront or Github pages. 

Such static blogs are easy to maintain, iterate or distribute because of their static build, fast build time and extensive range of plugins and extensions.


## Setup and Editing 

To setup and run the repo locally, follow the following instructions.

```bash
1. Install the HUGO builder locally using the [following instructions](https://gohugo.io/installation).
2. Clone the repo using `git clone https://www.github.com/rakesh-gupta29/dots.git`
3. move to the directory using `cd dots`
4. run `npm i` to install the dependencies for running tailwindCSS locally. This project uses tailwind for styling.
5. run the command `hugo server -D` to start a local server with build cache disabled. In the cache disabled mode, the output is a bit slow but more accurate.
```
## Contribution

## Directory Structure

Offical documentation of HUGO provides a better overview of the project structure and layouts. The project follows the standard for the project structure.

## Building

To build the code, run `hugo`. It will emit the output in `public` folder.

## Adding a blog

To contribute and add a blog, create a file named `{filename}.md` under `content/blog` folder. Add the meta data to the file in the following format.
some  frontmatter format will be here.
Push and create a pull request.
