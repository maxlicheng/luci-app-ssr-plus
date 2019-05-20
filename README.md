# luci-app-ssr-plus

## 说明
   鉴于L大已删除相关源码，现将自用的ssr源码托管到github

   源码特色：

   1.免开门

   2.更新g-f-w列表，共5176条

   3.更新国内IP段，共8369条

## 使用方法一
```Brach
    cd package/
    mkdir openwrt-packages
    cd openwrt-packages
    git clone https://github.com/maxlicheng/luci-app-ssr-plus.git
```

## 使用方法二
```Brach
    cd package/lean/
    git clone https://github.com/maxlicheng/luci-app-ssr-plus.git
```

在源码根目录
```Brach
    vi .gitignore
```
在文件最后一行，加入
```Brach
    git rm --cached package/lean/luci-app-ssr-plus/ -r
```

## 注意
两种方法只能选其中一种，
这样ssr就不受git pull影响了。
