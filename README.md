# Github Actions
- Github Actions is the pipeline tooling that is part of Github
- Github Actions is one of the deployment pipeline tools that is available in the market

Continuous Integration
- Fast and frequent integration of changes to verify they work correctly together

Continuous Delivery
- Every accepted change leads to the automated build of a deployable package

Continuous Deployment
- Every accepted change is automatically deployed

## Building pipelines with Github Actions
- Triggers
  - Following are available triggers
    - Manually
    - On code events
      - on push or pull request
      - around 30 other event types
      - optionally with branch filters
    - on a schedule
- Workflows
  - The outer process description for how your pipeline should run is called a workflow
  - Within the workflow, there can be one or more separate jobs
  - Jobs can run concurrently depending on how you define them
  - Example
    - A typical small workflow could contain three jobs
      - one to create the package
      - one to deploy to test
      - one to deploy to production
  - Each workflow needs `some reason to start`. A common reason can be a change in your source control repository, in which case that reason is called an event
- Actions
  - Each job contains one or more actions
  - Actions are the atomic building blocks that define one step in your job
  - Examples
    - Running a script or compiling some files
    - In many cases, the first action is to clone or checkout your source code repository as they contain raw materials that most workflows operate on
  - List of available actions is longer
    - Checkout a repository
    - Invoke a script
    - Compile, test or deploy code
    - Lint and run Ansible files
    - Over 4000 others
    - You can write your own


ansible
- playbook.yml
- 

