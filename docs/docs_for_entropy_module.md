# Entropy module
## Notes for entropy:
    - Entropy measures uncertainty.

    - How many guesses would an attacker need on average to find this password?

    - Higher entropy = more randomness = harder to crack.

    - Entropy is measured in bits.

    - Every +1 bit doubles the search space.

Examples:

20 bits → about 1 million possibilities

40 bits → about 1 trillion possibilities

60 bits → extremely strong

# Formula of calculation of entropy:

search space = (character set size) ^ (password length)

Then entropy is:

entropy = log₂(search space)

Using log rules, that simplifies to:

entropy = length × log₂(character set size) ** This is the final formula used **