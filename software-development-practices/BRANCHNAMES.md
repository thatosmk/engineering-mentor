## How to name your git branches

It is code software development practice to separate your production code from your development code, thus version control. To ensure that this is followed correct, we recommend you name your branches according to your development process pipeline.

> Some development process pipelines involve a lot other stages between developing a feature and deploying it.

### Development branch

Branch `development` or `develop` has some of the code all other developers branch off from when adding a new feature.

### Staging branch

Before your changes can be QA'd, you want to have another look at them in a production-like environment to ensure no other edge cases can be discovered. Usually, this branch name is `staging` .

### UAT or QA branch

Some software development teams have a QA, and thus, needing a separate environment to perform end-to-end tests on the codebase before it gets deployed, thus, `qa` or `uat`.

### Production branch

This is the client/users facing codebase that runs on a live server. This is the last stage of the develoment process pipeline and you do not commit code to this branch directly. name this branch `prod`,`production`, `main` or whatever you feel strongly about namning it.
