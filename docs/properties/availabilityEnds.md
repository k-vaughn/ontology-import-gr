# availabilityEnds

This property specifies the end of the availability of the gr:ProductOrService included in the gr:Offering.
The difference to the properties gr:validFrom and gr:validThrough is that those specify the period of time during which the offer is valid and can be accepted.

Example: I offer to lease my boat for the period of August 1 - August 31, 2010, but you must accept by offer no later than July 15.

A time-zone should be specified. For a time in GMT/UTC, simply add a "Z" following the time:

2008-05-30T09:30:10Z.

Alternatively, you can specify an offset from the UTC time by adding a positive or negative time following the time:

2008-05-30T09:30:10-09:00

or

2008-05-30T09:30:10+09:00.

Note: There is another property gr:availableAtOrFrom, which is used to indicate the gr:Location (e.g. store or shop) from which the goods would be available.

**Domain**: [Offering](../classes/Offering.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [xsd:dateTime](https://w3id.org/citydata/imported/xsd/dateTime)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |

**IRI**: `http://purl.org/goodrelations/v1/availabilityEnds`
