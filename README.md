# Plurality

## 📌 Description
This project implements a simple **plurality voting system**.  
Each voter casts **one vote** for a candidate, and the candidate with the most votes wins.  
In case of a tie, all candidates with the highest number of votes are printed.

---

## 🛠️ How it works
1. The program receives the list of candidates as command-line arguments.  
2. It asks the user for the number of voters.  
3. Each voter types the name of their chosen candidate.  
4. The program validates the vote (checks if the candidate exists).  
5. At the end, it prints the winner(s).  

---

## ▶️ Compilation and Execution
In the terminal:

```bash
# Compile
gcc plurality.c -o plurality

# Run with candidates
./plurality Alice Bob Charlie

Example:
$ ./plurality Alice Bob Charlie
Number of voters: 4
Vote: Alice
Vote: Bob
Vote: Alice
Vote: Charlie
Alice
