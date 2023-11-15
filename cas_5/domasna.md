## Домашна 5

### Задача 1.

Да се дефинира функција printFunc koja што ќе прима еден параметар seconds. Оваа функција треба да печати "Coding is not that hard!" во конзола после специфицираните секунди. Доколку ја повикаме функцијата со аргумент кој што не е број, функцијата треба да испечати "Please enter number". Исто така потребно е да го лимитираме бројот на секунди да биде едноцифрен број. Доколку аргументот не е едноцифрен број, треба да се испечати: "Please enter one digit number"
Пр. Ако аргументот е бројот 3, "Coding is not that hard!" ќе се испринта во конзола после 3 секунди.

### Задача 2.

Напишете 5 функции кои враќаат Promise

а. да се повикаат истите со .then() и .catch()

б. да се повикаат истите со async await каде што ќе ги употребите и блоковите try и catch

### Задача 3.

Да се креира функција checkNumber која што ќе прима еден параметар number. Оваа функција треба да враќа Promise со тоа што доколку бројот е парен, треба да се направи resolve и да се испринта пораката “The number is even” a ако бројот е непарен, да се направи reject со пораката “The number is odd”.

- Да се дефинира функција handleSuccess koja што ќе има еден параметар message и ќе го принта во конзола

- Да се дефинира функција handleError која што ќе има еден параметар error и ќе го принта во конзола

Да се повика функцијата checkNumber со неколку различни аргументи и соодветно во .then() и .catch да се повикаат handleSuccess и handleError

### Задача 4.

Во продолжение е дадена функција која што симулира API повик:

```
function fetchData() {
  return new Promise((resolve) => {
    setTimeout(() => {
      resolve({
        name: "John Doe",
        age: 30,
        email: "john@example.com",
      })
    }, 2000)
  })
}
```

Ваша задача е да дефинирате асинхрона функција displayUserDetails која што ќе ги испечати податоците во конзола. Да се употребат try/catch блокови.

### Задача 5.

Во продолжение е дадена парцијално напишана функција со испуштени клучни зборови:

```
function calculateSquareRoot(number) {
    {
    (number < 0) {
    new Error("Cannot calculate square root of a negative number")
    }
    return Math.sqrt(number)
    } (error) {
    new Error("Error occurred during square root calculation")
    } {
    console.log("Square root calculation completed.")
    }
    }

    console.log(calculateSquareRoot(10))
```

Ваша задача е да ги употребите правилните клучни зборчиња на соодветното место за да може да се изврши самата функцијата.