# billingIncrement

This property specifies the minimal quantity and rounding increment that will be the basis for the billing. 
The unit of measurement is specified by the UN/CEFACT code attached to the gr:UnitPriceSpecification via the gr:hasUnitOfMeasurement property.

Examples: 
- The price for gasoline is 4 USD per gallon at the pump, but you will be charged in units of 0.1 gallons.
- The price for legal consulting is 100 USD per hour, but you will be charged in units of 15 minutes.

This property makes sense only for instances of gr:Offering that include not more than one type of good or service.

**Domain**: [UnitPriceSpecification](../classes/UnitPriceSpecification.md)

**Range**: [xsd:float](https://w3id.org/citydata/imported/xsd/float)

## Used in classes

| Class |
|-------|
| [UnitPriceSpecification](../classes/UnitPriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/billingIncrement`
