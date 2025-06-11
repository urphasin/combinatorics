# ✅ Phase 1 Practice Set – Combinatorics Missions

Awesome — here’s a complete Phase 1 Practice Set broken into **Math Drills** and **Coding Challenges**, using terminology you like. Think of these more like **combinatorial missions** than “problems” 😉

---

## ✅ MATH DRILLS (no programming)

### 🔢 1. Fundamental Principle of Counting
Count the number of:
- 3-digit numbers with distinct digits.
- 4-letter passwords using A–Z (repetition allowed).
- Ways to assign 5 books to 3 shelves (assuming shelf order matters).
- Outfits: 4 shirts, 3 pants, 2 shoes = ?

---

### 🔁 2. Permutations & Combinations
Find:
- Ways to arrange the letters in `"BANANA"`.
- Number of 5-digit numbers formed with digits 1–9 with no repeats.
- Ways to choose 3 students out of 10 to form a group.
- Ways to seat 5 people in a row vs. around a round table.

---

### 📚 3. Ordered vs Unordered
You have 5 colored balls. How many ways to:
- Place 3 of them in a row (**ordered**)?
- Pick any 3 (**unordered**)?
- **Lottery ticket:** choose 6 numbers from 1–49. Is this permutation or combination?

---

### ⚙️ 4. Factorials & Their Properties
Simplify expressions like:
- $ \frac{8!}{5! \cdot 3!} $
- $ \frac{n!}{(n-k)!} $

Show:
- $ \binom{n}{r} + \binom{n}{r-1} = \binom{n+1}{r} $ (Pascal’s Identity)

Compute:
- Number of **trailing zeroes** in $100!$

---

### 🎲 5. Casework & Overcounting
Count how many 3-digit numbers:
- Have **exactly one 7**.
- Have digits **adding up to 9**.
- In how many ways can **two people share 4 identical cookies**?

---

### 🔺 6. Pascal’s Triangle
- Draw **rows 0–6** of Pascal’s triangle.
- Use it to expand $ (a + b)^5 $.
- Find and prove row sums: **sum of row $n$ is $2^n$**.

---

### 🕳️ 7. Pigeonhole Principle (Basic)
Prove:
- In any group of **13 people**, at least **2 have birthdays in the same month**.
- Among 6 people, at least **2 have the same number of friends** (if friendships are mutual).
- You have **10 socks** in a drawer (5 pairs). How many must you pull out to guarantee a **pair**?

---

## 💻 CODING CHALLENGES (Python / Java / C++ / JavaScript)

1. **Permutations Generator**  
   Write a function that prints all permutations of a string (e.g., `"abc"`).

2. **nCr Calculator**  
   Make a function to compute $ \binom{n}{r} $ efficiently using **factorials** or **Pascal’s recursion**.

3. **Unique Digit Counter**  
   Given a range (e.g., 100–999), count how many numbers have **all distinct digits**.

4. **Combinatoric Locker Locks**  
   You’re given **N dials**, each with digits 0–9. How many total lock combinations if:  
   - Digits can repeat?  
   - No digit repeats?

5. **Card Hand Counter**  
   Given a standard deck of 52 cards, write a program to compute how many **5-card hands** are possible.

6. **Pigeonhole Verification**  
   Simulate and confirm:
   - Given a list of birthdays for **13 people**, detect a **duplicate month**.
   - Given 6 numbers between 1–5, **prove at least one number is repeated**.
