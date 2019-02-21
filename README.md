# Dataset
1. all_projects.csv consists of list of projects corresponding to the different programming language. We have selected Python specific projects only.
2. Manual annotation folder consists of PR_LABELS.json consisting of all manually labeled pull requests along with the corresponding interaction types between generator and commenters. It has a format of:
{project name: {PR ID: {Commenter1: Score, Commenter2: Score}......}......}
3. Result folder consist of trust values and PR status corresponding to test data.
