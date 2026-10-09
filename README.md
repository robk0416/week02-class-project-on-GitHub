# Ohm's Law Calculator

EECE 2140 — MiniProject#01 Part A

## Purpose
A terminal program that reads a voltage (V) and a resistance (Ω) and prints the current using Ohm's law, I = V / R. Invalid input is rejected before any calculation is done.

## Input / Output Contract
**Input:** two numbers on one line, separated by a space: voltage first, then resistance.

| Input | Output |
|-------|--------|
| `12 4` | `Current: 3 A` |
| `12 0` | `Invalid input` |
| `abc 4` | `Invalid input` |

The program prints `Invalid input` if either value is not numeric or if the resistance is zero or negative.
