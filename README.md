# pipeline-lab

### GitHub has a pipeline runner built into every repository. It is switched on by a single file: anything you place
at the path .github/workflows/ci.yml is treated as a pipeline definition, and GitHub runs it automatically on
every push (on their machines, not yours). The file is just a list of steps that run in order, and the first step
that fails stops the run and marks it red. That is the whole mechanism
