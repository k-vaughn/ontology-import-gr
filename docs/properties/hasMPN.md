# hasMPN

The Manufacturer Part Number or MPN is a unique identifier for a product, service, or bundle from the perspective of a particular manufacturer. MPNs can be assigned to products or product datasheets, or bundles. Accordingly, the domain of this property is the union of gr:ProductOrService (the common superclass of goods and datasheets), and gr:Offering.

Important: Be careful when assuming two products or services instances or offering instances to be identical based on the MPN. Since MPNs are unique only for the same gr:BusinessEntity, this holds only when the two MPN values refer to the same gr:BusinessEntity. Such can be done by taking into account the provenance of the data. 

Usually, the properties gr:hasEAN_UCC-13 and gr:hasGTIN-14 are much more reliable identifiers, because they are globally unique.

See also http://en.wikipedia.org/wiki/Part_number

**Domain**: [Offering](../classes/Offering.md) or [ProductOrService](../classes/ProductOrService.md) or [schema1:Product](https://w3id.org/citydata/imported/schema1/Product)

**Range**: [xsd:string](https://w3id.org/citydata/imported/xsd/string)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [ProductOrService](../classes/ProductOrService.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasMPN`
