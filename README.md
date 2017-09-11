# bankingninja
A sample machine learning algorithm to detect fraudulent activities on a credit card


How a fradulent case is identified by banks?

from a bit of googling, reading few research papers and a good youtube video, My primary observation is with a thorough process of analyzing credit card transactions,recognizing patterns and spending profiles, credit card companies will identify transactions that are fraud.

The easiest way that credit card companies identify credit card fraud is by recognizing a break in spending patterns.  For example, if you live in waterloo, ontario and suddenly your card is used to buy something in vancouver, BC – that may tip the scales in favor of possible fraud, and your credit card company might decline the charges and ask you to verify them.

Examples of how these patterns work:

Location: Live in one place but make a purchase in another.

What you buy: If your card is commonly used to buy your morning cup of coffee and then a tank of gas, and out of the blue is used to buy a pair of expensive designer shoes.

Spending amount: If you typically spend $500 / month, and suddenly rack up $3000 in a week.

Spending frequency: If your card is used to make a large number of purchases over a short period of time.

Large purchase after a smaller one: Thieves typically test stolen credit cards with smaller purchases first, such as a song from iTunes; if the card works, they will proceed to make another larger purchase, like an expensive camera, or television, or sound system.

Digital origins: Ecommerce makes it easy for us to make purchases, but it also makes it easy for thieves to commit fraud; the digital origins of purchases are recorded and analyzed with each purchase; if an IP address had been used to commit fraud in the past, subsequent transactions from the same IP or network may be flagged.

what might be banks using?

1. clustering (mapping and linking common purchase attempts together).
2. classification (labeling purchases in respect to their characteristics, like location, time, fraud probability, etc)
3. averaging to determine patterns of behavior.


