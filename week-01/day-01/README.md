# Day 1 exercises

The day's notebook, with its reading and its exercises in the order of the slides: [`week-01-day-01.ipynb`](week-01-day-01.ipynb)

1. [Review a coding agent's change, and close every place a note leaks](find-note-leaks/README.md). Find each path that an agent's change opens for the text or the values of a note. Close each path, and keep what the change was for. Where: the folder `~/practice/week-01/day-01/find-note-leaks/extractor`, in VS Code and in a terminal. Done when: from `extractor`, `python3 ../check.py` prints a line that starts with `Done:`. Start: [`find-note-leaks/`](find-note-leaks/). Answer: [`answers/find-note-leaks/`](answers/find-note-leaks/).
2. [Classify four uses of AI tools with the data-rules check](data-rules-check/README.md). Classify a use of an AI tool with the data-rules check. Send a use that is not yours to decide to its owner. Where: the folder `~/practice/week-01/day-01/data-rules-check/lab`, in VS Code and in a terminal. Do not use AI tools. Done when: from `lab`, `python3 ../check.py` prints a line that starts with `Done:`. Start: [`data-rules-check/`](data-rules-check/). Answer: [`answers/data-rules-check/`](answers/data-rules-check/).
3. [Tighten your coding agent's configuration for the extractor's pilot](agent-boundary/README.md). Close the settings that let a coding agent reach real notes or act without your yes. Where: the folder `~/practice/week-01/day-01/agent-boundary/lab`, in VS Code and in a terminal. Do not use AI tools. Done when: from `lab`, `python3 ../check.py` prints a line that starts with `Done:`. Start: [`agent-boundary/`](agent-boundary/). Answer: [`answers/agent-boundary/`](answers/agent-boundary/).

## Maintaining the notebook

Maintain this checkout's notebook directly until the upstream generation workflow is confirmed. Keep the notebook valid JSON, preserve cell IDs and course content, and clear code outputs and execution counts before committing. Do not save instructor-specific Git identity commands, troubleshooting experiments, or a machine-specific kernel selection in the course notebook. Put reusable setup guidance in the root README and setup scripts.

The `metadata.catalyte` block records the original generator (`scripts/week/build_exercise_repository.py`), curriculum paths, source revisions, and a cell checksum. That generator and its curriculum sources are absent from this repository. The metadata is historical provenance, not evidence that the current notebook can be regenerated here; retain it without claiming a new generated checksum.

Ownership of the external generator remains unresolved. Before importing regenerated notebooks, identify its maintainer and source repository, carry course edits back into that source, and review the generated diff against this checkout so local improvements survive regeneration.

S1 validation: the committed notebook already contains the 58 intended cells with empty outputs and execution counts. The two instructor troubleshooting cells and recorded execution state existed only in the local working copy; removing them restores that committed artifact without changing lesson sources. Notebook JSON, cell IDs, lesson content, and provenance were checked against the upstream baseline. Full learner execution remains a separate validation task.
