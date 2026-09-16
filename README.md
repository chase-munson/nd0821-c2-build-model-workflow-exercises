# ML DevOps Nanodegree — Course 2: Build a Reproducible Model Workflow (Exercises)

Completed exercises and demos for Udacity's ML DevOps Engineer Nanodegree,
Course 2. This is Udacity's own course content — the instructions, starter
code, and demos are theirs (see `LICENSE.md`); this fork holds my completed
exercise solutions on top of it.

## What's here

Code is organized by the lesson it belongs to:

- **`lesson-1-machine-learning-pipelines/`** — intro to structuring an ML
  project as a pipeline of independent, reusable steps.
- **`lesson-2-data-exploration-and-preparation/`** — exploring and cleaning
  a raw dataset before it's fit to train on. Exercise 4 in this lesson uses
  a music-genre dataset that I later built out into a full standalone
  pipeline — see my `genre_classification` repo.
- **`lesson-3-data-validation/`** — automated checks (schema, statistical
  tests) that gate bad data out of a pipeline before it reaches training.
- **`lesson-4-training-validation-experiment-tracking/`** — training models
  inside the pipeline and tracking every run's parameters, metrics, and
  artifacts.
- **`lesson-5-final-pipeline-release-and-deploy/`** — tagging a pipeline
  version as a release and running it directly from its Git repository.

Each lesson folder contains a `demo/` and an `exercises/` directory; each
exercise has its own `README.md`, plus `starter/` and `solution/`
subdirectories. Some exercise-specific setup (API keys, environment
variables) is only described in the Udacity classroom, per the original
course instructions.
