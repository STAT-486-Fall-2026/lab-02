# Lab 02: Introduction to scikit-learn

## Objective

Practice using scikit-learn for data preparation, model fitting, and k-nearest-neighbors regression.

## Before you begin

You need Git, a GitHub account, and [uv](https://docs.astral.sh/uv/getting-started/installation/) installed on your computer. This lab includes the course-provided `pyproject.toml`, `.python-version`, and `uv.lock` files, so you do **not** need to create an environment or install packages manually.

## Set up your submission repository

### 1. Fork the starter repository

Fork [`STAT-486-Fall-2026/lab-02`](https://github.com/STAT-486-Fall-2026/lab-02) to your **personal GitHub account**. In the fork dialog, name your repository exactly:

```text
lab-02-<netid>
```

For example, a student whose NetID is `jdoe42` must create `lab-02-jdoe42`. Use your institutional NetID even if it differs from your GitHub username. The course organization hosts the starter repository; your personal fork is where you will complete and submit your work.

### 2. Clone your fork

Copy the HTTPS URL for **your fork**, then run the following commands in a terminal. Replace the placeholders with your GitHub username and NetID.

```bash
git clone https://github.com/<github-username>/lab-02-<netid>.git
cd lab-02-<netid>
```

### 3. Create the lab environment

From the repository directory, run:

```bash
uv sync
```

This creates a local `.venv` with the exact package versions selected for Lab 02. Do not run `uv init` or `uv add`, and do not edit `pyproject.toml`, `.python-version`, or `uv.lock`.

### 4. Open and complete the notebook

Open `lab-02.ipynb` in your preferred notebook editor. Configure the editor to use the Python interpreter or notebook kernel in this repository's `.venv`; do not use a global Python installation.

Follow the directions in the notebook and complete all required code and written responses. The lab downloads its data while running, so an internet connection is required.

### 5. Commit and push your work

Save the completed notebook, then commit and push it to your fork.

```bash
git add lab-02.ipynb
git commit -m "Complete Lab 02"
git push
```

## Submission

Paste the root URL of your fork into the Canvas submission textbox:

```text
https://github.com/<github-username>/lab-02-<netid>
```

Submit the repository URL, not the course starter URL, a notebook-view URL, a clone URL ending in `.git`, or a local file path. Do not open a pull request and do not upload the notebook file to Canvas.
