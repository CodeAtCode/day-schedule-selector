# day-schedule-selector Fork

A jQuery plugin to render a weekly schedule and allow selecting time slots in each day.

![demo](https://cloud.githubusercontent.com/assets/796573/7264504/23c2109a-e85a-11e4-9c26-19358686cbb0.gif)

Check `src/index.js` for the various parameters

## Events
The following custom events are triggered on the element.

#### selected.artsy.dayScheduleSelector
Triggered when a selection is made. Passes the event and an array of selected time slots to the event handler.
```javascript
$("#weekly-schedule").on('selected.artsy.dayScheduleSelector', function (e, selected) {
  /* selected is an array of time slots selected this time. */
}
```
