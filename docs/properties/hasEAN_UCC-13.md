# hasEAN_UCC-13

The EAN·UCC-13 code of the given gr:ProductOrService or gr:Offering. This code is now officially called GTIN-13 (Global Trade Identifier Number) or EAN·UCC-13. Former 12-digit UPC codes can be converted into EAN·UCC-13 code by simply adding a preceeding zero.

Note 1: When using this property for searching by 12-digit UPC codes, you must add a preceeding zero digit.
Note 2: As of January 1, 2007, the former ISBN numbers for books etc. have been integrated into the EAN·UCC-13 code. For each old ISBN-10 code, there exists a proper translation into EAN·UCC-13 by adding "978" or "979" as prefix. Since the old ISBN-10 is now deprecated, GoodRelations does not provide a property for ISBNs.

**Domain**: [Offering](../classes/Offering.md) or [ProductOrService](../classes/ProductOrService.md) or [schema1:Product](https://w3id.org/citydata/imported/schema1/Product)

**Range**: [xsd:string](https://w3id.org/citydata/imported/xsd/string)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [ProductOrService](../classes/ProductOrService.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasEAN_UCC-13`
