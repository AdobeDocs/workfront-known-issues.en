---
title: "Proofs: New stage created because deadline cannot match deadline of existing stage"
description: When new proof is created, the deadline can be set in an increment of 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). However, when a user is added to a proof after the proof is created, the deadline can only be set in increments of 30 minutes (10:00, 10:30, 11:00, etc.).
---

# Proofs: New stage created because deadline cannot match deadline of existing stage

When new proof is created, the deadline can be set in an increment of 15 minutes (10:00, 10:15, 10:30, 20:45, etc.). However, when a user is added to a proof after the proof is created, the deadline can only be set in increments of 30 minutes (10:00, 10:30, 11:00, etc.). Therefore, the new user cannot be added to a stage with a deadline ending in :15 or :45, because the deadlines cannot be matched. Instead, the new user is added to a new stage, with a deadline set in 30 minute increments.

**Workaround**:

* If selecting a deadline for a new proof, set the deadline to a time that ends in :00 or :30 (10:00, 10:30, 11:00, etc.).
* If the deadline is set automatically at the time of proof creation, manually set the deadline of the proof to a time that ends in :00 or :30 (10:00, 10:30, 11:00, etc.).