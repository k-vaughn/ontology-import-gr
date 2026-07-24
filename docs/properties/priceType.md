# priceType

This attribute can be used to distinguish multiple different price specifications for the same gr:Offering. It supersedes the former gr:isListPrice property. The following values are recommended:

The absence of this property marks the actual sales price.

SRP: "suggested retail price" - applicable for all sorts of a non-binding retail price recommendations, e.g. such published by the manufacturer or the distributor. This value replaces the former gr:isListPrice property.

INVOICE: The invoice price, mostly used in the car industry - this is the price a dealer pays to the manufacturer, excluding rebates and charges.

**Domain**: [UnitPriceSpecification](../classes/UnitPriceSpecification.md)

**Range**: [xsd:string](https://w3id.org/citydata/imported/xsd/string)

## Used in classes

| Class |
|-------|
| [UnitPriceSpecification](../classes/UnitPriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/priceType`
