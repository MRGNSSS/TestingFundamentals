
## Summary (Summarize the bug encountered concisely)

Upon creating new blank project the title in "Create blank project" has a typo and says "Create black project" instead of "Create blank project" This leads to a bug where clicking on the "Create black project" doesn't do anything and therefore a new blank project cannot be created with the use of this option.

## Steps to reproduce     

Open gitlab.com
log in
Navigate to Projects page
Press "New Project" button
Press "Create blank project" option

## What is the current bug behavior?

Clicking on the "Create black project" button doesn't illicit a response.     

## What is the expected correct behavior?

The expected behavior of the button is to create a new blank project
     
## Relevant logs and/or screenshots

immediate visible issue is inside title of div that houses "Create blank project"

See example image "newprojecttypocode.png" in Image folder

## Possible fixes

Searching the front-end code and Fixing all possible typos in all areas of the code will most likely fix pathing issues so that clicking on the option will lead to the expected correct behavior (creating a new blank project)

## Whom do you report/ Assign To/ Tags

/label ~blocker ~major-bug ~urgent ~front-end ~reproduced
/cc @frontend-dev @project-manager @qa-lead
/assign front-end-devteam

## Priority

Blocker
