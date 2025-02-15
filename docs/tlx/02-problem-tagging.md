# Problem Tagging

## A. Goals

1. By viewing the list of tags, one can **discover new concepts** that they didn't know before.
1. By clicking on one tag, one can practice with **relevant problems** that use the concepts.
1. By solving problems tagged with a tag, one will **gain more experience** with the concepts.

## B. Principles

1. It is important to be **consistent** in choosing tags.
   - Before tagging, please explore existing problem tagging in TLX, to see and "feel" the existing convention.

## C. Choosing Tags

1. Consider all intended solutions. For each solution, pick one or more appropriate tags, based on the following rules:
   1. `constructive`
      - Pick this tag if the solution is to **creatively** construct **any solution** which satisfies the provided criteria, out of (usually) **many possible solutions**.
      - Don't pick this tag if the solution heavily relies on a well-known algorithm/technique. The emphasis here is "creatively".
      - Usually, **interactive** problems will have this tag, because usually it requires creative solutions.
   1. `data structure`
      - `compression`
        - Pick this tag if the solution requires "compressing" coordinates / array positions.
      - `fenwick tree`
        - Pick this tag if the solution can use either Fenwick tree or segment tree, e.g. just for **standard range query** capability.
        - If we pick this tag, don't pick the `segment tree` tag.
      - `segment tree`
        - Pick this tag if the solution needs segment tree with **lazy propagation**.
      - `prefix sum`
        - Pick this tag if prefix sum is the **main idea** of the solution.
        - Don't pick this tag if prefix sum is just for **optimizing** larger DP transition.
   1. `dynamic programming`
      - `combinatorics`
        - Pick this tag if the DP is about counting number of ways.
        - Pick this tag if the DP needs counting the number of ways to solve the problem. Example: printing K-th lexicographically smallest sequence.
      - `tree`
        - If we pick this tag, don't pick the `tree` tag.
   1. `heuristic`
      - Pick this tag if the scoring can be **partial** based on the creativity of the solution.
      - Usually, output-only problems will have this tag.
   1. `implementation`
      - Pick this tag if the solution is to (almost) exactly do what the problem statement **literally says**.
      - Don't pick this tag if there is one or more additional steps/insights needed. This tag is intended for beginners to practice implementing code. 
   1. `math`
      - `combinatorics`
        - Pick this tag if the problem is about counting number of ways.
        - If `dp:combinatorics` is already picked, don't pick this tag.
      - `number theory`
        - Pick this tag is the problem requires knowledge of properties of integers.
2. For each of these tags, if it is picked, at least a subtag must be picked. If there are no appropriate subtag, **DON'T** pick the tag at all (or contact **fushar** to add a new subtag):
   1. `data structure`
   1. `searching`
   1. `optimization trick`
3. Also pick the `ad hoc` tag if the set of the tags (possibly empty) is a subset of the following:
   1. `bitwise operation`
   1. `constructive`
