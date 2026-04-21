## preconditions

| Description | File |
|---|---|
| Required context or input that should exist before this stage begins | `path/to/file.md` |
| Prior artifact, note, or source document this stage depends on | `path/to/supporting-file.md` |

## postconditions

| ID | Description | Evidence File | Quality (/5) | Met? |
|---|---|---|---:|---|
| P1 | Expected result or deliverable produced by this stage | `outputs/example.md` | 0 | no |
| P2 | Important decision, summary, or artifact left behind for later stages | `notes/example.md` | 0 | no |

## evaluation criteria

### P1
- What does good look like?
- What would make this `3/5` versus `5/5`?
- What gaps would still be acceptable?

### P2
- What should later stages be able to rely on?
- What evidence would make this strong and reusable?
- What caveats should lower the quality score?

## notes

- This contract is guidance, not strict enforcement.
- Preconditions should point to the file that currently satisfies the condition.
- Postconditions should point to the file that best demonstrates the outcome.
- Use `Met?` as a lightweight status marker such as `yes`, `partial`, or `no`.
- Keep evaluation criteria outside the table when they need more than a short phrase.
- Use the quality score as a lightweight judgment of completeness or confidence, not a hard gate.
