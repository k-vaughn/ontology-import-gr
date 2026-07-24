# advanceBookingRequirement

The minimal and maximal amount of time that is required between accepting the gr:Offering and the actual usage of the resource or service. This is mostly relevant for offers regarding hotel rooms, the rental of objects, or the provisioning of services. The duration is specified relatively to the beginning of the usage of the contracted object. It is represented by attaching an instance of the class gr:QuantitativeValueInteger. The lower and upper boundaries are specified using the properties gr:hasMinValueInteger and gr:hasMaxValueInteger to that instance. The unit of measurement is specified using the property gr:hasUnitOfMeasurement with a string holding a UN/CEFACT code suitable for durations, e.g. MON (months), DAY (days), HUR (hours), or MIN (minutes).

The difference to the gr:validFrom and gr:validThrough properties is that those specify the interval during which the gr:Offering is valid, while gr:advanceBookingRequirement specifies the acceptable relative amount of time between accepting the offer and the fulfilment or usage.

**Domain**: [Offering](../classes/Offering.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [QuantitativeValueInteger](../classes/QuantitativeValueInteger.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |

**IRI**: `http://purl.org/goodrelations/v1/advanceBookingRequirement`
