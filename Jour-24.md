# Objectifs journaliers

## Mercredi 11/09/2019


* [ ] Javascript :
  * [ ] Approfondir les `strings` en Javascript (https://javascript.info/string)
  * [ ] Comprendre le fonctionnement des tableaux en Javascript (https://javascript.info/array)
  * [ ] Approfondir les tableaux en Javascript en faisant le tour des méthodes disponibles (https://javascript.info/array-methods)



* Codewars :
  * [x] String repeat (https://www.codewars.com/kata/string-repeat/javascript)
  ( refaire, sans while avec la fonction ES6 ... )
  
  * [x] Remove First and Last Character (https://www.codewars.com/kata/56bc28ad5bdaeb48760009b0)
  ( SLICE <3 )

  * [x] Convert a Number to a String! (https://www.codewars.com/kata/5265326f5fda8eb1160004c8)
  * [x] Convert a String to a Number! (https://www.codewars.com/kata/544675c6f971f7399a000e79)
  * [ ] Sum of positive (https://www.codewars.com/kata/sum-of-positive/javascript)
  * [ ] Find the smallest integer in the array (https://www.codewars.com/kata/55a2d7ebe362935a210000b2)



**LIFO = Last In  - First Out**
**FIFO = First In - First Out**

`Slice` = Trancher 
`Splice` = Supprimer un Index + Rajouter a un index !

********* mémoire ***********
function positiveSum(arr) {
`déclare une function ce nomman : positiveSum, avec comme argument "arr"`
 let sum = 0;
 `déclaration d'une variable avec comme valeur "0"`
 for(let i = 0; i < arr.length; i++) {
     `déclanchement d'une boucle *Pour* pour begin = "0", condition plus petit que la longeur du nombre de argument rentrer (incrémentation de "I" après la boucle`
   if(arr[i] > 0) {
       `déclanchement d'une condition *SI* la variable *I* qui représente mes Index mémoire, sont plus grand que "0", on peut ajouter calculer l'addition`
    sum += arr[i];  -->  sums = sums + arr[i](ca va chercher la valeur dans l'index rajouter)
  }
 }
return sum;
`retourne la variable qui contient le résultat`
}

*********** tttttttttt ***********