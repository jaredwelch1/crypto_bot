# crypto_bot

This is a chat bot for slack, designed to integrate cryptocurrency information and tooling into slack for convenient use.

## ToDo

- Need to use sched to make every hour report

- Put tokens in virtual env [ X ] 

- Create ability to report each hour on top 10 growth on a predefined list of coins. (or maybe can change from a command top X)

- allow cryptos to be added to list (will start a validation thread, then when coin is found to exist, will add to list of tracked coins) 

- allow a virtual bank account, activated by using "create account <name>"

	- default amount to a predefined value?

	- use database to track account data + coins + amount invested for acct

- report current value in a concise way when asked for any crypto in:

	- the valid list

	- OR check for coin and then return if a valid one (do not save)

- allow ability to create 'do not disturb mode' 

	- do not report hourly

	- maybe do something that does a high low change from that period instead, to summarize the quiet duration

- ranking by week / month when asked  
