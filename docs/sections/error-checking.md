<!-- nav:top -->
[Contents](../../README.md#contents) · Previous: [Numerical Comprehension](numerical-comprehension.md) · Next: [How scoring works](../scoring.md)
<!-- /nav:top -->

# Error Checking

**In one line:** you compare an original set of records with a copy and find the row where the copy differs, or confirm that there is no error.

Error Checking is the third sub-test in **Swift Comprehension Aptitude**. Saville's technical summary says it assesses the ability to "proofread text, check figures and verify codes", with 8 questions in just 1.5 minutes. That is about 11 seconds a question, the fastest pace of any Swift sub-test.

## What it measures

This is the sub-test closest to real work in the roles Swift Comprehension is built for: keying an order number, checking an invoice against a delivery note, copying a customer's postcode. The hard part is that reading normally works against you. Your brain fixes "Hollowey" to "Holloway" before you notice, and it reads 906 and 960 as "about nine hundred".

So the skill is to stop reading and start comparing: code against code, digit pair against digit pair, letter against letter. The errors in these items are the kind that slip through in real offices, such as two digits swapped, one letter changed, or M typed for N. Some items have no error at all, and saying so quickly is part of the skill.

## How the questions look

In Saville's own practice test (checked 24 November 2026), Error Checking shows the original data, such as a spreadsheet row, above a re-entered copy. You then choose which fields of the copy contain an error. The options are "The entire item is correct" or an error in a named field, such as Company Name, Serial Number, Type or Date. Saville's instructions say: "An item may have more than one error, or no errors at all. Select all options that apply."

**How the items here differ.** The practice items in this repo show four records and ask which one holds the error. They train the same character-by-character comparison, but the real test asks about fields, and an item can have two errors. So in the real test, check every field, even after you have found one error.

## A method that works

1. **Compare in chunks, not whole rows.** Check the code, then the name, then the amount.
2. **Read numbers in pairs of digits.** "30 41 88 27" is easier to compare than "30418827".
3. **Split long codes into parts.** Check the start, the end, then the middle, so no part of the code goes unchecked.
4. **Do not read names for meaning.** Your brain fixes typos automatically. Look at the letters.
5. **If every row matches, choose "No error" and move on.** Do not keep searching for an error that is not there.

## Traps that cost points

- **Transposed digits.** 906 and 960, 30419902 and 30419092. The digits are all there, in a different order.
- **One-letter name changes.** Lindqvist and Lindquist, Whitcombe and Whitcomb.
- **Similar characters.** M and N, 6 and 9, 0 and O.
- **Swapped letter pairs at the end of a code.** WEK and WKE.
- **Hunting for an error in a perfect copy.** Some items have none.

## Timing

1.5 minutes for 8 questions is about 11 seconds each. Saville's practice test says: "You will be presented with 8 questions which you have 1 minute and 30 seconds to answer." At this pace you cannot check everything twice. Check once, carefully, in chunks.

## Practice items

These 3 items are original, written for these notes. They are not taken from any Saville test. Each shows four original rows and a copy. Which row of the copy contains an error? Time yourself: aim for 40 seconds for all three.

**Item 1.**

```
Original
Row 1  ORD-58213 | Halden Supplies | £1,482.50
Row 2  ORD-58219 | Kestrel Tools | £906.00
Row 3  ORD-58224 | Brightmoor Ltd | £2,315.75
Row 4  ORD-58230 | Ashby & Lowe | £74.20

Copy
Row 1  ORD-58213 | Halden Supplies | £1,482.50
Row 2  ORD-58219 | Kestrel Tools | £960.00
Row 3  ORD-58224 | Brightmoor Ltd | £2,315.75
Row 4  ORD-58230 | Ashby & Lowe | £74.20
```

A. Row 1 &nbsp; B. Row 2 &nbsp; C. Row 3 &nbsp; D. Row 4 &nbsp; E. No error

**Item 2.**

```
Original
Row 1  14/03/2026 | Room 2B | 09:30
Row 2  14/03/2026 | Room 4A | 11:00
Row 3  15/03/2026 | Room 1C | 14:15
Row 4  16/03/2026 | Room 2B | 10:45

Copy
Row 1  14/03/2026 | Room 2B | 09:30
Row 2  14/03/2026 | Room 4A | 11:00
Row 3  15/03/2026 | Room 1C | 14:15
Row 4  16/03/2026 | Room 2B | 10:45
```

A. Row 1 &nbsp; B. Row 2 &nbsp; C. Row 3 &nbsp; D. Row 4 &nbsp; E. No error

**Item 3.**

```
Original
Row 1  Mrs J. Okafor | 27 Linden Way | LS6 4QT
Row 2  Mr P. Harrow | 3 Mill Lane | LS12 9RB
Row 3  Ms A. Lindqvist | 118 Park Road | LS8 2HD
Row 4  Dr S. Mehta | 9 Elm Court | LS17 5AN

Copy
Row 1  Mrs J. Okafor | 27 Linden Way | LS6 4QT
Row 2  Mr P. Harrow | 3 Mill Lane | LS12 9RB
Row 3  Ms A. Lindquist | 118 Park Road | LS8 2HD
Row 4  Dr S. Mehta | 9 Elm Court | LS17 5AN
```

A. Row 1 &nbsp; B. Row 2 &nbsp; C. Row 3 &nbsp; D. Row 4 &nbsp; E. No error

<details>
<summary>Answers and explanations, items 1 to 3</summary>

**Item 1: B, Row 2.** The amount £906.00 was copied as £960.00. The last two digits were swapped.

**Item 2: E, no error.** All four rows match character for character.

**Item 3: C, Row 3.** The surname Lindqvist was copied as Lindquist: the v became a u.

</details>

## Score yourself

| Item | 1 | 2 | 3 |
|---|---|---|---|
| Answer | B | E | C |

- **3 in about 40 seconds:** you are close to the real pace. Keep practising for speed.
- **3 but much slower:** accuracy is there. Use the chunking method to speed up.
- **2 or fewer:** look at which error types you missed and add them to your checklist: swapped digits, one-letter changes, look-alike characters.

Want more? The free timed Saville Swift style practice test on PrepClubs has the full 24 questions, scored by section: [prepclubs.com/free-practice-tests/saville-swift](https://prepclubs.com/free-practice-tests/saville-swift?utm_source=github&utm_medium=referral&utm_campaign=study-notes&utm_content=saville-swift).

## Next step

Error Checking is only in Swift Comprehension. The free [Saville Swift practice test on PrepClubs](https://prepclubs.com/free-practice-tests/saville-swift?utm_source=github&utm_medium=referral&utm_campaign=study-notes&utm_content=saville-swift) follows the Swift Analysis style, which has no error checking, so for this sub-test use Saville's own Swift Comprehension practice test and the items above. The PrepClubs test is still useful practice for the verbal and numerical parts.

---

<!-- nav:bottom -->
← Previous: [Numerical Comprehension](numerical-comprehension.md) | Next: [How scoring works](../scoring.md) → | [Back to contents](../../README.md#contents)
<!-- /nav:bottom -->
