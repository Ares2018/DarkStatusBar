# DarkStatusBar
> 更改状态栏内文字和图标亮暗状态

#### 添加依赖

1、主工程build.gradle添加仓库地址
``` gradle
allprojects {
    repositories {
        google()
        jcenter()
        maven { url "http://10.100.62.98:8086/nexus/content/groups/public" }
    }
}
```

2、项目工程build.gradle添加依赖 (点击查看[最新版本](http://10.100.62.98:8086/nexus/#nexus-search;gav~com.core~DarkStatusBar~~~))
``` gradle
compile 'com.core:DarkStatusBar:0.0.1'
```

#### 使用方法

变暗
``` java
DarkStatusBar.get().fitDark(Context)
```

变亮
``` java
DarkStatusBar.get().fitLight(Context)
```
