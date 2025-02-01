# Contributing Guide
We welcome any contributions to Project Rose!

Here is a run down of everything you need to know:

# Code of Conduct
## Be respectful
No personal attacks, nor harassment of others will be tolerated.
## Think before you speak
Before hitting the "send" button, think of what you are saying is mature and professional. If it is something possibly sensitive, you can privately message a developer.
## Keep things relevant
Only talk about things that actually should be mentioned.

# Workflow
## Branches
There will *typically* be a `main` branch, a `staging` branch, and `dev` branch. The `main` branch is what is currently being pushed in production (what is currently active). The `dev` branch is  where all the development occurs - it will eventually get merged into the `staging` branch. The `staging` branch is where everything from the `dev` branch is put when it is in its testing phase. When everything is good, it will be merged into `main`.

Generally, unless you are committing a simple fix, do not commit directly to these branches. Make a fork (or make a branch, preferably have it be `yourname/what-you-are-doing` so we know who is primarily working on what, and then open a pull request.

## Pull Requests
Ideally, keep them short and simple. This is for the purposes of review and keeping the code manageable. Every PR should be reviewed by at least one other person, as code tends to become increasingly complex over time. The goal is to have another person be able to look at the code and understand what it is doing.

### Draft PRs/Untested commits
If your PR is incomplete or it is untested, mark it as a draft.

### But what if my feature/bug fix/what I am working on is incomplete?
**That is okay!** The `dev` branch does not have to be perfect. A feature does not need to be perfect and extended as far as possible. Start small, then once the small feature is working, it can be extended and improved upon. Just leave a note saying that it is incomplete.

## Commits
**Do not be afraid to commit!** It is good to have a history of how the code changes over times. Even if it is one-line code fixes, or even if it is an incomplete feature - commit anyways. If you are in a state where you are working on many features at once, **it is okay to push only specifically chosen modified files in your workspace.**

### Naming
Have it be logical and professional. The commit name should say what you are fixing or improving or adding and to what specific module. It should NOT be something including "i hate this", or "this is messy", or "pls help" - even as a side-statement.

Good commits look like this:
`accounts api: added /create endpoint`
`fixed styling in provider setup menu`

# Questions
Don't ask to ask - just ask!
