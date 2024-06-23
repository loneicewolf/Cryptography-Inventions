# Cryptography-Inventions
Me &amp; My Friends Ideas in Cryptograpgy

NOTE this will only be ideas, not practical things, cuz (one does not invent own crypto) but interesting ideas only. `^_^`

# A friends idea 1
- TODO: Verify this [ ] 
```md
# Internal Inner Workings:
## First Draft
- password is stored in this format: "`{seed-32bit suppose}:{n-byte pattern}`"
-  `32`-bit key is the seed, ( `4` byte unsigned int = the seed to the sub keys grid)
  - and the `32` bit pattern is a sequence of n bytes, `1 byte` being one unsigned number randing 0-255
- The  `n-byte` pattern is repeated upto the length of the non-encrypted data
- Each letter of input string `a` is simply: `a[i] = sb[pattern[i]][a[i]]`

```
