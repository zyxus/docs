
# [Product](Product.md)

## ProductDetails

### Детали продукта

Детали представляют из себя фотографии конкретных областей товара, например молний на рукавах или вставок из прочной ткани на коленях брюк, с небольшим описанием.

<pre>
id: bigint          // Id детали
product_id: bigint  // Id продукта
image: Image        // Изображение
enabled: boolean    // Видимость -включен/выключен
sort: int           // Сортировка
</pre>

### ProductDetailsLanguages

<pre>
detail_id: bigint       // Id детали
lang: Language          // Язык
name: String            // Изображение
description: text       // Видимость -включен/выключен
</pre>
