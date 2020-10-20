
# [Product](Product.md)

## RelatedProducts

### Связанные продукты

У каждого продукта есть набор связанных с ним продуктов двух и болеетипов - рекомендуемые и похожие.  

<pre>
productId: bigint                   // Id продукта
relationType: RelationTypes         // Тип связи с другим продуктом
relatedProduct: relatedProducts     // Связанный продукт
</pre>

## RelationTypes

Типы связей продуктов - рекомендуемые, похожие и т.д.

<pre>
id: bigint                   // Id связи
relationName: string         // Название связи
</pre>