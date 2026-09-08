# Workspace isolation

- This directory is the hard write boundary for this project. Treat sibling projects as read-only unless the user explicitly requests cross-project work.
- Keep permanent sources and deliverables inside this directory.
- Put every disposable artifact only in `My_Diy/_TEMP/firmware-ota/<task-id>/`; remove that task directory before finishing.
- Never create generic `tmp`, `output`, `runtime`, logs, archives, browser profiles, or test databases in the `My_Diy` root or another project.

