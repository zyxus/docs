
# [Product](Product.md)

## ProductDimensions

### Габаритно весовые параметры продукта

Продукту могут быть присвоены параметры веса и объема.  
Для каждого размера продукта существует свой вес и объем.

<pre>
productId: bigint           // Id продукта
productSize: <a href="ProductSizes.md">ProductSizes</a>   // Id размера продукта
weight: decimal             // Вес
volume: decimal             // Объем
</pre>

