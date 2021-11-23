# Contributor's Guide

First of all, thank you for hosting a tutorial through the Project Pythia Python Tutorial Seminar Series. Project Pythia appreciates your support, your work, and commitment to community.


To add your tutorial directory please follow these steps:

### 1. Become a member of the ProjectPythiaTutorials GitHub organization
If this is your first time hosting a tutorial through the Project Pythia Tutorial Seminar Series, you will need to be added as a member of the ProjectPythiaTutorials organization before you can create a new repository. Please let us know if you need to be invited to this organization by emailing `projectpythia@ucar.edu`.

### 2. Create a unique tutorial repository from this template repository
Within the ProjectPythiaTutorials organization please create a new repository for your tutorial with the naming convention `TOPIC_YYY_MM_DD` (e.g. `pandas_2021_11_24`). If you have multiple tutorials in a series that build off of each other, please create **multiple repositories** that represent the state of the series at each lesson (e.g. `pandas_part1_2021_11_24` and `pandas_part2_2021_12_08`).

### 3. Review the tutorial template (`/tutorial/template.ipynb`).
The tutorial template is designed to give you a brief overview of what is expected of a Project Pythia Tutorial seminar. We hope you find the template a useful reminder of good presentation ideas and bookendsl. It is not designed to be restrictive or time-consuming if you choose to adapt your material to it.

### 4. Upload your tutorial content.
Add any relevant `.ipynb` files to the `/tutorials/` directory of your repository and any data to the `/data/` directory (if the data is too large to store on GitHub, i.e. over the 100 MB limit per file, please indicate this in a `/data/README.md` file).

Because we understand that you may be editing your notebook right up until your tutorial, the contribution "barrier for entry" in this repository is lower than elsewhere in the Pythia ecosystem. And since you will only be editing files in your new directory, feel free to push directly without waiting for a review.

### 5. Create a `README.md` file associated with your tutorial directory.
Every tutorial repository is intended to be accompanied by a `README.md` markdown file. The contents of this file are similar to what should go out with an announcement of your seminar: title, speaker name, a brief speaker bio, live time and date, and any past tutorials that this new seminar is a continuation of. After the session a member of the Pythia team will embed the Youtube recording into this same file. Please see the `README_template.md` file for assistance (coming soon).

You may also merge this new markdown content without waiting for an approval on your pull request.

### 6. Check the repository-wide `environment.yaml` file.
Every tutorial has environment file. Binder should be enabled from this file. Please check the `environment.yaml` file to make sure all of your necessary dependencies are listed.


If you would like to host a tutorial through the Project Pythia Tutorial Seminar Series, please reach out to us here on GitHub or by emailing `projectpythia@ucar.edu`. Contributors Guide coming soon.
