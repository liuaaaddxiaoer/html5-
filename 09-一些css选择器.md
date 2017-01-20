# CSS选择器

1. div 标签选择器
2. id 选择器
3. class选择器
4. 后代选择器
5. div.xiaoer 交集选择器
6. div,xiaoer 并集选择器
7. div&gt;p 直接后代选择器\(儿子\)

```
<style>
        div>p{
            background-color: blue;
        }
    </style>
</head>
<body>
   <div>
       <p>haha</p>
   </div>

    <div>
        <ul>
            <li>
                <p>haha</p>
            </li>
        </ul>
    </div>
```

8.\*通配符选

9：

序选择器 :可以选择第一个 最后一个等  

```
div li:nth-child(2)  选择第二个
div li:nth-child(2n+2) 选择所有的偶数
```

```
<style>
        div li:last-child {
            background-color: blue;
        }
    </style>
</head>
<body>
    <div>
        <ul>
            <li>haha</li>
            <li>hahad</li>
            <li>hahadsad</li>
            <li>hahadd</li>
            <li>hahaddd</li>
        </ul>
    </div>
```

可以用safari的 用户代理模式模拟



10.下一个兄弟选择器

div+p    只有第一行变了

```
    <style>
        div+p{
            background-color: blue;
        }
    </style>
</head>
<body>
    <div></div>
    <p>haha</p>
    <p>haha2</p>
    <p>haha3</p>
    <p>haha</p>
```



