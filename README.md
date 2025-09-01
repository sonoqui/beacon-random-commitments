# beacon-random-commitments
Public repository of cryptographic commitments for randomness draws based on the NIST Randomness Beacon. Each file locks in a future beacon pulse before it is known, ensuring fair, unbiased, and fully auditable draws.

This repository publishes commitment hashes for random draws anchored in the NIST Randomness Beacon v2
.

Each file in the commitments/ folder corresponds to a beacon pulse timestamp (in Unix epoch seconds) and contains the SHA-256 hash of the draw parameters.

By committing in advance, and using beacon outputs once published, we guarantee that every draw is unpredictable, unbiased, and independently verifiable.
