# Crack Simulator

## Crack-Time

### Layers to get crack time:

- Entropy (bits) [ ***How many possibilities exists*** ]
- Guesses required [ ***How many tries attacker must make***]
- Guesses per second [ ***Attacker hardware speed*** ]

### Formula
> **time = guesses required / guesses per secound**
 
## Steps Used:

### Step-1:
- Convert Entropy to Number of Guesses
    - Total possible passwords ≈ 2^(entropy)
### Step-2:
Attack speed depends on scenario:

**🟢 Offline Attack (hash cracking)**

- Attacker has password hash and can try guesses freely.

- Speed is extremely high:

- basic machine → millions/sec

- GPU → billions/sec

- cluster → trillions/sec

**🔴 Online Attack (login attempts)**

- Limited by server defenses:

- rate limits

- lockouts

- captchas

- Speed is very low:

- 1 to 10 guesses/sec typical

### Step-3:
Core formula:
>time_seconds = total_guesses ÷ guesses_per_second
