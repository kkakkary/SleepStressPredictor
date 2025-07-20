
# COMPE596 Machine Learning Stress-Predictor Setup Guide

## Creating a Python Virtual Environment

A Python virtual environment is a self-contained directory tree that includes a Python installation and numerous additional packages. Using a virtual environment avoids installing Python packages globally which could break system tools or other projects.

### Step 1: Install `virtualenv`

If you do not have `virtualenv` installed, open your terminal and execute:

```bash
pip install virtualenv
```

### Step 2: Create the Virtual Environment

Create a new virtual environment by running:

```bash
virtualenv myenv
```

Replace `sayopillow_env` with your desired environment name.

### Step 3: Activate the Virtual Environment

Activate the virtual environment using the command below:

- On macOS and Linux:

```bash
source myenv/bin/activate
```

- On Windows:

```bash
.\myenv\Scripts\activate
```

Your command prompt will change to show the name of your activated environment.

## Installing Dependencies

With the virtual environment active, install the project dependencies with pip using the `requirements.txt` file provided in this repository.

### Ensure `pip` is Up-to-Date

It's a good practice to ensure that `pip` is up-to-date before installing dependencies:

```bash
pip install --upgrade pip
```

### Install Packages from `requirements.txt`

Install all the required packages with:

```bash
pip install -r requirements.txt
```

This command reads the `requirements.txt` file and installs all the libraries listed there.

## Deactivating the Virtual Environment

When you have finished working within the virtual environment and wish to return to the global Python environment, simply run:

```bash
deactivate
```
