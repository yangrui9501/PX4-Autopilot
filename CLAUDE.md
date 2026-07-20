# PX4-Autopilot

Safety-critical C/C++ flight control firmware for autopilots, plus SITL
simulation and Python tooling.

- **Commits:** use the `/commit` skill. Conventional commit format with
  topic-based scope: `type(scope): description`.
- **Pull requests:** use the `/pr` skill.
- **AI policy:** follow @AGENTS.md. Disclose with an `Assisted-by:` commit
  trailer. Never `Co-Authored-By: Claude`, never a "Generated with Claude
  Code" footer.
- **Style:** run `make format` on changed C/C++ before committing; CI
  enforces `make check_format`.
