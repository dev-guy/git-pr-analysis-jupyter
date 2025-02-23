# git-pr-analysis-jupyter
A notebook to analyze pull requests for one or more repositories, with the following analysis:

### All author aggregate analysis
Distribution of PRs into buckets: < 1 day, 1-2 days, 2-3 days, 3-4 days, > 4 days
- For time to first review
- For time to merge

### Per-author analysis
- Number of all PRs
- Number of PRs merged
- Time to first review (avg/median/max)
- Time to merge (avg/median/max)

## Usage

1. Get a GitHub personal access token for the repositories that you want to analyze. Required permissions are read-only for PRs and issues
2. Before running the notebook, specify:
  - Your GitHub personal access token
  - Which repositories to process

## Colab

Instead of using this repo, you can copy [this notebook](https://colab.research.google.com/github/dev-guy/git-pr-analysis-jupyter/blob/main/git-pr-analysis.ipynb) in Colab
