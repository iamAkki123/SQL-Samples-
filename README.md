##Identify entities and relationships##

Product ↔ Category: many-to-many.
Product → ProductVariant: one-to-many.
Variant → Inventory: one-to-one or one-to-many (multi-warehouse).
Customer → Order: one-to-many.
Order → OrderItem: one-to-many (each references a product_variant).
