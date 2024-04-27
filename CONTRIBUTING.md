# Contributing

**This document applies to all those who want to contritubte to this project from 2024 and may change at a future date.**

<!--

## General description

open issue > discuss, if agreed > pull request


## Versions

for what versions what kind of changes are allowed

definition of breaking change


## Opening issue

expectation from issue


## Pull-request

expectation from PR
-->

### Introduction

The current status of the SPVS project is as follows:

> The SPVS project is in a planning stage, still in phase 1 of our roadmap.


### How to make changes this project

> Once we have uploaded our inital set of standards you may contribute by opening a issue and we will dsicuss via the issues, if agreed we will need a pull request with changes.

### Standard for changes

#### Keep all current numbers

* New requirements must be placed at the end of sub-category
* Deleted requirements must keep "placeholder" to avoid some other requirements to be added/moved to that number, examples:


#### Use tags to describe the change

The following tags should be added to any modified requirement as appropriate. These tags should all be relative to how the requirement appeared in v4.0.3.

* `[ADDED]` - New requirement (should only be added at the end of a sub-section.)
* `[ADDED, SPLIT FROM x.y.z]` - New requirement which was previously part of another requirement
* `[MODIFIED]` - Requirement description has been modified
* `[MOVED FROM x.y.z]` - Requirement has been moved to a different sub-section but **not** modified. (should only be added at the end of a sub-section.)
* `[MODIFIED, MOVED FROM x.y.z]` - Requirement description has been modified **and** requirement has been moved to a different sub-section.
* `[MOVED TO x.y.z]` - Placeholder to keep number, requirement has been moved to another category (but not modified).
* `[DELETED]` - Placeholder to keep number, requirement has been deleted
* `[DELETED, MERGED TO x.y.z]` - Placeholder to keep number, requirement has been merged into another requirement, e.g. to solve a duplicate
* `[LEVEL L1 > L2]` - Requirement's level has changed

CWE and/or NIST mapping changes do not require labels.

Tags must be placed before verification description, example:

```
| **12.4.2** | [MODIFIED] Verify that files obtained from untrusted sources are scanned by antivirus scanners to prevent upload and serving of known malicious content. | ✓ | ✓ | ✓ | 509 |
```


