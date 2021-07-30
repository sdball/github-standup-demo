# github-standup-demo

How to use GitHub to run a standup

## Using individual worklogs and pull requests

1. Each member of the standup maintains a workflow markdown file e.g. [steve.md](./steve.md) and [alice.md](./alice.md)
2. For standup each member edits their worklog in a branch for that day
3. Open pull request from their branch back to main
4. The pull request is where questions/dicussion can be captured if the standups are async. Or clarifications can be captured if questions are synchronous in a meeting.
5. After standup: merge PR

Pros:
* Each team member can easily review work from other team members without having to scroll back in chat history or review a running document.
* Easy to view individual flows of work, especially for members that have left

Cons:
* Viewing the combined team work becomes a task of viewing multiple files.

## Using GitHub Issues per day

1. Each day of standup becomes a GitHub issue
2. Each member of the standup comments on the issue with their update
3. The issue is where questions/discussion can be captured if standups are async. Or clarifications can be captured if questions are synchronous in a meeting.
4. After standup: close the issue

Pros:
* Easy to view teams work as a whole
* More of a cohesive standup concept that members may be comfortable with

Cons:
* Less specific points for discussion: e.g. cannot easily discuss a specific line of an update
* Harder to see history of work for individual members

