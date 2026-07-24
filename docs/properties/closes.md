# closes

The closing  hour of the gr:Location on the given gr:DayOfWeek.
If no time-zone suffix is included, the time is given in the local time valid at the gr:Location.

For a time in GMT/UTC, simply add a "Z" following the time:

09:30:10Z.

Alternatively, you can specify an offset from the UTC time by adding a positive or negative time following the time:

09:30:10-09:00

09:30:10+09:00.

Note 1: Use 00:00:00 for the first second of the respective day and 23:59:59 for the last second of that day.
Note 2: If a store opens at 17:00 on Saturdays and closes at 03:00:00 a.m. next morning, use two instances of this class, one with 17:00:00 - 23:59:59 for Saturday and another one with 00:00:00 - 03:00:00 for Sunday.
Note 3: If the shop re-opens on the same day of the week or set of days of the week, you must create a second instance of gr:OpeningHoursSpecification.

**Domain**: [OpeningHoursSpecification](../classes/OpeningHoursSpecification.md)

**Range**: [xsd:time](https://w3id.org/citydata/imported/xsd/time)

## Used in classes

| Class |
|-------|
| [OpeningHoursSpecification](../classes/OpeningHoursSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/closes`
