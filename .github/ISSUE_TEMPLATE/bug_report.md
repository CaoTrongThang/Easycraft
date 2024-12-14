name: Bug Report Form
description: Create a report to help us improve
labels: bug
body:
    -   type: textarea
        attributes:
            label: Describe the bug
            description: A clear and concise description of what the bug is
        validations:
            required: true
    -   type: textarea
        attributes:
            label: To Reproduce
            description: Steps to reproduce the behavior
            placeholder: |
                1. Go to '...'
                2. Click on '....'
                3. Scroll down to '....'
                4. See error
    -   type: textarea
        attributes:
            label: Additional context
            description: Add any other context about the problem here. It would be best if you could attach the game log or crash report.
    -   type: markdown
        attributes:
            value: "You can paste your game log or crash report on [mclo.gs](https://mclo.gs/)"