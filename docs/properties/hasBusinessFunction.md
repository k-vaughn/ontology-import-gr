# hasBusinessFunction

This specifies the business function of the gr:Offering, i.e. whether the gr:BusinessEntity is offering to sell, to lease, or to repair the particular type of product. In the case of bundles, it is also possible to attach individual business functions to each gr:TypeAndQuantityNode. The business function of the main gr:Offering determines the business function for all included objects or services, unless a business function attached to a gr:TypeAndQuantityNode overrides it.
	
Note: While it is possible that an entity is offering multiple types of business functions for the same set of objects (e.g. rental and sales), this should usually not be stated by attaching multiple business functions to the same gr:Offering, since the gr:UnitPriceSpecification for the varying business functions will typically be very different.

**Domain**: [Offering](../classes/Offering.md) or [TypeAndQuantityNode](../classes/TypeAndQuantityNode.md) or [schema1:Offer](https://w3id.org/citydata/imported/schema1/Offer)

**Range**: [BusinessFunction](../classes/BusinessFunction.md)

## Used in classes

| Class |
|-------|
| [Offering](../classes/Offering.md) |
| [TypeAndQuantityNode](../classes/TypeAndQuantityNode.md) |

**IRI**: `http://purl.org/goodrelations/v1/hasBusinessFunction`
