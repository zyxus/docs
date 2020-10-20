# ProductPropertyBlock
## Свойство товара
Является структурной единицей [ProductPropertyBlockCollection](ProductPropertyBlockCollection.md)
Абстрактная группа для компоновки свойств товаров. Из блоков свойств составляют наборы свойств.
Существуют два системных блока **::before** и **::after**.
<pre>
id: bigint                          // идентификатор, примари    
name: String                        // Значение свойства  
properties: ProductProperty[]       // Размерность
sort: int                           // Значение сортировки  
enabled: int                        // Видимость - включен/выключен
</pre>
## Cм. также
[ProductPropertyBlockCollection](ProductPropertyBlockCollection.md) - Коллекция блоков свойст товаров.  
[ProductProperty](ProductProperty.md) - Свойство товара.  