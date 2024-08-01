# Texas_Holdem_Poker_Calculator
This project creates a Python calculator to determine the odds of achieving specific hands in Texas Hold 'Em after the flop. It generates random two-card hands, calculates probabilities for various hands, and verifies accuracy with 1000 simulations, preventing duplicate cards.


Project Description: Poker Odds Calculator for Texas Hold 'Em
This project involves creating a excel-based calculator to determine the probability of achieving specific hands in Texas Hold 'Em poker after the flop. The calculator generates random two-card hands and calculates the odds of obtaining the following hands after the flop: Four of a Kind, Three of a Kind, Two Pair (using both cards), Flush, and Full House (using both cards).

Steps:

Random Hand Generation: The tool generates a random two-card hand for the user, ensuring no identical cards are dealt. Users can reset and generate new hands.
Odds Calculation: Given the initial two-card hand, the calculator computes the probabilities of achieving the specified hands after the flop.
Four of a Kind
Three of a Kind
Two Pair (using both cards)
Flush (using both cards)
Simulation Verification: To verify the calculated odds, the tool runs 1000 simulations of random hands and flops, ensuring no card is dealt more than once.
Hand Type Analysis: Based on the type of hand dealt (e.g., pair, no pair, suited, no suited), the tool verifies the odds through simulations.
This project combines probability calculations with Monte Carlo simulations to provide accurate poker odds and validate them through extensive testing.
