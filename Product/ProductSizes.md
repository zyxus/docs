
# [Product](Product.md)

## ProductSizes

### Размеры продукта

У каждого продукта есть размер.  
Размеры для одежды состоят из собственно самого размера и роста, например:  

 - 88-92 / 158-164
 - 88-92 / 170-176  

Для остальной продукции размер состоит только из размера - обувь, перчатки и т.д.
Размер может быть числовым, например для обуви - 40, или буквенным для другой продукции - X, XL и т.д. 

<pre>
id: bigint             // Id размера
productId: bigint      // Id продукта
sizeFrom: string       // Размер ОТ
sizeTo: string         // Размер ДО
heightFrom: string     // Рост ОТ
heightTo: string       // Рост ДО
</pre>

