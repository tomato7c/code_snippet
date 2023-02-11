**SimpleDateFormat 日期操作**
```scala
import java.text.SimpleDateFormat
import java.util.Date
val sdf = new SimpleDateFormat("YYYY/MM/DD HH:mm:ss:SSS")
println(sdf.format(new Date(1669649780638L)))
```