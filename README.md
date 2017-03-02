# NFA-TO-DFA-
NFA TO DFA using JEE on server side and Javascript on client interface .
about Application :

1- JEE on server side and Javascript on client interface .
2- the application is  doing the NFA TO DFA without minimisation .
3- the application can process only NFA that have only 1 initial state .
4- the application can process  both NFA that have epsilon transitions and those that don't have it (normal NFA).

initial instructions :

1- unzip Deterministe.rar
2- import the project to the workspace of your IDE (eclipse jee kepler)
3- run the project using a tomcat server .
4- or you can open the application directly via "http://localhost:8080/Deterministe/index"

using instructions :

1- you will have only one state at the begining , it's the initial state .
2- if you decide that it will be the initial state , you must name it "0" , otherwise change it
3- you must add states and name them using numbers (recommanded)  .
3- you can use letter "e" only for naming EPSILON TRANSITIONS . all other letters are accepted for naming normal transitions .
4- once you finish building the NFA , you must fill in the input form in order to add final states BUT this must be using "," between final states (EXAMPLE : 4,5,6 )
5- you click on save in order not to lose the NFA you built .
6- and finaly you click on "envoyer" 
7- you will get  a DFA output and initial state "l'Etat d'entrée:" and final states "les Etats finaux " on the bottom.

