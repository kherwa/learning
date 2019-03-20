# Plasma Leap - General Computation on Plasma

  Define spending conditions by breaking down smart contracts with the help of EVM script

  encapsulating state into non fungible tokens

Any applications running on plasma should define its own conditions and rules to custody of funds

plasma operator has to bond a substantial stakes on main chain

#Problem Statement

  first part of our problem statement: the introduction of a computing model for rules and conditions governing funds on the Plasma chain as well as the enforcement of correct execution of such code

  second part of the problem statement: Exits can be hard or impossible to coordinate if funds have multiple or undefined ownership

  The third part of the problem statement describes the coordination problem arising for funds that entered the exit queue


The Plasma operator periodically records state hashes claiming the current state of the child chain as valid 

The security of Plasma is assured by the exit procedure, a challenge game through which Plasma guarantees that every party can exit their funds back to the main chain at any given time
