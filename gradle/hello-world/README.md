
### hello-world

來源：[Kotlin Tutorial（2）10分鐘認識Kotlin][1]

### 字串

字串裡面需要替換內容方式如下：


```
"..$變數.."
```

```
"...${運算式}.."
```

example

```
val s = "X: $x, Y: $y, Z: $z"
println("summary: $x + y + z")
println("summary: ${x + y + z}"
```

./gradlew build
./gradlew run
```
> Task :run
X: 3, Y: 5, Z: 7
summary: 3 + y + z
summary: 15
```


[1]:http://www.codedata.com.tw/kotlin/kt02/
