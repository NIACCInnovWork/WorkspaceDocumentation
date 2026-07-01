# Contributing Guide
Thank you for you interest in helping improve the Makerspace documentation.
There are many ways of helping out for example:
- Opening issues
- Fixing typos 
- Updating outdated/broken documentation.
- Adding examples of how the machines preform under different settings
- Documenting project tutorials 
- Help write trainings 
- Help review trainings
## Documentation Initiate Goals
- Provide high quality documentation for our members.
- Encourage since of community ownership (creating opportunities for people to contribute to the space.)
- Decrease Bug Fix turnaround time.
    - It should be easy to fix typos, confusing wording, outdated/deprecated procedures.
    The Makerspace is a livening dynamic place with new things are created all the time. 
    This requires our documentation to be equally accommodating to change.
## Key Technologies
### Markdown
Markdown is a simple file format. The raw file format only contains text (no formatting).
This raw file can then be run though a renderer to create a printer formatted document.
Markdown is specificity designed to be understandable in both its raw and formatted forms.

NOTE: There are a few different flavors of Markdown we will be using [GitHub flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links).

### Git
Git is a version control tool designed for collaborating on text documents. 
Git supports branching histories where each user gets their own copy of the document that they can work on independently.
These branches can then be merged back together.
These are the two key concepts to remember, git collaboration is about **Branching and merging**.

### GitHub
GitHub is a code hosting and team management solution.
Git allows us to:
- Manage Permissions and access. 
- Track work that needs to be done (Issues) 
- Track work in progress (Pull requests)
- Hosts the content online in a publicly accessible place.
## Key Terms
### Issue
**A description of a problem.**
Anyone with a GitHub account (even if they have not been added as a collaborator) can create [Issues](#issue) documenting that something "Is not how it should be".
A good issues has a few parts:
- A good name
- Who does the issues effect. 
- What is it blocking/What are the consequences of this issues.
    - "This wording is confusing" is a valid issues.
    - "I think rockets are cool" is not.
    - "Investigate the possibility of creating a bottle rocket module for STEM camp" could be depending on how the rest of the issue is written.
- Suggested fix.
    If the issue writer knows how to fix this issues (or at least has an idea) they can note that down.
    This field is not required since the solution may required discussion and is non obvious.
- Steps to reproduce
    - If there is a specific sequence of events that happen for the problem to occur, document it.
    - It is not the reviewers job to figure out what esoteric set of 3d printer settings you used.
        If you are assigned an issues without clear steps to reproduce don't waist time tying to figure it out. @ the original issue author asking for clarification and if they don't respond close as "could not reproduce".
Spending the time to creating a well defined issues is mostly about **defining a unit of work** that can hand off to someone else.
If you are assigning the issue to yourself rather than hand it off to someone else you can be loser/less rigorous with each of those sections.

Issues are all about **defining the work to be done**. What is the **actual problem** that needs to be resolved.
### Branch 
A branch is **a** history of changes. Note the canonical branch (the actual released published documentation) is called **main**.
An issues is not considered fixed untill it is fixed in main.
You are not allowed to edit main directly, instead you must make a new branch and make your changes there.

### Pull Request
Pretty pretty please accept my changes into main (the canonical released documentation).

Opening a pull request is saying please accept my changes into your branch (normally the main branch).
The changes are then reviewed, errors identified and sent back to the original author for them to fix.

Pull request track discussion and comments **about the work in progress**.
(NOTE: you can open a draft pull request to say "I would like to start getting feed back, but this is not yet ready for release".)
### Commit
A save point. If you need more then that come talk to me (Jacob Riesen) you are probably stepping into the advanced rabbit hole and have not yet realized that.
### Closed
This [Issues](#issue)/[Pull Request](#pull-request) has been resolved/dealt with. Common reasons for closing something include:
- Fixed
- Duplicate
    Link to what it is a duplicate of. 
    Example: Five people opening issues about the same typo.
- Considered not done
    List reason for why it is not done.
    Examples: Not in line with Workspace goals/mission statement. Not worth the time/money required to implement.
- Stale/Abandoned
    Example: Someone started a pull request 2 years ago but it stalled out/ the author lost interest.
    In this case I would close the pull request as stale and reassign the associated issue to someone else.
- Could not reproduce
- Unclear issues
    Issues author did not clearly defined what their issue actually was/did not respond when asked for clarification.
### Open 
This [Issues](#issue)/[Pull Request](#pull-request) is still active.
