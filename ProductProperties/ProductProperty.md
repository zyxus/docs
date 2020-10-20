# ProductProperty
## Свойство товара
Является структурной единицей [Product](../Product.md)
<pre>
id: bigint                       // идентификатор, примари    
value: ProductPropertyValue[]    // Значение свойства  
unit: Unit                       // Размерность
sort: int                        // Значение сортировки  
enabled: int                     // Видимость - включен/выключен
</pre>
## Cм. также
[Product](../Product.md) - Товар.  
[ProductPropertyValue](ProductPropertyValue.md) - Значение свойства.   
[Unit](Unit.md) - Размерность. 