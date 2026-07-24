# deliveryLeadTime

This property can be used to indicate the promised delay between the receipt of the order and the goods leaving the warehouse.

The duration is specified by attaching an instance of gr:QuantitativeValueInteger. The lower and upper boundaries are specified using the properties gr:hasMinValueInteger and gr:hasMaxValueInteger to that instance. A point value can be modeled with the gr:hasValueInteger property. The unit of measurement is specified using the property gr:hasUnitOfMeasurement with a string holding a UN/CEFACT code suitable for durations, e.g. MON (months), DAY (days), HUR (hours), or MIN (minutes).

**Domain**: [Offering](../classes/Offering.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [QuantitativeValueInteger](../classes/QuantitativeValueInteger.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |

**IRI**: `http://purl.org/goodrelations/v1/deliveryLeadTime`
