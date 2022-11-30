# MAP

## Project Overview

MAP, short for Map Accessibility Project, is a research project designed to help blind individuals access information on a map.

INSERT MORE INFORMATION ABOUT THE PROJECT AND TEAM MEMBERS HERE

## Usage

### Setup

#### Required

Download Git. Link can be found [here](https://git-scm.com/downloads).

With Git installed, run:

```bash
git clone https://github.com/Mrjk1212/MapAccessibilityProject.git
```

This will clone the repo into the current directory.

#### Optional

Git usually asks you to setup a **GitHub** account, but in case you don't have one, setting one up at [github.com](https://github.com) is well worth it. It will let you clone and manage your repos using a great user interface.

**VSCode** is a great tool to use with this repo. You can install it [here](https://code.visualstudio.com). There are recommended VSCode extensions that make the files easy to use. You will be prompted to install these recommended extensions when you open the project in VSCode. Refer to their documentation for usage instructions.

### LaTeX Compilation

#### With Docker and GNU make

If you have both [Docker](https://www.docker.com) and [GNU make](https://www.gnu.org/software/make/manual/make.html) installed:

Within the literature-review directory, run:

```bash
make build
```

This will install a Docker image on your computer that contains all the required software for compiling main.tex. **It may take several minutes to run. Be patient.**

Then, whenever you need to compile, run:

**Mac or Linux:**

```bash
make
```

**Windows Powershell:**

```bash
make windows
```

Your new main.pdf file will be saved to the literature-review directory.

#### Docker Only

If you have [Docker](https://www.docker.com) but **don't** have GNU make:

Within the literature-review directory, run:

```bash
docker build -t lit .
docker create --name lit lit
```

**Note: Don't forget the period at the end of the first line.**

This will install a Docker image on your computer that contains all the required software for compiling main.tex. **It may take several minutes to run. Be patient.**

Then, whenever you need to compile, run:

**Mac or Linux:**

```bash
docker run -v $(PWD):/app lit make docker
```

**Windows Powershell:**

```bash
docker run -v ${PWD}:/app lit make docker
```

Run the same command, but replace `$(PWD)` with the path to the literature review directory.

Your new main.pdf file will be saved to the literature-review directory.
