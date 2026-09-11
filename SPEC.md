# TARGET: today's build

- **Thing:** A one-page student-life schedule optimizer with a color-coded weekly calendar, a compact monthly overview, and an “Optimize my week” action that places a new task around example classes, clubs, recruiting, social, and self-care blocks.
- **Audience:** An overwhelmed college student who needs a calm, clear plan for classes, clubs, homework, recruiting, social commitments, emails, and self-care.
- **Requirements:** One working primary interaction: the visitor adds a task with importance, rigidity, and time-sensitivity, then optimizes the schedule. Fixed commitments remain visible; the resulting placement and priority reason are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Use clearly labeled sample schedule data. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A calm Apple Calendar-inspired interface with a light-gray background, rounded calendar tables, bold pastel task colors, and clear weekly/monthly views. Color and labels distinguish classes, clubs, recruiting, social events, tasks, and flexible self-care.
- **Test:** I can add a high-priority, time-sensitive task, optimize the weekly schedule, verify that fixed commitments were not moved, see a flexible self-care block rescheduled when necessary, and identify the priority explanation in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
