# AI-Exercises

this repository holds excersises of the fontys 4th semester of AI.

# setting up a python virtual environment

each folder requires a specific python version and specific dependencies. To establish a foundation for each project (folder) we can create a virtual environment

## Creating a Python Virtual Environment

1. Navigate to the project folder where you want to create the virtual environment. You can do this using the `cd` command in your terminal. For example:

```bash
cd path/to/your/project/folder
```

```bash
python -m venv venv
```

## Activate the virtual environment

windows

```bash
.\venv\Scripts\activate
```

unix/macos

```bash
source venv/bin/activate
```

## download dependencies

the project folders are all equipped with a requirements.txt which you can use to install all the dependencies required to run the project.

```bash
pip install -r requirements.txt
```
