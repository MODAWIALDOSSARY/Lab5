# ARTI 303 — Lab 5: Working with Rules

This repository contains a Prolog knowledge base for the family tree shown in Lab 5.

## Files
- `family_tree.pl` — gender and parent facts, all required rules, and two test queries per required rule with expected results in comments.

## Run it
1. Install SWI-Prolog from https://www.swi-prolog.org/ if it is not already installed.
2. Open a terminal in this folder.
3. Start Prolog by running `swipl`.
4. Load the file:
   ```prolog
   ?- [family_tree].
   ```
5. Try a query, for example:
   ```prolog
   ?- father(X, bart).
   ```

## Conventions
Relations use the form `relation(Person, Person)`. For example, `father(Father, Child)`, `parent(Parent, Child)`, and `ancestor(Ancestor, Person)`.
