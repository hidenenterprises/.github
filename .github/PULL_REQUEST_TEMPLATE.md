<!-- Feature PRs (into dev/develop): the Summary is enough; delete the Release section.
     Release PRs (into main): fill in every section. The automated review (pr-watch) reads this
     description, and anything unusual that is explained here does not need a separate message. -->

## Summary

<!-- What changes and why. Link the PRs or issues it includes. -->

## Release checklist (PRs into `main` only)

- [ ] CHANGELOG updated for this version
- [ ] Database migrations: none / listed below (additive, data, reversible?)
- [ ] New or changed config keys / `.env` variables: none / listed below, with their defaults
- [ ] Deployment steps and order (panel first? daemon first? commands to run, what to note before restarting)
- [ ] Anything that changes what is sanctioned, suspended, quarantined or banned automatically: none / explained below
- [ ] Anything unusual (a limit, a timing, a behaviour, a file outside the usual scope, a new dependency): none / explained below

### Migrations, config keys and deployment notes

<!-- Leave "None" if nothing applies. -->

### Unusual things and why

<!-- Say what is unusual and why it is done this way. The review takes it into account and verifies it;
     if it is not explained here, the PR waits for a manual review. -->
