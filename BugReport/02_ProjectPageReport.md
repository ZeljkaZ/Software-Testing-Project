## Summary (Summarize the bug encountered concisely)

    The Create New Project page on GitLab displays 'Create Black Project' as one of the options, instead of 'Create Blank Project'.

## Steps to reproduce

    1. Open Web browser (tested on Chrome and Safari)
    2. Navigate to GitLab (https://gitlab.com)
    3. Sign up or log in to your account
    4. Click on Projects in the main navigation menu
    5. Click New Project button
    6. Make note of the four project creation options displayed
    7. Note that the first option shows 'Create Black Project' instead of 'Create Blank Project'

## What is the current bug behavior?

    The button displays the word 'Black' instead of 'Blank' which may confuse users.

## What is the expected correct behavior?

    The correct wording should be 'Create Blank Project'.

## Relevant logs and/or screenshots

![Bug Screenshot](../Image/Bug_Screenshot.png)

    Console log does not display errors.

## Possible fixes

    Find the section in the code where this title is located.
    Replace incorrect text 'Create Black Project' with correct text 'Create Blank Project'.

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation
    /cc @project-manager
    /assign @frontend-developer

## Priority

    Minor priority: A typo can affects user experience and cause confusion, but it does not prevent project creation. Regardless, the bug should be fixed in timely manner to ensure smooth user experience.
