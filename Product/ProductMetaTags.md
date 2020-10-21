
# [Product](Product.md)

## ProductMetaTags

### Мета теги и данные для поисковиков и соцсетей

<pre>
id: bigint          // Id
type: MetaType      // Тип заголовка меты
name: string        // Заголовок тега (title / description / og:title)
value: text         // Содержимое тега
</pre>

## MetaType

### Тип мета тега

Либо в типе выбирать тип мета тега: 
```
- name
- property
```

либо сразу комбинации 
```
- name|title
- name|description
- property|og:title
- property|og:locale
- property|og:description
```

Объект:

<pre>
id: bigint        // Id
name: string      // Тип меты (name / property)
</pre>

Как лучше надо подумать, лишние объекты и для имен и для типов как то лишним кажется езе городить.

