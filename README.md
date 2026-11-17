# schedule

Static timetable for El's availability: **https://asaeltarigan.github.io/schedule/**

`index.html` is generated from the live `schedule.json` by
`~/.hermes/scripts/build_schedule_static.py` and pushed automatically when the
schedule changes. Do not edit `index.html` by hand.

View-only by design: booking was removed from the public page, so meetings go
through email. The FastAPI app keeps running locally on port 8033 for admin use.
