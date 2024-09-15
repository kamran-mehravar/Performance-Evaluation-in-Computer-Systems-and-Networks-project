Consider a punch’em videogame where your avatar meets two type of enemies: minions and bosses.
Fighting either of them until defeat takes some time (see later on) and they arrive with some interarrival
times. The rule of the game is such that you can fight only one opponent at a time. When you are fighting
a minion and a boss arrives, you stop fighting the minion and fight the boss instead.
A fight lasts until the opponent is defeated. However, when you fight a boss, the minion that you were
fighting earlier recovers some health, at a rate which is x% of the rate at which you deplete it when fighting
it.
A defeated opponent leaves the game. Opponents of the same class queue up one after the other and
are fought in a FIFO order.
