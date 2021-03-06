# Adaptive UI for autonomous vehicles (WMG 2021 Summer Research Internship)

This GitHub repository is home to the code for the [Adaptive User Interfaces for Autonomous Vehicles](https://warwick.ac.uk/fac/sci/wmg/education/internships/wmg_research_internships/projects/rogerwoodman) WMG project, completed during Summer 2021.

## Install

Install the packages in requirements.txt:
```
pip install -r requirements.txt
```

## Run

Linux:
```
$ export FLASK_APP=adaptiveui
$ export FLASK_ENV=development
$ flask run
```

Windows:
```
set FLASK_APP=adaptiveui
set FLASK_ENV=development
flask run
```

Go to http://127.0.0.1:5000 to access the UI.

## Test

To test the decision tree's accuracy, run test_decision_tree.py and tweak the tile_data labels ("include" row) if needed.

## Acknowledgements

Thanks go to [Dr Roger Woodman](https://warwick.ac.uk/fac/sci/wmg/research/cav/humanfactors/people/rogerwoodman/) for supervising this project. His advice was invaluable for the project.
