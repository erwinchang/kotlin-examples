
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

### if else, while

```
    val x = 3
    val y = 5

    if ( x > y ) {
        println("x greater than y")
    }
    else if ( x < y) {
        println("x less than y")
    }
    else
        println("x equals y")

```

```
    var index = 0
    while ( index < 5 ) {
        println(index)
        index++
    }
```

執行結果

```
> Task :run
x less than y
----------------
0
1
2
3
4
```

### Array

```
    val ia: IntArray = intArrayOf(3, 5, 7)
    var total: Int = 0
    for ( n in ia ) {
        total += n
    }
```

```
    val ib: IntArray = intArrayOf(120, 30, 15, 27, 66)
    ib.filter { it > 50 }
        .sortedBy { it }
        .map { it / 10 }
        .forEach { print("$it-")}
```

執行結果

```
Total: 15
----------------
6-12-
```



[1]:http://www.codedata.com.tw/kotlin/kt02/
