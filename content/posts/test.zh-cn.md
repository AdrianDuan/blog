---
date: 2020-09-03T17:40:15+08:00
title: 测试
description: 测试
isCJKLanguage: true
---

# 测试代码高亮

```ts
export class TextureLoader {
  public static use(
    resource: ILoaderResource,
    next: (...args: any[]) => void
  ): void {
    if (resource.data && resource.type === Resource.TYPE.IMAGE) {
      resource.texture = Texture.fromLoader(
        resource.data,
        resource.url,
        resource.name
      );
    }
    next();
  }
}
```

# 测试 Markdown 语法

# Header 1

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

- Red
- Green
- Blue

1.  Bird
1.  McHale
1.  Parish

- Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
  Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
  viverra nec, fringilla in, laoreet vitae, risus.
- Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
  Suspendisse id sem consectetuer libero luctus adipiscing.

- A list item with a blockquote:

  > This is a blockquote
  > inside a list item.
  
# 测试MWeb发布服务

