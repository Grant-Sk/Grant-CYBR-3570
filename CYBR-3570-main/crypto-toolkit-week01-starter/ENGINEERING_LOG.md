# Engineering Log

## Week 1 - Toolkit v0.1

### Added
- Caesar cipher educational implementation
- Brute force demonstration
- Frequency analysis helper
### Security Lesson
Encryption is needed, but insecure encryption is not much better.
### Reflection
Ineffective encryption can be detrimental and easily broken,
so don't make your own!

## Week 2
1. Which modules did you add?
- I added randomness, modular, and gcd modules to my toolkit
2. Which mathematical function was most difficult to understand?
- Secret vs random and how one is safe mathematically
3. What is one way randomness can fail in a cryptographic system?
- If the attacker knows the seed of the PRNG, or if similar to hashing the output from the seed isn't random enough.
4. What is one rule you will follow when generating random values in future projects?
- Make sure, if the value needs to be secure, to use the secret module, and like always, never create my own algorithm for it.