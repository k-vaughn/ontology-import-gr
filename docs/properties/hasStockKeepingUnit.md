# hasStockKeepingUnit

The Stock Keeping Unit, or SKU is a unique identifier for a product, service, or bundle from the perspective of a particular supplier, i.e. SKUs are mostly assigned and serialized at the merchant level. 
Examples of SKUs are the ordering or parts numbers used by a particular Web shop or catalog.

Consequently, the domain of gr:hasStockKeepingUnit is the union of the classes gr:Offering and gr:ProductOrService. 
If attached to a gr:Offering, the SKU will usually reflect a merchant-specific identifier, i.e. one valid only for that particular retailer or shop. 
If attached to a gr:ProductOrServiceModel, the SKU can reflect either the identifier used by the merchant or the part number used by the official manufacturer of that part. For the latter, gr:hasMPN is a better choice.

Important: Be careful when assuming two products or services instances or offering instances to be identical based on the SKU. Since SKUs are unique only for the same gr:BusinessEntity, this can be assumed only when you are sure that the two SKU values refer to the same business entity. Such can be done by taking into account the provenance of the data. As long as instances of gr:Offering are concerned, you can also check that the offerings are being offered by the same gr:Business Entity.

Usually, the properties gr:hasEAN_UCC-13 and gr:hasGTIN-14 are much more reliable identifiers, because they are globally unique.

See also http://en.wikipedia.org/wiki/Stock_Keeping_Unit.

**Domain**: [Offering](../classes/Offering.md) or [ProductOrService](../classes/ProductOrService.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer) or [schema1:Product](https://w3id.org/citydata/imported/schema1/Product)

**Range**: [xsd:string](https://w3id.org/citydata/imported/xsd/string)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [ProductOrService](../classes/ProductOrService.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasStockKeepingUnit`
