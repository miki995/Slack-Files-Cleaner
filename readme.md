# Slack Files Cleaner

<p align="center">
    <img src="https://github.com/miki995/Slack-Files-Cleaner/blob/master/images/cleaner.png" alt="Slack Files Cleaner" width="200" height="200"/>
</p>

This is Slack Files Cleaner script.
Slack does not have an option to delete bulk of files, but they provide an api which this script consumes.

## Getting Started

This script will delete all files older than days you specify. 


### Prerequisites

What things you need to install the software and how to install them

* [python](https://www.python.org/downloads/)

* [pipenv](https://pipenv.readthedocs.io/en/latest/)

* [python requests](http://docs.python-requests.org/en/latest/user/install/#install)

```

Please ensure that you have installed these requirements.

```


## Running the script
In terminal: 

1. Export your SLACK_API_TOKEN 

```
export SLACK_API_TOKEN="YOUR_API_TOKEN" - example
```

1. Export OLDER_THAN - this is the number of days from now that we want to keep files. 

```
export OLDER_THAN="30" - example
```


2. Run the script

```
python3 delete_files.py

```

## Further steps

* Create an API and deploy to server.
* Create frontend client so users can delete it via UI.

## Acknowledgments

* https://www.techjunkie.com/delete-all-slack-files/
* https://gist.github.com/jackcarter/d86808449f0d95060a40

## Author

* **[Miroslav Maksimovic](https://github.com/miki995)** 

