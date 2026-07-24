# isVariantOf

This states that a particular gr:ProductOrServiceModel is a variant of another product or service model. It is pretty safe to infer that the variant inherits all gr:quantitativeProductOrServiceProperty, gr:qualitativeProductOrServiceProperty, and gr:datatypeProductOrServiceProperty values that are defined for the first gr:ProductOrServiceModel.

Example:
foo:Red_Ford_T_Model gr:isVariantOf foo:Ford_T_Model

**Domain**: [ProductOrServiceModel](../classes/ProductOrServiceModel.md)

**Range**: [ProductOrServiceModel](../classes/ProductOrServiceModel.md)

## Used in classes

| Class |
|-------|
| [ProductOrServiceModel](../classes/ProductOrServiceModel.md) |

**IRI**: `http://purl.org/goodrelations/v1/isVariantOf`
