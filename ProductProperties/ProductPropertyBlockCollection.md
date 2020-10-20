# ProductPropertyBlockCollection
## Свойство товара
Является структурной единицей [Product](../Product.md)
Абстрактная группа для компоновки **блоков свойств**, используется для получения древовидной иерархии от товара 
к **свойству товара**. В состав коллекции свойств входят пользовательские блоки свойств, а также системные 
блоки **::before** и **::after**. Взаимоотношение с товаром устанавливается на основе **свойства тип**.
<pre>
id: bigint                                    // идентификатор, примари
productType: ProductPropertyValue             // Значение типа товара
name: String                                  // Значение свойства  
propertiesBlock: ProductPropertyBlock[]       // Блок свойств товаров
</pre>
## Cм. также
[Product](../Product.md) - Товар.  
[ProductPropertyBlock](ProductPropertyBlock.md) - Блок свойств товаров.  
[ProductPropertyValue](ProductPropertyValue.md) - Значение свойства.  