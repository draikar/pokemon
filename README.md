# pokemon
Pokemon Exercise


This Is a Pokemon Exercise.

It is as per this below description-

Description
You work in a toy store that is selling Pokemon. Customers who buy more than one type of Pokemon get a
discount. The same type of Pokemon cannot be added to a discount group.
Number of Different Pokemon Purchased ===== Discount Amount
                                   1 ======     No discount
                                   2 =======    10%
                                   3========     20%



        Pokemon for Sale Price
Pikachu $6
Squirtle $5
Charmander $5



Requirements

The completed program should be able to calculate the best possible discount for any collection of Pokemon.
You may use multiple transactions to get the best price.


Each example should be translated into a Unit Test. No UI component is required, each test scenario may be
hard coded. Additional Unit Tests are encouraged.


Competitive advantage


We will be looking to interview those individuals whose completed exercise most closely adheres to the
principles listed in the book “Clean Code”. If you are unfamiliar with this book, do not worry. Just try to write
your code in a manner which leaves you feeling proud of the end product.



Example One
Purchased 1 Pikachu
Should yield $6.00


Example Two
Purchased 2 Pikachu
Should yield $12.00


Example Three
Purchased 1 Pikachu
Purchased 1 Squirtle
Should yield $9.90



Example Four *note that each group of two Pokemon receives a 10% discount.
Purchased 2 Pikachu
Purchased 2 Squirtle
Should yield $19.80 *2x Example 3 => $9.90 + $9.90 = $19.80


Example Five *note that each group of two Pokemon receives a 10% discount.
Purchased 3 Pikachu
Purchased 3 Squirtle
Should yield $29.70 *3x Example 3 => $9.90 + $9.90 + $9.90 = $29.70


Example Six *note that the 10% discount does not apply to the second Pikachu.
Purchased 2 Pikachu
Purchased Squirtle
Should yield $15.90


Example Seven
Purchased 1 Pikachu
Purchased 1 Squirtle
Purchased 1 Charmander
Should yield $12.80


Example Eight *note that the 20% discount applies to the three grouped Pokemon, but not the additional
ungrouped Pikachu.
Purchased 2 Pikachu
Purchased 1 Squirtle
Purchased 1 Charmander
Should yield $18.80
