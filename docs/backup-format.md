# Backup Format

Taki Life OS exports app data as JSON from the Data tab. The backup is meant to be readable and easy to inspect before importing.

## Contents

A backup can include:

- Tasks and task status
- Habits and completion history
- Focus sessions
- Notes
- Expenses
- Theme and app settings

## Safety

Backups may contain personal information. Store exported files privately and avoid sharing them in public issues.

## Import Expectations

When importing a backup:

- The file should be valid JSON.
- The app should replace the current browser state with imported data.
- Users should export a fresh backup before testing imports with important data.

## Compatibility Goal

Future changes should keep old backups importable when possible. If a breaking format change is needed, document the migration path in the changelog.
