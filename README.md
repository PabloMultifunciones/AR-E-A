# AR-E-A
Aprendizaje Reforzado - Entropia - Adicional

### Definicion
La entropia es el nivel de aleatoriedad que tienen el resultado de un experimento. Por ejemplo, al lanzar una moneda hay un 50% de probabilidades de que sea cara y un %50 de probabilidades de que sea cruz. 

![zzzzzzz](https://user-images.githubusercontent.com/95035101/208321260-80bf26ba-99cd-4a8c-a58b-31ec789ce96c.png)

Por lo tanto, se podria decir que en este caso la aleatoriedad es muy alto porque ninguna de las posibles situaciones tiene mas probabilidad de suceder que la otra.  

Suponga ahora que tenemos tres estudiantes que hicieron una prueba, y cada uno tiene cierta probabilidad de aprobar:
* El estudiante A tiene un 90% de probabilidades de aprobar.
* El estudiante B tiene un 70% de probabilidades de aprobar.
* El estudiante C tiene un 50% de probabilidades de aprobar.

![ccccc](https://user-images.githubusercontent.com/95035101/208321840-190d36cf-6395-4bb5-bcdc-d4e6da41a271.png)

![xxadasdas](https://user-images.githubusercontent.com/95035101/208321912-becb9d6c-53fd-4939-8939-e66944aa9980.png)  

Para el estudiante A se puede pensar esto como un experimento de 10 resultados donde 9 son F y 1 es P  

Estudiante A -> FFFFFFFFFP

Resultados de A = [ F, F, F, F, F, F, F, F, F, P]

El mismo enfoque se puede hacer para el estudiante B y C

![xxadasdasas](https://user-images.githubusercontent.com/95035101/208321917-8bf129c8-e762-40c5-b8f4-cb73be6051e3.png)  

Ahora imagine que tiene mas de dos posibles resultados. En ese caso se podria producir un numero muy pequeño. Para evitar esto se trabaja con logaritmos:  
log(ab) = log(a) + log(b)

![fff111](https://user-images.githubusercontent.com/95035101/208322646-d5715bee-fbad-4968-a1db-7e6627d237e7.png)

La media del resultado del logaritmo del producto de todas las probabilidades de los estudiantes:  
![22222](https://user-images.githubusercontent.com/95035101/208322686-52976bf7-b1e3-4d8c-bd60-d84468bea344.png)  

La entropia es lo negativo de la media

![zzfaafafa](https://user-images.githubusercontent.com/95035101/208322820-da5d9347-8430-4fd9-a113-4ba097390998.png)

La entripoa para el estudiante C es la mas alta, lo que significa que es el que enfrenta mayor incertidumbre.

