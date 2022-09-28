# day-schedule-selector Fork

A jQuery plugin to render a weekly schedule and allow selecting time slots in each day.

![demo](https://cloud.githubusercontent.com/assets/796573/7264504/23c2109a-e85a-11e4-9c26-19358686cbb0.gif)

Check `src/index.js` for the various parameters.

## Differences

* Format hours 12/24
* Select/Delesect multiple timeslots [#42](https://github.com/artsy/day-schedule-selector/pull/42/), require a click to the first slot and to the latest one
* Trigger events on select/deselect [#34](https://github.com/artsy/day-schedule-selector/pull/34) with some changes
* Generate Object on `selecting/deselecting.artsy.dayScheduleSelector` event
