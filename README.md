We’re going to see how to implement the Caesar cipher in Python.
The Caesar cipher, also known as the Caesar shift or Caesar's code, is one of the oldest and simplest encryption techniques in the history of cryptography.
The Caesar cipher is a type of substitution cipher. It involves shifting each letter in the plaintext by a fixed number of positions down or up the alphabet. 
This shift is known as the key. The original Caesar cipher uses a fixed shift of 3 positions down the alphabet. This means that A would be replaced by D, B by E, etc. 
It wraps around the alphabet, so Z becomes C with a shift of 3.
The Caesar cipher provided a basic level of security for its time, but it is relatively simple to break. 
With only 26 possible keys to try (since the key can be between 0 and 25), a brute-force attack can quickly reveal the plaintext (original message/text). 
