# release-drafter-lag-test

Reproducer for [release-drafter](https://github.com/release-drafter/release-drafter)'s
GitHub GraphQL `associatedPullRequests` index lag. PRs whose merge commit
is in the comparison range may be missing from the standard query for a
brief window after merge.
