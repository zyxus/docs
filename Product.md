
# Product

## Продукт

<pre>
id: int                         // Id продукта	
sku: string                     // Артикул
slug: string                    // Служебное имя (1)
name: string                    // Имя
description: string             // Описание
price: ProductPrice             // Цена
stock: ProductStock             // Распродажа
state: ProductState             // Состояние
meta: ProductMeta               // Мета данные для поисковиков и соцсетей
details: ProductDetail          // Детали продукции
properties: ProductProperty     // Свойства товаров
sizes: ProductSize              // Размеры
dimensions: ProductDimension    // Габариты 
reviews: ProductReview          // Отзывы
relatedProducts: RelatedProduct // Связанные товары 
</pre>

(1) - Если нужно, т.к. мы говорили что путь продукта будет по артикулу автоматом как и сейчас

- [ProductDimension](ProductDimension.md) - Габариты 
- [ProductDetail](ProductDetail.md) - Детали продукции
- [ProductMeta](ProductMeta.md) - Мета данные для поисковиков и соцсетей
- [ProductProperty](ProductProperties/ProductProperty.md) - Свойства товаров
- [ProductReview](ProductReview.md) - Отзывы
- [ProductSize](ProductSize.md) - Размеры
- [ProductState](ProductState.md) - Состояние продукта 
- [RelatedProduct](RelatedProduct.md) - Связанные товары 
