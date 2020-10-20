# ProductProperty
## Свойство товара
Является структурной единицей [ProductPropertyBlock](ProductPropertyBlock.md)
<pre>
id: bigint                       // идентификатор, примари    
value: ProductPropertyValue[]    // Значение свойства  
unit: Unit                       // Размерность
sort: int                        // Значение сортировки  
enabled: int                     // Видимость - включен/выключен
</pre>
## Cм. также
[ProductPropertyBlock](ProductPropertyBlock.md) - Блок свойств товаров.   
[ProductPropertyValue](ProductPropertyValue.md) - Значение свойства.   
[Unit](Unit.md) - Размерность. 