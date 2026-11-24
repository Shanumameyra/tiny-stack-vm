# Tiny Stack VM

[![make.fun](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122)

A faithful interpreter of make.fun's tiny stack ISA v1: 32-bit wrapping
arithmetic, a 256-value stack, 64-deep calls, 256 words of memory, ten traps
with their own exit codes, and the step and output limits — every rule in the
order ISA.md states it. `main.ts` runs a whole set of 40 instances in one go
and writes `/output/<id>/stdout.bin` and `/output/<id>/exit.txt` for each.

Practice set score: **1,000,000 / 1,000,000** (40/40 instances, house
baseline plain-vm 1.0.0 scores 670,000 on the same set).
