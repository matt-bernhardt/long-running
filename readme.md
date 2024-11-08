# Long running branches

This is an experimental git repo to conform how long-running branches can work
in a git repository.

There are two long-running branches in this repo:

* `main` - which maps to what might be deployed in a production environment.
* `sandbox` - which maps to what might be deployed in a sandbox environment.

Some environment-specific details have been contributed to each branch, and
there is a common workflow possible where changes would start in a feature
branch, get merged into the sandbox branch, and also merged into the main
branch - while leaving environment-specific elements in place.

Hopefully this works.
