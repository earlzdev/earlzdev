<div id="header" align="center">
</div>

```Kotlin 
class EarlDev : Developer {

    init {
        val name = "Ilya"
        val age = "23 years"
        val education = "Ufa State Petroleum Technical University"
    }
    
    override val specification = "Android development"
    
    override val languages = listOf("Kotlin", "Java")
    
    val fondOf = CurrentlyLearning {
        val platform = "Kotlin Multiplatform, IOS development"
        val languages = "Swift"
    }
    
    val communication = Links {
        val telegram = "@earldev"
    }
}
```
