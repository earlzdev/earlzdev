<div id="header" align="center">
</div>

```Kotlin 
class EarlDev: Developer {

    init {
        val name = "Ilya"
        val age = "24 years"
        val education = "Ufa State Petroleum Technical University"
    }
    
    override val specification = "Android development"
    
    override val languages = listOf("Kotlin", "Java", "C++")
        
    val about = Links {
        telegram = "t.me/earldev"
        leetcode = "https://leetcode.com/Earldev/"
    }
}
```
