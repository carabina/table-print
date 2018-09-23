# TableLog
A universal logging tool that prints in a nice table format to easily find it in the console – especially in big logs.

##  `KeyValueLogger` Example

```swift
let stuff = [
    "String" : "Hello World",
    "nil string" : nil,
    "date": Date()
]

Log(stuff)
```


The above code would produce this output:

```
+------------+---------------------------+
| Key        | Value                     |
+------------+---------------------------+
| nil string | <nil>                     |
| date       | 2018-06-15 12:22:43 +0000 |
| String     | Hello World               |
+------------+---------------------------+
```
