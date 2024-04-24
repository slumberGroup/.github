Use this PR template whenever an existing third party dependency is updated.

## Overview

| Dependency Name | Old Version | New Version | Release Notes URL |
|-----------------|-------------|-------------|-------------------|
| ExampleLib      | 1.2.3       | 1.4.0       | [release notes](example.com/whats_new)   |


## Description

**Code Changes Made**
- What code changes were necessary to make the updated dependencies work.
- NOTE: Any non trivial changes should be done in a seperate PR

**Future Changes Needed**:
- What code changes will be necessary to make in the future and why.  Create and link shortcut stories as needed.

**Potential Risks**
- Highlight any potential risks this update might introduce.


## Ready to Review

All of the below must pass 100% before marking the PR as Ready to Review.  Any exceptions should be explained here or in the PR comments.

- ✅  All pre-submit unit tests pass
- ✅  All linter and static analysis warnings addressed
- ✅  All temporary testing code removed

## Before Merging

1. Merge the base branch (usually develop) into this branch first
2. Rerun all formatters, linters, and pre-submit unit tests and ensure all pass
