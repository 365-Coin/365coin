365Coin
==============



Technical Information

+ 113,225 coins
+ 0.00069445coins rewarded per block
+ 60 second block times
+ difficulty retargeting using Kimoto Gravity Well


-----------------------------

+ replacement of ECDSA with Schnorr signing
+ use of secp256r1 curve over secp256k1
+ requirement for public key when verifying transactions
+ modification to RPC interface s.t. public keys are Base64 encoded

Modifications to the RPC API
+ verifymessage <365oinaddress> <publickey> <signature> <message>

Forked from Bitcoin reference wallet 0.8.5 and Blakecoin

License
------

365Coin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
