# eligibleDuration

The minimal and maximal duration for which the given gr:Offering or gr:License is valid. This is mostly used for offers regarding accommodation, the rental of objects, or software licenses. The duration is specified by attaching an instance of gr:QuantitativeValue. The lower and upper boundaries are specified using the properties gr:hasMinValue and gr:hasMaxValue to that instance. If they are the same, use the gr:hasValue property. The unit of measurement is specified using the property gr:hasUnitOfMeasurement with a string holding a UN/CEFACT code suitable for durations, e.g. MON (months), DAY (days), HUR (hours), or MIN (minutes).

The difference to the gr:validFrom and gr:validThrough properties is that those specify the absiolute interval during which the gr:Offering or gr:License is valid, while gr:eligibleDuration specifies the acceptable duration of the contract or usage.

**Domain**: [License](../classes/License.md) or [Offering](../classes/Offering.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [QuantitativeValue](../classes/QuantitativeValue.md)

## Used in classes

| Class |
|-------|
| [License](../classes/License.md) |
| [Offering](../classes/Offering.md) |

**IRI**: `http://purl.org/goodrelations/v1/eligibleDuration`
