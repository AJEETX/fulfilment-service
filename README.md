# fulfilment service

## Folder Structure detail:
- api: Backend API folder!
    - src: web api service with business logic.
    - test: Unit tests, integration tests… 
- ui: Frontend Application folder!
    - src: user interface source code.
    - test: Unit tests, etc.
- db: Data storage folder!
- .github: github actions for Continuous Integration.
- .config: It should local configuration related to setup on local machine.
- .build: This folder should contain all scripts related to build process (PowerShell, Docker compose…).
- dep: This is the directory where all your dependencies should be stored.
- doc: The documentation folder
- resources: For all static resources in your project. For example, images.
- tools: Utility directory for development purpose. for example, build scripts, rename scripts. Usually contains .sh, .cmd files for example.
- ignore, linting files, etc

## Github Branching strategy options:
- Trunk based development
- Feature based development

## PR approval and merge process:
- TBD

## ReadMe template
- create self explanatory readme  with complete details to setup, configure, run applications
