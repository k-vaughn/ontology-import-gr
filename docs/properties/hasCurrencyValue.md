# hasCurrencyValue

This property specifies the amount of money for a price per unit, shipping charges, or payment charges. The currency and other relevant details are attached to the respective gr:PriceSpecification etc.

For a gr:UnitPriceSpecification, this is the price for one unit or bundle (as specified in the unit of measurement of the unit price specification) of the respective gr:ProductOrService. For a gr:DeliveryChargeSpecification or a gr:PaymentChargeSpecification, it is the price per delivery or payment.

GoodRelations also supports giving price information as intervals only. If this is needed, use gr:hasMaxCurrencyValue for the upper bound and gr:hasMinCurrencyValue for the lower bound. 

Using gr:hasCurrencyValue sets the upper and lower bounds to the same given value, i.e., x gr:hasCurrencyValue y implies x gr:hasMinCurrencyValue y, x gr:hasMaxCurrencyValue y.

**Domain**: [PriceSpecification](../classes/PriceSpecification.md)

**Range**: [xsd:float](https://w3id.org/citydata/imported/xsd/float)

## Used in classes

| Class |
|-------|
| [PriceSpecification](../classes/PriceSpecification.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasCurrencyValue`
