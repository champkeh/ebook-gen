# ebook-gen
电子书生成，支持 html 和 epub

## Usage
```js
import EBook from '@champkeh/ebook-gen'

const data = {
    // 章节数据
    chapters: [
        {
            title: '', // 章节标题
            html: '', // html内容
            style: '', // style内容
        },
    ],
    // 书籍的元数据
    bookDetail: {
        title: '',
        author: '',
        isbn: '',
        cover: '',
    },
    // 目录数据
    toc: [],
}

EBook.generate(data, {
    format: 'epub',
})
```
