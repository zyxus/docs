
# [Product](Product.md)

## RelatedProduct

### Связанные продукты

У каждого продукта есть набор связанных с ним продуктов двух и болеетипов - рекомендуемые и похожие.  

<pre>
productId: bigint            // Id продукта
type: RelationType           // Тип связи с другим продуктом
product: relatedProduct      // Связанный продукт
</pre>

## RelationType

Типы связей продуктов - рекомендуемые, похожие и т.д.

<pre>
id: bigint           // Id связи
name: string         // Название связи
</pre>