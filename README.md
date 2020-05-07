# Django Plugin Auditor.

A static code analysis tool for Django plugins

## Adding a project

1. Create a git submodule in `targets`
2. Add the project name to the GitHub actions matrix
3. Check out the artifacts with the results

## Viewing results

Check out 
https://github.com/tonybaloney/django-plugin-audit/actions

# TODO

* The inspection tool works better if the PyCharm inspector can detect the virtual environment and has the correct packages installed. 
* Many of the rules within pycharm-security check that a certain package exists in the environment to reduce false positives.
* The published artifacts are all in JSON. This could _either_ be in HTML, or, a script to download the artifacts, combine them and produce a report
* Figure out how to assess the requirements. 
