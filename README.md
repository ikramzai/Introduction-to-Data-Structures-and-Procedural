1. Sum of Unique Numbers
What it does:
Adds up all numbers that appear in only one of two number lists.

Step-by-Step:
Start with two number lists:

List A: [3, 1, 7, 9]

List B: [2, 4, 1, 9, 3]

Check each number in List A:

If the number is NOT in List B → Add to total
(Example: 7 is only in List A → Add 7)

Check each number in List B:

If the number is NOT in List A → Add to total
(Example: 2 and 4 are only in List B → Add 2 + 4)

Final total = 7 + 2 + 4 = 13

Plain English Rules:
✔ Add numbers that appear in just one list
✖ Don't add numbers that appear in both

2. Dot Product Checker
What it does:
Checks if two arrows (vectors) point in completely different directions (called "orthogonal").

Key Idea:
Multiply matching numbers from two lists

Add all the results together

If the final sum is 0 → The arrows are perpendicular!

Example:
Arrow 1: [1, 0]
Arrow 2: [0, 1]

Calculation:

Multiply first numbers: 1 × 0 = 0

Multiply second numbers: 0 × 1 = 0

Add results: 0 + 0 = 0

Result: They're perpendicular!

How to Use:
Write down two number lists of the same length

Multiply each pair of numbers (first with first, second with second, etc.)

Add all the products

If the total is exactly 0, they're perpendicular

Why This Matters
First algorithm helps find unique items

Second algorithm is useful in graphics and physics

Try It Yourself!
Play with different number lists to see how the results change.

(Hint: For the dot product, try [1, 1] and [-1, 1] next!)
