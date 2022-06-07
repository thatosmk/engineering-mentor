## Pull Requests

### Contributing to a codebase

To contribute to a codebase, pull the latest version of the base branch. Then create a new branch;

```sh
git pull main
git branch new-feature
git switch new-feature
```

Make the necessary changes to the codebase by adding a new feature and commit your changes.

```sh
git commit -am 'descriptive commit message'
```

Push your changes up to the remote repository and create a pull request.

1. Make a good and descriptive title for your pull request on Github
2. All a description that explains what your ticket or feature introduces to the codebase.
3. Put the pull request in draft mode while you make changes to it. Only put the pull request in ready to review if you are ready to have it reviewed.
4. Make sure the tests pass in your CI tool before you ask for a review of your pull request.
