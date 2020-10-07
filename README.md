# OC4IDS Database Notebooks

A collection of notebooks for storing and querying OC4IDS data in a database.

Use the buttons below to open notebooks from the master branch:

* [Check and Import Notebook](https://github.com/open-contracting/oc4ids_database/blob/master/OC4IDS_Database_Data_Import.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/open-contracting/oc4ids_database/blob/master/OC4IDS_Database_Data_Import.ipynb) - Use this notebook to check data using the OC4IDS DRT and import the data and check results into the OC4IDS database.

To open a notebook from a different branch, use Colab's [Github browser](https://colab.research.google.com/github/open-contracting/oc4ids_database/) to choose the notebook and branch you want to open.

Alternatively, you can use the Open in Colab browser extension ([Chrome](https://chrome.google.com/webstore/detail/open-in-colab/), [Firefox](https://addons.mozilla.org/en-US/firefox/addon/open-in-colab/)) to add a button that, when clicked when viewing a Jupyter notebook on github, will open that notebook in Colab.

## Contributing

### Edit a copy of a notebook

1. In the Github web interface, open the notebook you want to edit and click the 'Open in Colab' badge.

2. Make your changes in Colab.

3. Format any SQL code you add or edit using [pgFormatter](http://sqlformat.darold.net/).

### Commit your changes

1. [Create a branch](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-and-deleting-branches-within-your-repository#creating-a-branch).

In Colab:

2. Click Edit -> Clear all outputs.

3. Remove any database credentials you entered into the notebook.

4. Click File -> Save a copy in Github.

4. Uncheck 'Include a link to Colaboratory'

5. Select your branch, enter a commit message and click OK.

### Request a review

1. [Create a pull request](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

2. Request a review from a helpdesk analyst.

3. If the reviewer requests changes, make the changes then repeat this step.

### Merge your changes

Once approved, you can merge your changes yourself.

### Reviewing changes

[Review the changes](https://docs.github.com/en/free-pro-team@latest/github/collaborating-with-issues-and-pull-requests/reviewing-proposed-changes-in-a-pull-request).

For small changes, you can use the diff in the Github review interface.

For larger changes, you might find it easier use Colab's [notebook diff](https://colab.research.google.com/diff) feature.
