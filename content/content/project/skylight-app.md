---
title: Skylight App
date: 2025-11-09T09:30:00-07:00
type: project
tags: [task management, user management, testing]
summary: Created a README. Migrated task and user models to asynchronous versions. Updated tabs. Streamlined database setup. Added placeholder tabs and a testing framework.
status: in-progress
reading_time: 3
related:
  - /project/gift-registry
links:
  - text: GitHub repository
    url: https://github.com/thephinux132/skylight-app
---

- Created a README.
- Migrated the task model to an asynchronous version and removed the old model.
- Updated the Tasks tab to use the new model.
- Migrated the user model to an asynchronous version and removed the old model.
- Removed explicit database initialization and deleted the old database to allow for lazy table creation.
- Added placeholder Calendar, Meals, and Settings tabs.
- Set up a tests directory and added a basic CRUD test for the task model.
- Resolved import errors, missing dependencies, module not found issues, and database schema inconsistencies.

Next step: Implement user interface improvements and more tests.
