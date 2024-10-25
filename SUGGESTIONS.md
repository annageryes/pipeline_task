# Suggestions

### Project
Good work, but some what messy IMHO, the project needs to be compact in order to understand the usage of project

### README
- Missing links to
  - INSTALL.md
  - TASKS.md

### Jenkinsfiles
- Preferably to use folder for Jenkins files
  - Usually, it will be required to use either shared library(seperate repo that includes groovy or shell based code) that is imported while running the pipeline
  - In our case we could have written seperate single file that would have predefined functions that are loaded as [shown in this example](https://stackoverflow.com/questions/37800195/how-do-you-load-a-groovy-file-and-execute-it)
