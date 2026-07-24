# validThrough

This property specifies the end of the validity of the gr:Offering, gr:PriceSpecification, gr:License, or gr:OpeningHoursSpecification.
A time-zone should be specified. For a time in GMT/UTC, simply add a "Z" following the time:

2008-05-30T09:30:10Z.

Alternatively, you can specify an offset from the UTC time by adding a positive or negative time following the time:

2008-05-30T09:30:10-09:00

or
2008-05-30T09:30:10+09:00.

Note 1: If multiple contradicting instances of a gr:Offering, gr:PriceSpecification, or gr:OpeningHoursSpecification exist, it is a good heuristics to assume that
1. Information with validity information for the respective period of time ranks higher than information without validity information.
2. Among conflicting nodes both having validity information, the one with the shorter validity span ranks higher.
Note 2: For Google, attaching a gr:validThrough statement to a gr:UnitPriceSpecification is mandatory. 


**Domain**: [License](../classes/License.md) or [Offering](../classes/Offering.md) or [OpeningHoursSpecification](../classes/OpeningHoursSpecification.md) or [PriceSpecification](../classes/PriceSpecification.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [xsd:dateTime](https://w3id.org/citydata/imported/xsd/dateTime)

## Used in classes

| Class |
|-------|
| [License](../classes/License.md) |
| [Offering](../classes/Offering.md) |
| [OpeningHoursSpecification](../classes/OpeningHoursSpecification.md) |
| [PriceSpecification](../classes/PriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/validThrough`
