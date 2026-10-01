# Dynamic-Skyline-Visibility
You are given a skyline represented by an array of building heights. Each building can "see" other buildings to its right if no taller building blocks the view in between.

Formally:

Building 𝑖
 can see building 𝑗(𝑗 > 𝑖 ) if every building between 𝑖 and 𝑗 has a height strictly less than both 𝑖 and 𝑗.

For each building, count how many buildings it can see to its right.

Return the result as an array of integers.
