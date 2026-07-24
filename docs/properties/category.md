# category

The name of a category to which this gr:ProductOrService, gr:Offering, gr:BusinessEntity, or gr:Location belongs.
	
Note 1: For products, it is better to add an rdf:type statement referring to a GoodRelations-compliant ontology for vertical industries instead, but if you just have a short text label, gr:category is simpler.
Note 2: You can use greater signs or slashes to informally indicate a category hierarchy, e.g. "restaurants/asian_restaurants" or "cables > usb_cables"


**Domain**: [BusinessEntity](../classes/BusinessEntity.md) or [Location](../classes/Location.md) or [Offering](../classes/Offering.md) or [ProductOrService](../classes/ProductOrService.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer) or [schema1:Organization](https://w3id.org/citydata/imported/schema1/Organization) or [schema1:Place](https://w3id.org/citydata/imported/schema1/Place) or [schema1:Product](https://w3id.org/citydata/imported/schema1/Product)

**Range**: [rdfs:Literal](https://w3id.org/citydata/imported/rdfs/Literal)

## Used in classes

| Class |
|-------|
| [BusinessEntity](../classes/BusinessEntity.md) |
| [Location](../classes/Location.md) |
| [Offering](../classes/Offering.md) |
| [ProductOrService](../classes/ProductOrService.md) |

**IRI**: `http://purl.org/goodrelations/v1/category`
