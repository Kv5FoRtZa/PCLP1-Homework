##    Description
This project implements a package distribution management system in ANSI C.
A chief postman distributes packages to local postmen based on neighborhood IDs.
Each package contains an encoded binary address and a message that must be
processed and validated according to specific rules.

## Features:
- Dynamic memory allocation for all `char*` fields
- Decoding 18-bit binary address into:
  - Neighborhood ID
  - Street
  - House number
- Distribution of packages by neighborhood
- Sorting packages by:
  - Priority (descending)
  - Weight (descending)
- Message processing:
  - Reverse word order
  - Remove punctuation
  - Compute encoded checksum
- Bitwise code alteration using:
  - Prime factorization of postman ID
  - Bit manipulation
- Delivery correctness score calculation
