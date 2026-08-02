# Storage layout

Runtime application state is stored outside Git.

- `/srv/containers`: persistent container application data
- `/srv/media`: media libraries
- `/srv/backups`: local backup staging
- `/srv/vm`: virtual-machine data

The Git repository contains deployment definitions and documentation only.
