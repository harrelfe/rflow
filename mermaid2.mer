
flowchart TD
  S["Screened (n=1000)"] --> E["Excluded (n=286)"]
  E1["pain-free (n=156)"]
E2["age < 40 (n=85)"]
E3["Hx med (n=45)"]
E --> E1
E --> E2
E --> E3
  E1 & E2 & E3 --> M["1, 2, ≥3 exclusions: n=260, 25, 1"]
  S   --> Q["Qualified for Randomization (n=714)"]
  Q   --> C["Consented (n=634)"]
  C   --> R["Randomized (n=534)"]
  Tx1["A (n=285)"]
Tx2["B (n=249)"]
R --> Tx1
R --> Tx2
  F1["Finished (n=204)"]
F2["Finished (n=175)"]
Tx1 --> F1
Tx2 --> F2
  O1["Outcome assessed (n=196)"]
O2["Outcome assessed (n=165)"]
F1 --> O1
F2 --> O2
click E callback " # Exclusions # Subjects
            0        714
            1        260
            2         25
            3          1"
