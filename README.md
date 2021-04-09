# Quizzes for Programming Education Assitant

This repository contains quizzes for a project of
[programming education assistant tools](https://github.com/google/prog-edu-assistant).
The tools can add autograding capability to Python programming courses using
Jupyter or Colab notebooks.  Note that this repository only includes quizzes,
and the source code of the tools should go to
[the tool's repository](https://github.com/google/prog-edu-assistant).

## Who is this project for?

The main target audience is teaching staff who develops programming courses
using Colab Python notebooks. The quizzes provided in this repository
can be added to existing courses and made autocheckable by students.

The main focus is Japanese universities, so the quiezzes provided
in this repository are mostly in Japanese language.

## How to integrate autograder to your course

If you have a course based on Jupyter notebooks and want to integrate the
autochecking tests, there are multiple different way how the autochecking tests
can be run. See [README of the tool](https://github.com/google/prog-edu-assistant/blob/main/README.md#how-to-integrate-autograder-to-your-course) for its details.
Basically, the quizzes in this repository considers running autochecking inside
the student notebook.

## How to generate student notebooks

TODO(salikh): Replace with the packaged scripts once the PyPI package
includes the scripts.

1. Clone the tools project

   ```
   git clone http://github.com/google/prog-edu-assistant
   ```

2. Create a virtual Python3 environment and activate it.

   ```
   virtualenv -p python3 venv
   source venv/bin/activate
   ```

3. Install the tool dependencies.

   ```
   pip install -r prog-edu-assistant/python/colab/requirements.txt
   pip install prog_edu_assistant_tools
   ```

4. Convert the instructor notebook to student format.

   ```
   python prog-edu-assistant/python/colab/convert_to_student.py \
     --master_notebook instructor/python-intro.ipynb \
     --output_student_notebook student/python-intro-student.ipynb
   ```


## Development environment setup

Follow [the tools guideline](https://github.com/google/prog-edu-assistant/blob/main/SETUP.md)
if you want to modify the tools.

## License

This work is licensed under a CC BY 4.0 license. See [LICENSE](LICENSE) for details.

## Disclaimer

This project is not an official Google project. It is not supported by Google
and Google specifically disclaims all warranties as to its quality,
merchantability, or fitness for a particular purpose.
