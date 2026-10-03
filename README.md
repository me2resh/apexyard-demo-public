# ApexYard demo

A public demo repository for ApexYard. The [ApexYard Gate](https://github.com/me2resh/apexyard-gate-action) protects `main`.

Every pull request needs:

- a link that closes an open issue in this repository;
- an approval on the latest commit from a listed approver who is not the author.

The gate checks both and reads the team's signed rule pack from `.apexyard/`. It posts the `ApexYard Gate` check as the repository's own GitHub App.

The gate never calls the ApexYard cloud.
