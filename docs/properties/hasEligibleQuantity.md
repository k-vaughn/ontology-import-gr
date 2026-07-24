# hasEligibleQuantity

This specifies the interval and unit of measurement of ordering quantities for which the gr:Offering or gr:PriceSpecification is valid. This allows e.g. specifying that a certain freight charge is valid only for a certain quantity.
Note that if an offering is a bundle, i.e. it consists of more than one unit of a single type of good, or if the unit of measurement for the good is different from unit (Common Code C62), then gr:hasEligibleQuantity refers to units of this bundle. In other words, "C62" for "Units or pieces" is usually the appropriate unit of measurement.

**Domain**: [Offering](../classes/Offering.md) or [PriceSpecification](../classes/PriceSpecification.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [QuantitativeValue](../classes/QuantitativeValue.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [PriceSpecification](../classes/PriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasEligibleQuantity`
