# Kotlin Basic Repository

Extension Function example: 

    class Box(var length: Int, var width: Int, var height: Int){

        fun getVolume() = length*width*height

    }
    
    //Extension function
    fun Box.expand(fold: Int) = Box(length*fold, width*fold, height*fold)
    
    val smallBox = Box(3,2,5)
    val biggerBox = smallBox.expand(2)
    println(smallBox.getVolume())
    println(biggerBox.getVolume())
    
    
 [Scope function](https://www.youtube.com/watch?v=Vy-dS2SVoHk)
 
 
    
    


</br></br>
## About author
<p align="center">This Repository is developed and maintained by </p>
<p align="center">
  <a href="https://stackoverflow.com/users/4700156/rohit-singh?tab=profile"><img width="100" height="100" src="https://user-images.githubusercontent.com/11274840/30627155-38952a30-9dec-11e7-9072-a00d9a86bdb8.gif">
</p></a>
<a href="https://stackoverflow.com/users/4700156/rohit-singh?tab=profile">
<p align="center">
  Rohit Singh
</p>
</a>
