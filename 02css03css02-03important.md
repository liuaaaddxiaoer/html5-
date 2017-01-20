# important

```
 <style>
        .haha {
            color: red !important;
        }
        #xixi{
            color: yellow;
        }
    </style>
</head>
<body>
    <div>
        <p class="haha" id="xixi">dd</p>
        <p >dd2</p>
        <p>dd3</p>
```

### 可以通过！important来提升属性的权重

![](/assets/important.png)



### 但是无法提升继承的权重:

```
<style>
        .xixiss {
            color: red ;
        }
        #xixi{
            color: yellow !important;
        }
    </style>
</head>
<body>
    <div>
        <p class="haha" id="xixi">dd
            <p class="xixiss" >dsdd</p>
        </p>
        <p >dd2</p>
        <p>dd3</p>
    </div>
```



