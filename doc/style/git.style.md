# Git Style Guide

1. Master should have a clear commit history that follows the Commit Style Guide
2. Branches should be named branchtype-issuenumber-username-brief-desc eg bugfix-1-jsalt-http500fix
3. Master will always be the result of a rebase -f
4. A git tag will be created for each version with a version number - a version will generally be a useful group of bugfixes, features and enhancements

## Branch Types

1. bugfix - fixes a Bug issue
2. feature - provides a Feature issue
3. enhancement - provides an enhancement - normally a long lived branch including multiple bugfix and feature merges
