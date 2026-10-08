# Westport Weeknight Minyan Planner

A single-page planning widget that compares MyZmanim values for Westport, Connecticut 06880 with Metro-North New Haven Line schedules from Grand Central to Westport.

## Published files

GitHub Pages deploys the contents of `dist/`. The site is static and requires no build step.

## Local preview

From the project directory, serve `dist/` with any static HTTP server. For example:

```powershell
python -m http.server 4173 --directory dist
```

Then visit `http://127.0.0.1:4173/`.

## Updating the sample

Before changing the recommended service time, re-check:

- MyZmanim daily values for ZIP code 06880.
- The official MTA Metro-North timetable or GTFS feed.
- The 10-minute transfer from Westport station to the shul.
- The shul rabbi's guidance concerning Mincha and Maariv timing.

This project is a planning aid, not a halachic ruling or a guarantee of train service.
