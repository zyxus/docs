
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
meta: <a href="ProductMetaTags.md">ProductMetaTags</a>               // Мета данные для поисковиков и соцсетей
details: <a href="ProductDetails.md">ProductDetails</a>          // Детали продукции
media: ProductMedia             // Медиа библиотека продукта (2)
properties: <a href="ProductProperties/ProductProperty.md">ProductProperty</a>     // Свойства товаров
sizes: <a href="ProductSizes.md">ProductSizes</a>              // Размеры
dimensions: <a href="ProductDimensions.md">ProductDimensions</a>    // Габариты 
reviews: <a href="ProductReviews.md">ProductReviews</a>          // Отзывы
relatedProducts: <a href="RelatedProducts.md">RelatedProducts</a> // Связанные товары 
</pre>

- [ProductDimensions](ProductDimensions.md) - Габариты 
- [ProductDetails](ProductDetails.md) - Детали продукции
- ProductMedia - Медиа файлы привязанные к товару
- [ProductMetaTags](ProductMetaTags.md) - Мета данные для поисковиков и соцсетей
- [ProductProperty](../ProductProperties/ProductProperty.md) - Свойства товаров
- [ProductReviews](ProductReviews.md) - Отзывы
- [ProductSizes](ProductSizes.md) - Размеры
- [ProductState](ProductState.md) - Состояние продукта 
- [RelatedProducts](RelatedProducts.md) - Связанные товары 

> (1) Если нужно, т.к. мы говорили, что путь продукта будет по артикулу автоматом как и сейчас - product/4-125.htm - тогда slug не нужен продукту 
> (2) Медиа целиком или только картинки