# react-date-range-headless

A fork of https://github.com/hypeserver/react-date-range in which the Headless UI Listbox (Select) uses instead html select and options.

----

### Other differences from the original library 

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## 1.2.7

### Added
- `daySecondLessFirst` css-class style for Day, which is activated if the second date is less than the first


## 1.2.2

### Added
- `onHoverDate` prop for `<DateRange ... />` component: return hovered day in calendar, without redefining `onPreviewChange` prop logic

## 1.2.0

### Added
- `disableReverseDates` prop for `<DateRange ... />` component: disable reverse dates in DateRange component, when end date less than start date (Default: `false`)
