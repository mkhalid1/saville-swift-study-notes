<!-- nav:top -->[Contents](../../README.md#contents) · Previous: [Numerical Analysis](numerical-analysis.md) · Next: [Verbal Comprehension](verbal-comprehension.md)<!-- /nav:top -->

# Diagrammatic Analysis

**In one line:** a row of shapes passes through lettered boxes, each of which changes the row in a fixed way. You work out what each box does, then find the output, the missing box or the input.

Diagrammatic Analysis is the third sub-test in **Swift Analysis Aptitude**. Saville's technical summary says it assesses the ability to "analyze diagrams, sequences and transformations", with 8 questions in 6 minutes. It is the sub-test most people have never seen before, which is why a little practice helps so much.

## What it measures

Diagrammatic questions test rule-finding and rule-applying, with no words or numbers to lean on. The skills are:

- **Inferring a rule from examples.** You see what goes into a box and what comes out, and work out the change.
- **Applying rules in order.** A row may pass through two or three boxes, one after another.
- **Working backwards.** Given the output, find the input or the missing box.

## How the questions look

In Saville-style diagrammatic items, including the free PrepClubs practice test, a row of black and white shapes passes through lettered operators. Each operator always does the same thing. You might be asked for the output, the operator that must be missing, or the input that would produce a given output. Saville's own free practice test shows the exact screens.

In these notes we write rows as text, left to right:

| Symbol | Meaning |
|---|---|
| ● ○ | black circle, white circle |
| ■ □ | black square, white square |
| `●○■ → A → ■○●` | the row ●○■ goes into box A and comes out as ■○● |

## A method that works

1. **Work out each operator from the examples first.** Write its rule in three or four words: "reverses order", "flips first colour".
2. **Check each rule against every example.** A rule that explains one example but not the other is wrong.
3. **Compare only one feature at a time.** Did the order change? Did any colours change? Did the shapes change?
4. **Apply operators one at a time,** writing the row after each step.
5. **To work backwards, undo each step in reverse order.** Undoing "move the last shape to the front" means moving the first shape to the end.
6. **Use the options.** If the question asks which operator is missing, test each one on the row. Usually only one fits.

## Traps that cost points

- **Settling on a rule too early.** "Swap the first and last shapes" and "reverse the row" look the same on a row of three. Check a longer example.
- **Mixing up direction.** Moving the last shape to the front is not the same as moving the first shape to the end.
- **Losing track in a chain.** Write the row down after every operator. Doing it in your head is where errors start.
- **Undoing in the wrong order.** If the chain is A then C, undo C first, then A.
- **Forgetting that colour and position are separate.** A box can change one, the other, or both.

## Timing

Saville gives 6 minutes for 8 questions: 45 seconds each. Learning the operators takes the most time, and that cost is shared across every question that uses them. As our guidance: spend up to a minute understanding the operators the first time, then aim for 30 seconds per question.

## Practice items

These 10 items are original, written for these notes. They are not taken from any Saville test. All of them use the same four operators.

### Work out the operators

| Example | Input | Operator | Output |
|---|---|---|---|
| 1 | ●○■ | A | ■○● |
| 2 | ●○□■ | A | ■□○● |
| 3 | ●○■ | B | ○○■ |
| 4 | □□● | B | ■□● |
| 5 | □●○ | C | ○□● |
| 6 | ■■○● | C | ●■■○ |
| 7 | ■○ | D | □● |
| 8 | ●□○ | D | ○■● |

Write a rule for each of A, B, C and D before you start the items.

### Items

**Item 1.** ○■● → A → ?

A. ●■○ &nbsp; B. ○■● &nbsp; C. ●□○ &nbsp; D. ■○● &nbsp; E. ○●■

**Item 2.** ●■○ → C → B → ?

A. ○●■ &nbsp; B. ●●■ &nbsp; C. ○○■ &nbsp; D. ●■● &nbsp; E. ■●○

**Item 3.** ○□ → D → A → ?

A. ●■ &nbsp; B. □○ &nbsp; C. ■● &nbsp; D. ○□ &nbsp; E. ●□

**Item 4.** ●○■ → B → ? → ●●□. Which operator is missing?

A. Operator A &nbsp; B. Operator B &nbsp; C. Operator C &nbsp; D. Operator D &nbsp; E. No single operator works

**Item 5.** ? → D → ○■●. What was the input?

A. ●■○ &nbsp; B. ●□○ &nbsp; C. ○□● &nbsp; D. ○■● &nbsp; E. ●□●

**Item 6.** ? → A → C → □●○. What was the input?

A. □●○ &nbsp; B. ○●□ &nbsp; C. □○● &nbsp; D. ●○□ &nbsp; E. ●□○

<details>
<summary>Answers and explanations: the operators and items 1 to 6</summary>

**The operators.**

- **A reverses the order of the row.** Example 2 rules out "swap the first and last shapes": that would give ■○□●, not ■□○●.
- **B flips the colour of the first shape only.** Example 4 shows it is the first shape, not every square, because the second □ stays white.
- **C moves the last shape to the front.** Example 6 confirms it on a row of four.
- **D flips the colour of every shape.**

**Item 1: A, ●■○.** Reversing ○■● gives ●■○.

**Item 2: B, ●●■.** C moves the last shape to the front: ●■○ becomes ○●■. B flips the first shape: ○ becomes ●, giving ●●■. *Why not A:* ○●■ is the row after C only.

**Item 3: C, ■●.** D flips both colours: ○□ becomes ●■. A reverses: ■●. *Why not A:* ●■ is the row after D only.

**Item 4: D, operator D.** After B, the row is ○○■. Only D turns ○○■ into ●●□, by flipping every colour. *Why not A or C:* both give ■○○.

**Item 5: B, ●□○.** D flips every colour, so undo it by flipping back: ○■● becomes ●□○.

**Item 6: C, □○●.** Undo the last step first. C moved the last shape to the front, so move the first shape to the end: □●○ becomes ●○□. Then undo A by reversing: □○●. *Check:* □○● → A → ●○□ → C → □●○.

</details>

**Item 7.** ●●○■ → C → C → ?

A. ■●●○ &nbsp; B. ○■●● &nbsp; C. ●○■● &nbsp; D. ■○●● &nbsp; E. ●●■○

**Item 8.** Which single operator turns ■●○ into ○●■?

A. Operator A &nbsp; B. Operator B &nbsp; C. Operator C &nbsp; D. Operator D &nbsp; E. None of them

**Item 9.** ○○● → D → B → A → ?

A. ●●○ &nbsp; B. ○●○ &nbsp; C. ●○● &nbsp; D. ○○● &nbsp; E. ●○○

**Item 10.** Which of these pairs, applied in the order shown, turns ●○□ into ■●○?

A. A, then B &nbsp; B. B, then C &nbsp; C. C, then B &nbsp; D. D, then C &nbsp; E. B, then D

<details>
<summary>Answers and explanations, items 7 to 10</summary>

**Item 7: B, ○■●●.** First C: ●●○■ becomes ■●●○. Second C: ■●●○ becomes ○■●●. *Why not A:* that is the row after one C.

**Item 8: A, operator A.** Reversing ■●○ gives ○●■. *Why not C:* C gives ○■●, which has the right first shape but the wrong order after it.

**Item 9: B, ○●○.** D: ○○● becomes ●●○. B flips the first shape: ○●○. A reverses ○●○, which reads the same both ways: ○●○.

**Item 10: C, C then B.** C: ●○□ becomes □●○. B flips the first shape: ■●○. *Check the others:* A then B gives ■○●, B then C gives □○○, D then C gives ■○●, B then D gives ●●■.

</details>

## Score yourself

| Item | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Answer | A | B | C | D | B | C | B | A | B | C |

- **9 to 10:** you have the method. Next, practise with drawn shapes under time.
- **7 to 8:** your slips are probably in chains (items 2, 7, 9) or working backwards (items 5, 6). Write the row down after every step.
- **6 or fewer:** go back to the examples table and make sure each rule fits both of its examples before using it.

## Next step

Drawn shapes look different from text symbols. See how diagrammatic items look on screen in the [free Saville Swift practice test on PrepClubs](https://prepclubs.com/free-practice-tests/saville-swift?utm_source=github&utm_medium=referral&utm_campaign=study-notes&utm_content=saville-swift), and try Saville's own practice test too.

---

<!-- nav:bottom -->← Previous: [Numerical Analysis](numerical-analysis.md) | Next: [Verbal Comprehension](verbal-comprehension.md) → | [Back to contents](../../README.md#contents)<!-- /nav:bottom -->
