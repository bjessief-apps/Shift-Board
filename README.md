https://bjessief-apps.github.io/Shift-Board/

# Shift Board

A simple, private shift logger for warehouse crews. Log each shift's start and end-of-day numbers and door-by-door work, and the board ranks shifts and people for you.

## What it does

- **Overview:** containers completed, labor hours per container, shift vs shift comparison, weekly chart, fastest and slowest shifts.
- **Shifts:** every logged shift, sortable and ranked. Tap a shift to see its reports and edit numbers.
- **People:** rankings built from door logs: pieces credited, pieces per hour, containers credited, person-hours per container.
- **Log:** paste a start or end-of-day report and the numbers are read for you, or log a single door (door, piece count, crew, start and end time).
- **Setup:** opens first on a new device. Your warehouse or agency name, worker title, your own shift schedules (name, days, start and end times), and your crew, plus backup and restore.

## Privacy

There is no backend and no account. Everything is saved only in the browser on your device. Nothing you enter is uploaded or included in this repository. Use **Setup → Save backup** to keep a copy or to move your data to another device.

## How credit is split

- Each door's credit is split evenly across the crew on it. A rolled-over door counts as half.
- Labor hours per container = workers × scheduled shift hours ÷ containers completed. Shift hours come from each shift's start and end times in Setup.
