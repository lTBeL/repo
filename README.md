### 添加存储库
- 项目根目录build.gradle添加存储库
```groovy
allprojects {
    repositories {
        ...
        maven {
            url "https://raw.githubusercontent.com/lTBeL/repo/master/repository"
        }
    }
}
```
- [okhttp http-日志](https://github.com/lTBeL/okhttp-logging)

- [字符集检测](https://github.com/lTBeL/okhttp-logging)

- [retrofit数据格式化](https://github.com/lTBeL/okhttp-logging)

- [android运行时请求权限](https://github.com/lTBeL/RTPermission)

- [rxjava取消订阅封装](https://github.com/lTBeL/rxjavautils)

- [RxJava协程调度器](https://github.com/lTBeL/rxjavautils)

- [retrofit接口请求参数封装，通用参数及对象转表单参数](https://github.com/lTBeL/retrofit-obj)

### 第三方的依赖包
#### 字符集检测使用的第三方库（原地址使用gradle始终加载不成功）
```groovy
implementation 'com.sjianjun.ext:chardet:0.0.1'
```

### 以下的库在jcenter仓库
```groovy
//日志工具，打印行号，写入磁盘
implementation 'com.sjianjun:aLog:1.2.2'

//将对象转换为表单或者get请求参数
implementation 'com.sjianjun:retrofitlib:0.0.1'

implementation 'com.sjianjun:serialize:1.0.1'
```
### 第三方库
- [Android 权限请求(https://github.com/yanzhenjie/AndPermission)](https://github.com/yanzhenjie/AndPermission)

- [Flexbox for Android](https://github.com/google/flexbox-layout)
