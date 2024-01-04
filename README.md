# Open Source Metrics

Documenting various metrics available for open source projects that can be used to visualize changes to the project over time and find correlations between metrics.

## Time series metrics

Time series metrics quantify patterns and trends in data over a chronological sequence

### Code contribution Metrics

| Metric                                   | Desired change direction | tbd |
|------------------------------------------|-----------------|-----------------|
| Number of commits                        |        ⬆️         |                 |
| Nubmer of unique committers              |        ⬆️        |                 |
| Number of bot commits                    |        -         |                 |
| Number of unique bot committers          |         -        |                 |
| Average number of commits per committer   |        ⬆️         |                 |
| Committer organization breakdown         |         ⬆️        |                 |
| Committer location breakdown             |         ⬆️        |                 |
| Lines of code added/removed              |         -        |                 |
| Average lines of code added/removed per committer |        -         |                 |
| Number of files changed                  |       -          |                 |
| Number of active branches                |        -         |                 |
| Number of new committers                 |        ⬆️         |                 |


### Bug tracker Metrics

#### Issues

| Metric                                    | Desired change direction | tbd |
|-------------------------------------------|-----------------|-----------------|
| Number of issues opened                   |         ⬆️        |                 |
| Number of issues closed                   |         ⬆️        |                 |
| Average time to close issues              |        ⬇️         |                 |
| Number of unique issue authors            |         ⬆️        |                 |
| Number of issue comments                  |         ⬆️        |                 |
| Average number of comments per issue      |        ⬆️         |                 |
| Number of bot issues                      |         -        |                 |
| Number of unique bot issue authors        |         -        |                 |
| Issue author association breakdown        |        -         |                 |
| Issue label breakdown                     |        -         |                 |
| Issue author organization breakdown       |        ⬆️         |                 |
| Issue author location breakdown           |        ⬆️         |                 |
| Ratio of self-close vs non-self-close      |       ⬆️          |                 |
| Average time to first response            |        ⬇️         |                 |
| Number of new issue authors               |        ⬆️        |                 |


#### Pull/Merge Requests

| Metric                                       | Desired change direction| tbd |
|----------------------------------------------|-----------------|-----------------|
| Number of pull requests opened               |         ⬆️        |                 |
| Number of pull requests closed               |        ⬆️         |                 |
| Average time to close/merge pull requests    |        ⬇️         |                 |
| Number of unique pull requests authors       |         ⬆️        |                 |
| Number of pull requests comments             |         ⬆️        |                 |
| Average number of comments per pull requests |         ⬆️        |                 |
| Number of bot pull requests                  |         -        |                 |
| Number of unique bot pull requests authors   |         -        |                 |
| Number of merged pull requests               |         ⬆️        |                 |
| Ratio of merged vs closed pull requests      |         ⬆️        |                 |
| Pull request author association breakdown    |         ⬆️        |                 |
| Pull request label breakdown                 |         -        |                 |
| Pull request author organization breakdown   |         ⬆️        |                 |
| Pull request author location breakdown       |         ⬆️        |                 |
| Number of pull request reviews               |         ⬆️        |                 |
| Number of unique pull request review authors |         ⬆️        |                 |
| Average number of reviews per pull request   |         ⬆️        |                 |
| Average time to review pull requests         |         ⬇️        |                 |
| Ratio of self-reviews vs non-self-reviews     |        ⬆️         |                 |
| Ratio of self-merges vs non-self-merges       |        ⬆️         |                 |
| Lines of code added/removed                  |         -        |                 |
| Number of files changed                      |        -         |                 |
| Average time to first response               |        ⬇️         |                 |
| Number of new pull request authors           |        ⬆️         |                 |


### Discussion/Mailing list Metrics

| Metric                              | Desired change direction | tbd |
|-------------------------------------|-----------------|-----------------|
| Number of posts                     |         ⬆️        |                 |
| Number of unique posters            |         ⬆️        |                 |
| Number of threads                   |         ⬆️        |                 |
| Average posts per thread            |         ⬆️        |                 |
| Average posts per poster            |         ⬆️        |                 |
| Number of new posters               |         ⬆️        |                 |


### Release Metrics

| Metric                               | Desired change direction | tbd |
|--------------------------------------|-----------------|-----------------|
| Number of releases                   |        ⬆️         |                 |
| Time between releases                |        ⬇️         |                 |
| Per release download counts         |         ⬆️        |                 |
| Number of dependents pinned to release|        -         |                 |
| Number of unique release authors     |         ⬆️        |                 |
| Number of new release authors        |        ⬆️         |                 |

### Populartity Metrics

| Metric                            | Desired change direction | tbd |
|-----------------------------------|-----------------|-----------------|
| Stars                             |        ⬆️         |                 |
| Forks                             |        ⬆️         |                 |
| Watchers                          |        ⬆️         |                 |
| Downloads                         |        ⬆️         |                 |
| Dependent packages                |        ⬆️         |                 |
| Dependent repositories            |        ⬆️         |                 |
| Dependent containers               |       ⬆️          |                 |
| Container Downloads               |        ⬆️         |                 |
| Page views                        |        ⬆️         |                 |
| Git clones                        |        ⬆️         |                 |
| Stackoverflow questions and answers|        ⬆️         |                 |


### Security Metrics

| Metric                               | Desired change direction | tbd |
|--------------------------------------|-----------------|-----------------|
| Number of vulnerabilities published  |         -        |                 |
| Number of unfixed vulnerabilities     |        ⬇️         |                 |
| Number of outdated dependencies       |       ⬇️          |                 |
| OpenSSF Scorecard score               |        ⬆️         |                 |


### Funding Metrics

| Metric                          | Desired change direction | tbd |
|---------------------------------|-----------------|-----------------|
| Income                          |        ⬆️         |                 |
| Expenses                        |         ⬆️        |                 |
| Balance                         |        -         |                 |
| Number of unique funders        |        ⬆️         |                 |
| Number of new funders           |        ⬆️         |                 |


## Binary Metrics

Binary metrics assess data with two possible outcomes, some times the time of the change can be found and so turned into a comparible time series metric.

### Maintenance Metrics

- Has an open source license
- Documents governance model
- Has contributing guideliens
- Has documentation

### Security Metrics

- Has a security policy document
- Uses CI
- Uses an automatic dependency updating tool
- Uses fuzzing tools
- Uses static analysis tools

## Sources

- [Ecosyste.ms](https://ecosyste.ms/) - Tools and open datasets to support, sustain, and secure critical digital infrastructure
- [Cauldron Projet Metrics](https://gitlab.com/cauldronio/cauldron/-/tree/master/guides/metrics)
- [OpenSSF Scorecard](https://github.com/ossf/scorecard) - Security health metrics for Open Source
- [CHAOSS](https://chaoss.community/kb-metrics-and-metrics-models/) - Community Health Analytics in Open Source Software
- [Open Source Metrics](https://opensource.guide/metrics/) - Make informed decisions to help your open source project thrive by measuring and tracking its success.
