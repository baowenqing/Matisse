> 首先感谢知乎提供的图片库  但是不要kpi工程啊!!!  总要定期维护一下吧  不然也太...
 

> 可以用这个依赖  临时修改了下 发布到了 jitpack   [包名 方法名都没有修改  只需要替换依赖即可]

`因代码里的三方权限库也没人维护了 我直接移除了相关请求读写的权限  大家在调用前动态申请！！！`

```groovy

dependencies {
    implementation 'com.github.baowenqing:Matisse:1.0.1'
}
```
 

