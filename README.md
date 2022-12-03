# MAP

## Project Overview

MAP, short for Map Accessibility Project, is a research project designed to help blind individuals access information on a map.

The project is led by Minnesota State University of Mankato (MNSU) Professor Dr. Guarionex Salivia.

This repo contains the literature review written by a team of students as part of their Fall 2022 Undergraduate Computer Science Project. The group contained J2 Student Lead Karter Prehn, as well as J1's Christian Stewart and Aaron Cherney. MNSU Alumni and legally blind individual Flint Million was consulted regularly for feedback and suggestions.

The literature review was used to create a survey for blind individuals The survey is pending IRB approval.

Future teams will analyze the results of the survey and use the results to help develop map accessibility guidelines and solutions for the visually impaired.

## Contents

### main.pdf

main.pdf is the compiled Literature Review written by Undergraduate Students Karter Prehn, Aaron Cherney, and Christian Stewart. It contains information about valuable takeaways from the studies and articles the students reviewed during the Fall 2022 semester.

### main.tex

A raw LaTeX version of the Literature Review.

### main.bib

BibTeX citations of all of the sources used in the Literature Review. Adding to this adds to the citations that can be referenced and compiled in main.tex.

### sources

Contains PDF versions of all the studies and articles referenced in the Literature Review.

### Dockerfile and Makefile

These files are used for LaTeX compilation. It compiles main.tex and main.bib into main.pdf, which is currently the literature review, but it can be customized to compile whatever LaTeX document you want, either by replacing main.tex and main.bib with your own versions, or changing Dockerfile and Makefile to reference different .tex and .bib files. (Extensive instructions are outside the scope of this README)

### .vscode

This directory contains the recommended VSCode extensions to use with this project.

## Repo Setup

### Required

Download Git. Link can be found [here](https://git-scm.com/downloads).

With Git installed, run:

```bash
git clone https://github.com/Mrjk1212/MapAccessibilityProject.git
```

This will clone the repo into the current directory.

### Optional

Git usually asks you to setup a **GitHub** account, but in case you don't have one, setting one up at [github.com](https://github.com) is well worth it. It will let you clone and manage your repos using a great user interface.

**VSCode** is a great tool to use with this repo. You can install it [here](https://code.visualstudio.com). There are recommended VSCode extensions that make the files easy to use. You will be prompted to install these recommended extensions when you open the project in VSCode. Refer to their documentation for usage instructions.

## LaTeX Compilation

### With Docker and GNU make

If you have both [Docker](https://www.docker.com) and [GNU make](https://www.gnu.org/software/make/manual/make.html) installed:

In your terminal, `cd` into the literature-review directory and run:

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

### Docker Only

If you have [Docker](https://www.docker.com) but **don't** have GNU make:

In your terminal, `cd` into the literature-review directory and run:

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

Your new main.pdf file will be saved to the literature-review directory.

**Note: Running this will add a bunch of main.\* files. This is normal. They can be removed after compilation if you would like.**
