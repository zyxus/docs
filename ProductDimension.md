
## ProductDimension

### Габаритно весовые параметры продукта

Продукту могут быть присвоены параметры веса и объема.  
Для каждого размера продукта существует свой вес и объем.

<pre>
productId: bigint           // Id продукта
productSize: <a href="ProductSize.md">ProductSize</a>   // Id размера продукта
weight: decimal             // Вес
volume: decimal             // Объем
</pre>

