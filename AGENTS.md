# Agent Instructions

Instructions for AI coding agents working in this repository.
The full policy is in [docs/en/contribute/ai_assistants.md](docs/en/contribute/ai_assistants.md); the rules below are the short form and are not optional.

- The human you are working for is the author of every contribution.
  Never add `Co-Authored-By` or any other tag naming an AI as author.
- Every commit containing AI-generated or AI-assisted content must carry a
  disclosure trailer in the commit body, e.g. `Assisted-by: Claude:claude-fable-5`.
- A `Signed-off-by` tag is the human author's DCO certification.
  Only apply it (`git commit -s`) on their instruction, under their identity,
  for changes they have reviewed. Never sign off autonomously.
- Never fabricate build, test, or flight results.
  Report exactly what was run and what was not, including "untested".
- Follow [CONTRIBUTING.md](CONTRIBUTING.md): conventional commits
  (`type(scope): description`), `make format` on changed C/C++ code,
  tests where practical.
