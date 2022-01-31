# Cups-and-Dice-UKa
Write a class SixSidedDie. The class should include the following methods: roll(), getFaceValue(), and
__repr__(). For example:
>>> d = SixSidedDie()
>>> d.roll()
3
>>> d.getFaceValue()
3
>>> d
SixSidedDie(3)
Create a TenSidedDie and a TwentySidedDie class. These two class must extend SixSidedDie. They must
provide the same functionality. They must not re-implement any code that is not necessary.
Create a Cup class. A cup will hold several dice that may be rolled at once. The cup may hold any number
of six-, ten-, or twenty- sided dice. For example, we could create a cup with one of each type of die as
follows:
>>> cup = Cup(1,1,1)
…or we could create a cup with 3 six-sided dice…
>>> cup = Cup(3,0,0)
By default, the cup will contain one of each type of die.
>>> cup = Cup()
The Cup class should include the following functionality: roll(), getSum(), __repr__(). For example:
>>> cup = Cup(1,2,1)
>>> cup.roll()
28
>>> cup.getSum()
28
>>> cup
Cup(SixSidedDie(3),TenSidedDie(5),TenSidedDie(3),TwentySidedDie(17))
