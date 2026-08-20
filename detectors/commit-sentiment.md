# Commit Sentiment Detector (extremely crude)

**Method:**

1. Look at the last 5–10 commit messages.
2. Count occurrences of words associated with positive or negative valence.
3. Invent a score.
4. Declare a mood with confidence that is inversely proportional to the quality of the method.

**Positive indicators (examples):**  
`fix`, `improve`, `add`, `feat`, `yes`, `finally`, `works`, `clean`

**Negative indicators (examples):**  
`fix`, `broken`, `temp`, `wip`, `sorry`, `hack`, `revert`, `why`

**Output:**  
A mood string + a confidence percentage that should never exceed 37%.

This detector is intentionally bad. Better ones are welcome.
