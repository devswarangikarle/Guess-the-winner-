# Guess-the-winner

Ninu and Yash play a game. They start with the integer N and take turns, with Ninu going first.
On their turn, a player must select an odd prime factor p of N, and subtract it from N (so N changes to N − p).
The player who cannot make a move loses (that is, if either N = 0 or N has no odd prime factors).
If Ninu and Yash play optimally, who wins the game?

def solve():

    T = int(input())  
    for _ in range(T):
        N = int(input()) 
        if N % 2 == 0:
            print("Yash")  
        else:
            print("Ninu") 

solve()
