# DRAFT UNFINISHED PAGE 

## Version 4.0.3 released

We are pleased to announce that the version 4.0.3 of the ASVS has now been released! Thanks to the project leaders and other contributors for their support in getting this out.

This is not a big release but rather it is intended to fix spelling errors and make requirements clearer without making breaking changes such as materially changing requirements, strengthening requirements or adding requirements.

However, some requirements may have been slightly weakened where we felt appropriate and some entirely redundant requirements have been removed (but without renumbering). Nevertheless, Anyone using 4.0.1 or 4.0.2 should be able to smoothly start using 4.0.3.

This document notes some key changes.

### New signficant contributors

We have recognised some new significant contributors in the updated document.

First of all, we have included Elar Lang's new position as a leader of the project. Elar has spent many hours tirelessly working through issues, wording and generally trying to make the standard better. His promotion to leader is well deserved. 

We are also pleased to recognize Ralph Andalis and Sjoerd Langkemper as Major Contributors for their significant inputs over the last year or so.

### Deleting redundant/non-actionable requirements

There were a number of requirements which were almost direct duplicates of other pre-existing requirements. We have tried to remove some of these to make it easier to consume the standard. Similarly, certain requirements appeared to not be practically actionable. We have removed some of these as well. Wherever we have removed requirements, we have deliberately left the numbering as it was and added a note in the text of the requirement starting with "```[DELETED...]```".

### Requirement weakening

In a couple of examples we have reduced what is necessary to fulfil certain requirements where discussion concluded that this was appropriate. This allowed us to increase the accuracy of the standard without causing applications which would have previously passed a requirement to fail it.

Notably, we have not reduced the minimum length from 12. It is likely that in future versions, this will occur but only in conjunction with very explicit requirements around other password requirements as well as Multi-Factor Authentication requirements.

### Unifying section headers

Some headers included the word "Requirements", some did not. We have tried to remove that as standard and fix some other wording issues along the way.

### Full differences report

For a full differnces report between 4.0.2 and 4.0.3, see [this pull request](https://github.com/OWASP/ASVS/pull/1104/files?file-filters%5B%5D=.md&file-filters%5B%5D=.py&file-filters%5B%5D=.sh&file-filters%5B%5D=.yml&file-filters%5B%5D=No+extension).
