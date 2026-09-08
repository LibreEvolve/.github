# Contributing

Use the instructions in the repository you are changing first. These shared
defaults apply only where a repository has no more specific contribution guide.

For the public LibreEvolve engineering preview, start with its
[development guide](https://github.com/LibreEvolve/libreevolve/blob/main/docs/development.md)
and [quickstart](https://github.com/LibreEvolve/libreevolve/blob/main/docs/alpha-quickstart.md).
For another repository, use its own README and local checks; do not assume the
preview's commands or support scope apply.

## Propose a focused change

- Search existing issues and pull requests in the affected repository.
- Describe the problem, expected behavior and a small reproducible example.
- Work on a branch and preserve unrelated changes. Keep the patch reviewable.
- Run the relevant local checks and report their exact results and limitations.
- Distinguish offline tests, live model use, hosted CI and deployed behavior.
  Do not make live provider calls an incidental test without authorization.

Only include material you have permission to share with that repository's
audience. Remove credentials, account identifiers, home paths, raw prompts and
private source from examples. Do not move private-repository evidence into a
public issue or pull request to make it easier to link.

Explain changes to evidence interpretation, source selection or execution
boundaries explicitly. A source hash identifies bytes; it does not authenticate
an experiment or prove a result. Claims should identify the checks behind them.

Be specific and respectful in review. Critique the work, not the person. A pull
request proposes a change; it does not promise acceptance or a response deadline.
