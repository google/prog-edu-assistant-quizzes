# Quizzes for Programming Education Assitant

This repository contains quizzes for a project of [programming education assistant tools](https://github.com/google/prog-edu-assistant). The tools can add autograding capability to Python programming courses using Jupyter or Colab notebooks.
Note that this repository only includes quizzes for the tools so codes of the tools itself should go to [the tool's repository](https://github.com/google/prog-edu-assistant).

## Who is this project for?

The main target audience is teaching staff who develops programming courses
using Jupyter notebooks. The tools provided by this project facilitate addition
of autogradable tests to programming assignments, automatic extraction of the
autograding tests and student versions of the notebooks, and easy deployment of
the autograding backend to the cloud.

The main focus is Japanese universities, so the quiezzes provided
on this repository are mostly in Japanese language.

## How to integrate autograder to your course

If you have a course based on Jupyter notebooks and want to integrate the
autochecking tests, there are multiple different way how the autochecking tests
can be run. See [README of the tool](https://github.com/google/prog-edu-assistant/blob/main/README.md#how-to-integrate-autograder-to-your-course) for its details.
Basically, the quizzes in this repository considers running autochecking inside the student notebook.

## Development environment setup

Follow [the tools guideline](https://github.com/google/prog-edu-assistant/blob/main/SETUP.md).

## License

This work is licensed under a CC BY 4.0 license. See [LICENSE](LICENSE) for details.

## Disclaimer

This project is not an official Google project. It is not supported by Google
and Google specifically disclaims all warranties as to its quality,
merchantability, or fitness for a particular purpose.
