# Open Execution Proof (OEP)

Open Execution Proof (OEP) is a protocol for **portable, cryptographically verifiable execution proofs**.

Instead of trusting screenshots, copied terminal logs, or textual claims, OEP proofs allow anyone to independently verify that a command execution actually occurred.

Execution claims become **verifiable artifacts**.

---

## System Architecture
command execution
↓
OEP proof generation
↓
portable proof artifact
↓
independent verification

---

## Components

### OEP-1

Protocol specification defining:

- execution proof schema  
- execution identity derivation  
- canonicalization rules  
- verifier validation rules  

### GUBAZ

Reference runtime that **produces signed OEP proofs**.

https://github.com/openexecproof/gubaz

### Verifier

Independent browser verifier that **validates execution proofs**.

https://github.com/openexecproof/verify

---

## Live Verifier

https://openexecproof.github.io/verify/

---

## Example Proof

https://openexecproof.github.io/verify/?id=5a6c7a254d5cc40cf0a5ff7394fb1801dd989ce63e32044a5fd2c4674ebdeba7
