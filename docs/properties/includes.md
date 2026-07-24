# includes

This object property is a shortcut for the original gr:includesObject property for the common case of having exactly one single gr:ProductOrService instance included in an Offering. 

When linking to an instance of gr:SomeItems or gr:Individual, it is equivalent to using a gr:TypeAndQuantityNode with gr:hasUnitOfMeasurement="C62"^^xsd:string and gr:amountOfThisGood="1.0"^^xsd:float for that good.

When linking to a gr:ProductOrServiceModel, it is equivalent to 
1. defining an blank node for a gr:SomeItems
2. linking that blank node via gr:hasMakeAndModel to the gr:ProductOrServiceModel, and
3. linking from the gr:Offering to that blank node using another blank node of type gr:TypeAndQuantityNode with gr:hasUnitOfMeasurement="C62"^^xsd:string and gr:amountOfThisGood="1.0"^^xsd:float for that good.

**Domain**: [Offering](../classes/Offering.md)

**Range**: [ProductOrService](../classes/ProductOrService.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |

**IRI**: `http://purl.org/goodrelations/v1/includes`
