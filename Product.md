
# Product

## Продукт

<pre>
id: int                         // Id продукта	
sku: string                     // Артикул
slug: string                    // Служебное имя (1)
name: string                    // Имя
description: string             // Описание
price: ProductPrice             // Цена
state: <a href="ProductState.md">ProductState</a>             // Состояние
meta: <a href="ProductMeta.md">ProductMeta</a>               // Мета данные для поисковиков и соцсетей
details: <a href="ProductDetail.md">ProductDetail</a>          // Детали продукции
media: ProductMedia             // Медиа библиотека продукта (2)
properties: <a href="ProductProperties/ProductProperty.md">ProductProperty</a>     // Свойства товаров
sizes: <a href="ProductSize.md">ProductSize</a>              // Размеры
dimensions: <a href="ProductDimension.md">ProductDimension</a>    // Габариты 
reviews: <a href="ProductReview.md">ProductReview</a>          // Отзывы
relatedProducts: <a href="RelatedProduct.md">RelatedProduct</a> // Связанные товары 
</pre>

- [ProductDimension](ProductDimension.md) - Габариты 
- [ProductDetail](ProductDetail.md) - Детали продукции
- ProductMedia - Медиа файлы привязанные к товару
- [ProductMeta](ProductMeta.md) - Мета данные для поисковиков и соцсетей
- [ProductProperty](ProductProperties/ProductProperty.md) - Свойства товаров
- [ProductReview](ProductReview.md) - Отзывы
- [ProductSize](ProductSize.md) - Размеры
- [ProductState](ProductState.md) - Состояние продукта 
- [RelatedProduct](RelatedProduct.md) - Связанные товары 

> (1) Если нужно, т.к. мы говорили, что путь продукта будет по артикулу автоматом как и сейчас  
> (2) Медиа целиком или только картинки