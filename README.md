# Overtime App

## Key requirement: company needs documentation that salaried employees did or not get overtime each week

## Models:
- x Post -> date:date, rationable:text
- x User -> Devise gem
- x AdminUser -> STI from User.

## Features:
- Approval Workflow.
- SMS Messages -> Link to log time.
- Admin dashboard -> Administrate gem
- Email Summary to Admin Users for approval
- Need documentation for Overtime

## UI:
- x Bootstrap -> formatting

## Refactor TODOS:
- x Add full_name method for users
- Refactor user association integration test in post_spec
