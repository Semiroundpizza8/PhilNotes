# Something about logic
## 1/24/18
### A Valid Argument
The current vice president will win the next election.
If the current vice president wins the next election, then the country will prosper.
So, the country will prosper.

All fish fly.
Anything which flies, talks.
Therefore - all fish talk.

A valid argument can have a false premisis, leading to a false conclusion.
Validity isnt about truth or falsity, its about whether or not a specific conclusion can be reached

### An Invalid Argument
If God exists, then the creation is perfect.
God doesnt exist.
Therefore, creation is imperfect.

In ordinary english, the terms 'Valid'/'True' and 'Invalid'/'False' are often used interchangably. For logicians its used in a more restricted way, where 'v' and 'iv' are only for arguments, and 't' or 'f' are only for 

OR = and/or
EITHER = or

Any creature with a kidney has a heart. <- Premise
Not every creature has a kidney.        <- Premise
So, not every creature has a kidney.    <- Conclusion

Everybody loves someone.                <- Premise
So, someone is loved by everyone.       <- Conclusion

There is evil in the world.                   <- Premise
If there were a God, there would be no evil.  <- Premise
Therefore, there is no God.                   <- Conclusion

God exists.                                   <- Premise
God doesn't exist.                            <- Premise
So, Chicago is west of New York.              <- Conclusion

In the above, 36 and 37 contradict each other.
While 38 is unrelated.
If we cannot determine if the premises are true, we cannot conclude that the end is false.
It is impossible that the premises are true and the conclusion is false.
From a contridiction, anything can be true.

This teacher is confusin                              <- Premise
The content is probably on YouTube                    <- Premise
Therefore, I should be playing Hearthstone right now  <- Conclusion

### Conclusions
An argument whose premises are necessarily false is valid.
An argument whose conclusion is necessaruily true is valid.

A good argument is not simply deductively valid; The following argument is deductively valid but unlikely to persuade anyone:
All fish fly.
Anything which flies, talks.
Therefore - all fish talk.
Though it is not possible for both to be true and false, the argument is unlikely to persuade anyone because 55 and 57 are false.

Normally, good arguments are not only deductively valid, but also have true premises.... making them sound.
**A sound argument is a valid argument whose premises are all true**
* If an argument is unsound, then it's invalid. -- *FALSE*
* If an argument is valid, then it's premises are true. -- *FALSE*
* If an argument is valid, then its conclusion is true. -- *FALSE*
* If the premises of a given argument are true, and the conclusion is also true, then the argument is valid. -- *FALSE*

### If... Then
* If abortion is murder, then abortion is morally wrong.    <- If p then q
* Abortion is murder.                                       <- p
* So, Abortion is morally wrong.                            <- So, q
Valid form of argument

* If the world was created by God, then it will exhibit order and lawfullness.  <- If p, then q
* The world does exhibit order and lawfullness                                  <- q
* So, the world was created by God.                                             <- So, p
Invalid form of argument

#### Not with If...Then
* If mental states are brain states, then they are located in space   <- If p then q
* But mental states are not located in space.                         <- Not q
* So, mental states are not brain states                              <- So, not P
Valid

* If God were at all evil, then the world could be better than it is. <- If p then q
* But God is not at all evil.                                         <- Not p
* So, the world could not be better than it is.                       <- So, not q
Invalid

#### Both... and with not
* Space cannot be both finite and unbounded.  <- Not both p and q
* Space is unbounded.                         <- p
* So, space is not finite.                    <- So, not q
Valid argument, Valid form.

* Mercy killing cannot be both morally obligatory and morally wrong.  <- Not both p and q
* It is surely not morally obligatory.                                <- Not p
* So, mercy killing must be morally wrong.                            <- So, q
Invalid, example of counter example. Premises are true, conclusion is false.

Sound arguments are all valid.
But not all valid arguments are sound.

# 11/31/18

## Logical Connectives
* If its impossible, the argument is invalid, If its possible, the argument is valid
* A complex sentence is a sentence whos parts themselves are sentences. 

### Simple or Atomic Sentences
### Connectives
Logical connectives serve to contruct compound sentences from simpler ones. In grammar, they are classified as the so-called sentential conjunctions.

### Negation: 'not'
* With the help of the word 'not', one forms the negation of any sentence
* Two sentences, one of which is the negation of the other, are called contradictory sentences.
* If a sentence is false, its negation is true.

Negation is created by adding 'not' to a sentence. In propositional logic, the word not is put in front of the whole sentence.
* Ex: "Not (1 is a positive integer)"

In everyday language, it is customary to place it with the verb, or replace it by "It is not the case that" ( why is everything overcomplicated )
* "1 is not a positive inteer", or else, "it is not the case that 1 is a positive integer"

### Conjunction: "and"
If, for instance, the sentences: 2 is a positive integer && 2 < 3 are joined by the word "and", we obtain the conjunction
2 is a positive integer and 2 < 3. The combined components are called conjunts.
* When we assert the conjunction of two sentences, this is tantamount to stating that both of the sentences forming it are true
* If that is the case, then the conjuntion is ture, but if at least one of the members are false, then both are false

IF true && true, conjuntion is true, 
ELSE conjunction is false

Differences between "and", "but", and "although" are ignored in logic. 

"and" === "but" === "although"

Not all ANDS are the same.
* John and Mary are friends.
  * Can't be spread into individuals, so isnt a conjunction.
  * John are/is friends XXX
* John and Mary are students.
  * Can be spread into individuals, so isnt a conjunction
  * John is a student

### Disjunction - "or"
When joining sentences by means of the word "or", one obtains the disjunction of those sentences. The components of that sentence are called disjuncts.

In every language, the word "or" posesses two different meanings ( at least )
* Taken in the non-exclusive (or inclusive) meaning, the disjunction expresses that at least one of the itemse are true
* When using "or" in logic, we are only concerned with if one or the other is true, not if both are true.

i.e. 2*2=5 or Chicago is a city is TRUE because one of the two statements are true.
* t & f = true 
* f & t = true 
* t & t = false
* f & f = false

### Conditional: "if...,then..."
The subordinate clause to which the word "if" is prefixed is called the _antecedent_, and the principal clause introduced by the word "then" is called the _consequent_.
By asserting a conditional, one claims that the antecedent cannot be true when the consequent is false.

* A conditional is true when:
  * Both the antecedent and the consequent are true.
  * The antecedent is false and the consequent is true.
  * Both the antecedent and consequent are false. 
* A conditional is false when:
  * The antecedent is true and the consequent is false.

Doesn't matter what it says, treated as a whole.
* (T then T) = true
* (F then T) = true
* (F then F) = true
* (T then F) = false

(The slide here doesn't make sense)

He or she who accepts its antecedent as true, but cannot accept its concequent and Whoever accepts a conditional as true and rejects its consequent as false, must also reject its antecedent.

If true, then true
If false, then true
If true, then false
If false, then false

* P and not Q is false, then if P then Q is true.
* P and not Q is true, then if P then Q is false.