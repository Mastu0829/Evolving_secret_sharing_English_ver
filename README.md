# Evolving_secret_sharing_English_ver
# Evolving 2-Threshold Secret Sharing — XOR Implementation

A Google Colab implementation of an Evolving 2-threshold secret sharing scheme using XOR operations.

> This implementation is a simplified model for learning purposes.

---

## Overview

A secret sharing scheme that requires no prior commitment to the number of participants.

- 2 or more participants can recover the secret
- New participants can be added at any time
- Existing shares are never modified

---

## Usage

Run each cell in order from the top.

| Cell | Content |
|---|---|
| Cell 1 | Class definition, share generation, recovery |
| Cell 2 | Function to add participants |
| Cell 3 | Example: adding participants and recovery |

To carry over state from the previous run, comment out the following line in Cell 3:

```python
# ess = EvolvingSecretSharing(secret)
```

---

## License

MIT License
