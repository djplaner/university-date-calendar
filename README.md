# university-date-calendar

Experiment with singleton web component (based on [example](https://github.com/elmsln/lrnwebcomponents/tree/master/elements/file-system-broker#readme) from [@bto-pro](https://twitter.com/btopro))

Intent is to allow different universities to provide institution specific date information and methods for use with the [university-date component](https://github.com/djplaner/university-date)

## Current institution specific data/methods

CALENDAR
- Specifies the start/stop dates for the weeks for all periods (e.g. semesters) for an institution
- Object of objects (hash of hashs for Perl folk)

getCurrentPeriod
- Function that figures out what the current period based on content in the current web page.
- The example looks for the period within a specific element

## Setup

Install dependencies:

```bash
npm i
```

## Example

There is an example HTML file located at `/dev/index.html` 
