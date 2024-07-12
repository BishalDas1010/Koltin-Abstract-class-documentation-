# Koltin-Abstract-class-documentation-
Koltin Abstract class documentation  || questions with answers

Q1) 
//Animal Sounds:
//Create an abstract class Animal with an abstract method makeSound().
//Create subclasses Dog and Cat that extend Animal and implement the makeSound() method to print “Bark” and “Meow” respectively.
 ANS   
 abstract class Animal(){
       //Abstract  Fun does not have any body
       abstract fun makeSound()
}
class cat : Animal(){
       override fun makeSound() {
              println("The sound of cat is Meaw")
       }

}
class dog : Animal(){
       override fun makeSound() {
              println("The dog is bhw")
       }
}
fun main(){
       val Dog = dog()
       val cat = cat()

       Dog.makeSound()
       cat.makeSound()
}


