# Dad-Son-Problem
Solution To Dad Son banking problem

The bank.c program has 3 processes namely, the dad process and two son processes. The critical section (CS) in the given problem is a son withdrawing money from the bank and the dad depositing money in the bank, at randomly selected time intervals.These 3 processes get into a race condition when accessing the shared bank_balance variable. The programs synchronization issues are taken care of by implementing the appropriate "P(sem)" and "V(sem)" operations. 
