# AXIOM Architecture Overview

Lightweight governance model for state validation and execution control.

AXIOM operates as a governance layer over execution.

It evaluates system state before allowing propagation.

---

## Layers

Vault → Invariants (intent + constraints)  
Vessel → Transformations (state transitions)  
Fabric → Execution (outputs)

---

## Principle

Output success does not imply system validity.

State must be evaluated before execution—not after.

---

## Enforcement

Invalid states are not corrected.  
They are refused.

SILENCE = stability.
