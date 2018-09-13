# Assignment-3.md

Part 1:
Math is easy so homework is done and it's sunny so camping is fun

(S ^ H) -> M v C
___________________________________________________________________
Part 2:
```
(¬B → ¬A) → ((¬B → A) → B)
```
((A → B)∧(B → ¬A)) → A

| A | B | ¬A | ¬B | ¬B -> ¬A | ¬B -> A  | ((¬B -> A) -> B )| (¬B → ¬A) → ((¬B → A) → B) | ((A → B)∧(B → ¬A)) → A
|---|---|--- |--- | -------- | -------  | ---------------  | -------------------------- | ----------------------
| T | T | F  | F  | T        |    T     |        T         |             T              |            T
| T | F | F  | T  | F        |    T     |        F         |             T              |            T
| F | T | T  | F  | T        |    T     |        T         |             T              |            F
| F | F | T  | T  | T        |    F     |        T         |             T              |            F

-Tautology
-Neither
_________________________________________________________________________________________________________________
Part 3:

 (p ∧ q) → r , p → (q → r)
 implication x 3
            
 (p ∧ q)' v r , p' v (q' v r)
 associative

 (p ∧ q)' v r , (p' v q') v r
 De Morg

 (p ∧ q)' v r , (p ∧ q)' v r  DONE
----------

 (q ∨ r) → p, (q → p)∧(r → p)
 implication x 3

 (q ∨ r)' v p, (q' v p)∧(r' v p)
 distribution

 (q ∨ r)' v p, p v (q' ^ r')
 De Morg

 (q ∨ r)' v p, p v (q v r)'  DONE

_____________________________________________________________
Part 4:

Let Loves(x,y) mean “x loves y,” Traveler(x) mean “x is a traveler,”
City(x) mean “x is a city,” Lives(x,y) mean “x lives in y.”

∃x∀y∀z(City(x) ∧ Traveler (y) ∧ Lives(z,x)) → (Loves(y,x) ∧ ¬Loves(z,x))

 -There are some cities that all travelers love and all the people who live there don't love it.

--------
“No traveler loves the city they live in.”

 -∀x∀y(City(x) ∧ Traveler(y) ∧ Lives(y,x)) ->  ¬Loves(y,x)

________________________________________________________________________________________________________
Extra Credit:

 Assuming: p → (q ∧ r ), s → r , r → p
Prove: s → q.


------------
 Assuming: ¬(r ∨ s), ¬p → s, p → q. 
Prove: q






