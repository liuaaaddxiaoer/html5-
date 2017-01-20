# Class选择器

重复共有 原子类

```

    <style>
        .xiaoer{
            color: red;
        }
    </style>
</head>
<body>
    <p class="xiaoer xiaoer2">haha</p>
    <p class="xiaoer">haha2</p>
    <p>haha3</p>
    <p>haha4</p>
    <p>haha5</p>
</body>
```



注意多个类的话用空格隔开不是写2个

```
错误： <p class="xiaoer" class="xiaoer2">haha2</p>
```

---

尽量不要在一个class种写完标签的所有属性而是应该让标签携带更多的class来完成

尽量使用class不要使用id 因为id是js要用的

