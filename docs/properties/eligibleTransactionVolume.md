# eligibleTransactionVolume

This property can be used to indicate the transaction volume, in a monetary unit, for which the gr:Offering or gr:PriceSpecification is valid. This is mostly used to specify a minimal purchasing volume, to express free shipping above a certain order volume, or to limit the acceptance of credit cards to purchases above a certain amount.

The object is a gr:PriceSpecification that uses the properties gr:hasMaxCurrencyValue and gr:hasMinCurrencyValue to indicate the lower and upper boundaries and gr:hasCurrency to indicate the currency using the ISO 4217 standard (3 characters).

**Domain**: [Offering](../classes/Offering.md) or [PriceSpecification](../classes/PriceSpecification.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [PriceSpecification](../classes/PriceSpecification.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [PriceSpecification](../classes/PriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/eligibleTransactionVolume`
