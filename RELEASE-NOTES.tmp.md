# Release trigger diagnostics
#
# Last verified: 2026-08-13 (JARVIS)
# - workflow_dispatch on Release: FIRES (run 31698829749, success)
# - push to dev (non-.github change): used to NOT fire Release;
#   a no-filter probe workflow DOES fire on push. See push-probe.yml.