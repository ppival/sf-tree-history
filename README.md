# yyc-tree-history

Tracking the history of trees in Calgary.

This repository [uses CircleCI](https://circleci.com/gh/simonw/sf-tree-history) to retrieve the [official CSV file of trees in Calgary](https://data.calgary.ca/Environment/Public-Trees/tfs4-3wwa/data) once a day and track any changes to it over time using the git commit history.

It uses [csv-diff](https://github.com/simonw/csv-diff) to generate human-readable commit messages.

You can see recent changes to the CSV file here: https://github.com/simonw/sf-tree-history/commits/master
