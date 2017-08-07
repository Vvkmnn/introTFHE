## introTFHE

An exploration of TFHE (Fast Fully Homomorphic Encryption Library over the Torus)[https://github.com/tfhe/tfhe], using [their excellent guide](https://tfhe.github.io/tfhe/coding.html).

In this example, we will walk through how Alice might perform homomorphic computations in the cloud:

1. `alice.c`: First, Alice will generate keys and encrypt two numbers.
2. `cloud.c`: Then, the "cloud" will do some homomorphic computations: here, a compution of the minimum of the two numbers.
3. `verif.c`: Finally, Alice will decrypt and print the cloud’s answer.
