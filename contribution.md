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
- Encourage sense of community ownership (creating opportunities for people to contribute to the space.)
- Decrease Bug Fix turnaround time.
    - It should be easy to fix typos, confusing wording, outdated/deprecated procedures.
    The Makerspace is a living dynamic place with new things being added/created all the time. 
    This requires our documentation to be equally accommodating to change.

## Key Technologies
### Markdown
Markdown is a simple file format. The raw file format only contains text (no formatting).
This raw file can then be run though a renderer to create a more visually appealing format.
Markdown is specificity designed to be understandable in both its raw and formatted forms.

NOTE: There are a few different flavors of Markdown. We will be using [GitHub flavored Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#section-links).

### Git
Git is a version control tool designed for collaborating on text documents. 
Git supports branching histories where each user gets their own copy of the document that they can work on independently.
These branches can then be merged back together.
These are the two key concepts to remember: git collaboration is about **Branching and merging**.

### GitHub
GitHub is a code hosting and team management solution.
Git allows us to:
- Manage Permissions and access 
- Track work that needs to be done (Issues) 
- Track work in progress (Pull requests)
- Hosts the content online in a publicly accessible place.

## Key Terms
### Issue
**A description of a problem.**
Anyone with a GitHub account (even if they have not been added as a collaborator) can create [Issues](#issue) documenting that something "Is not how it should be".
A good issues has a few parts:
- A concise, descriptive name
- Who does the issues effect 
- What is it blocking/What are the consequences of this issues.
    - "This wording is confusing" is a valid issues.
    - "I think rockets are cool" is not.
    - "Investigate the possibility of creating a bottle rocket module for STEM camp" could be depending on how the rest of the issue is written.
- Suggested fix
    If the issue writer knows how to fix this issues (or at least has an idea) they can note that down.
    This field is not required since the solution may required discussion and is non obvious.
- Steps to reproduce
    - If there is a specific sequence of events that happen for the problem to occur, document it.
    - It is not the reviewers' job to figure out what esoteric set of 3d printer settings you used.
        If you are assigned an issues without clear steps to reproduce don't waste time tying to figure it out.
        Use the '@' key to tag the original issue author and ask for clarification.
        If they don't respond, close the issue as 'could not reproduce'.
Spending the time to creating a well defined issues is mostly about **defining a unit of work** that can hand off to someone else.
If you are assigning the issue to yourself rather than hand it off to someone else you can be looser/less rigorous with each of those sections.

Issues are all about **defining the work to be done**. What is the **actual problem** that needs to be resolved.
### Branch 
A branch is **a** history of changes. Note the canonical branch (the actual released published documentation) is called **main**.
An issues is not considered fixed until it is fixed in main.
You are not allowed to edit main directly, instead you must make a new branch and make your changes there.

### Pull Request
>"Pretty pretty please accept my changes into main" (the canonical released documentation).
>
>–Pull Request Author

Opening a pull request is saying please accept my changes into your branch (normally the main branch).
The changes are then reviewed, errors identified and sent back to the original author for them to fix.

Pull requests track discussion and comments **about the work in progress**.
(NOTE: you can open a draft pull request to say "I would like to start getting feed back, but this is not yet ready for release".)

### Commit
A save point. If you need more then that come talk to me (Jacob Riesen). You are probably stepping into the advanced rabbit hole and have not yet realized that.

### Closed
This [Issues](#issue)/[Pull Request](#pull-request) has been resolved/dealt with. Common reasons for closing something include:

- Fixed
- Duplicate
    - Link to what it is a duplicate of. 
    - Example: Five people opening issues about the same typo.
- Won't Fix / Invalid
    - List reason for why it is not done.
    - Examples: Not in line with Workspace goals/mission statement. Not worth the time/money required to implement.
- Stale/Abandoned
    - Example: Someone started a pull request 2 years ago but it stalled out or the author lost interest.
    - In this case I would close the pull request as stale and reassign the associated issue to someone else.
- Could not reproduce
- Unclear issues 
    - Issues author did not clearly defined what their issue actually was/did not respond when asked for clarification.

### Open 
This [Issues](#issue)/[Pull Request](#pull-request) is still active.

## Workflows
There are 4 main workflows/roles that shepherd a proposal/issues into released documentation.

### Roles

#### Normal Volunteer
You, unless you have been specificity told otherwise.

- Issue Identification
- Change Proposal.

#### Admin Volunteer
Talk to a Workspace Staff member if you are interested in becoming an Admin Volunteer

- Issue Triage
- Change Proposal Review 

#### Workspace Staff
- Final Change Proposal Review.

### Issue Identification 
> Something is not as it should be. Document it so we can start to address it.

There are two main types of issues.
- Bug fixes (something is outdated or wrong.)
- Feature requires (It would be really neat if we could do X)

Steps:

- See something that is wrong or think of a new feature
- Open the [Issues page](https://github.com/NIACCInnovWork/WorkspaceDocumentation/issues) of the repository
- Click on the **New Issue** button
- Fill out the issue.
    See [key terms issue](#issue) for what makes a well written issue. (Note well written issues tend to be easier to resolve and therefore get resolved faster.)
- Click the **Create** button
- Respond to any clarifying questions.
    Questions may come up when the issue gets triaged/worked on. If that happens you will get an email. Your answer should be added as a comment on the issue. 

### Issue Triage
Process the issue. Get clarification and ask the tough questions.

Steps:

- Is there any necessary information that is missing from the issue? 
    - If so leave a comment asking for clarification.
- Is this something that should be done?
    If any of the following are true:
    - It is a bad idea,
    - There is some reason it can't be done,
    - It is not in line with the workspaces mission statement

    Then add a comment explaining your reasoning and close the issue as **Won't Fix**
- Is this something that would be good to do, but we don't have time at the moment?
    - Tag the Issue **Planned**
- Who should do this?
    - Assign the issues to whoever has the requisite knowledge, skills and/or time.

### Development
Implementing the change.

- You are assigned an issue.
- Read the issues.
    - If you need clarification add a comment, the issue author will be email.
- Create a branch
    - From the Issue page click "create a branch".
- Open your branch. \
    There are multiple ways of opening a branch.
    - From the homepage -> click the **Branches** button -> click on the branch you want to open.
    - From the Issue Page -> In the side panel under Development click the branch name.
    - From a file -> Locate the filepath. Immediately left of that is the branch name. -> Click on the current branch, a dropdown menu will appear. -> Select the branch you want.
- Edit the files. \
    Click the edit this file button.
- Commit (save) your changes
    Click the **Commit Changes** button. 
    Add a brief description of the change and optionally why you did it.
    "Fix Typo" is a fine commit message. 
- Open a pull requests.
    Once you are happy with your modifications open up a pull request.
    This signals that you are ready for someone to review your changes.
- Respond to and fix any issues that the reviewer finds.
- Request re-review
    When you have made the requested changes hover over the reviewers name and click "Request Re-Review"

### Change Proposal Review 
- You are assigned a Pull Request to review. (You will get an email.)
- Click on the Pull Requests tab then click on the Pull Request you were assigned.
- Read though any existing conversation.
- Click on the "Files Changed" tab.
- Read though the proposed change.
- If you find an issue
    - Hover over the problematic line.
    - Click on the blue "+".
    - Leave your comment
    - Click ***"Start a review"*** If you do this the developer will get one email after you are done with your review. If you hit Comment they will get an email per comment. (which is annoying)
- Finish your review. 
    - Click the Finish your review button (upper right hand of the screen)
    - If there were no issues click approve.
    - If there were issues click request changes.

### Change Proposal Review 
If you are the final reviewer (Workspace staff) go through the normal review process and then 

- Merge the branch
- Delete the branch
- Close the Pull Request and associated Issues. (GitHub Tryies to do this automatically but sometimes you need to step in and correct things.)
