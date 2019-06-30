# Entanglement

Basic: Given a state of a qbit, you automatically know the state of another qbit entangled with it.

## Logic

1. Define 4 quantum registers and 4 classical registers.

2. Put q[0] into superposition. Entangle it with q[1].

3. Measure q[0] and q[1] in c[0] and c[1] respectively.

4. Repeat 2 and 3 for q[2] and q[3] with c[2] and c[3].

## Expected output (multiple runs)

c[0] = c[1], c[2] = c[3]

- 0000: 25%
- 0011: 25%
- 1100: 25%
- 1111: 25%

## Simulated output (1024 runs)

- 0000: 25.293%
- 0011: 26.27%
- 1100: 23.926%
- 1111: 24.512%

## Conclusion

Quantum Entanglement observed.
