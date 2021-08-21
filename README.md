# Exposys Data labs -- Internship Project
Triple DES Encryption
# ENCRYPTION OF IMAGE USING TRIPLE DES

**PROJECT GOAL:  ENCRYPTION & DECRYPTION of IMAGE through Triple DES**

### Triple DES : Data encryption standard (DES)

In cryptography, Triple DES, officially the Triple Data Encryption Algorithm, is a symmetric-key block cipher, which applies the DES cipher algorithm three times to each data block.

Block sizes: 64 bits
Key sizes: 168, 112 or 56 bits (keying option 1, 2, 3 respectively)

Data encryption standard (DES) uses 56 bit key to encrypt any plain text which can be easily be cracked by using modern technologies. To prevent this from happening double DES and triple DES were introduced which are much more secured than the original DES because it uses 112 and 168 bit keys respectively. They offer much more security than DES.
 
**Triple DES:**
Triple DES is a encryption technique which uses three instance of DES on same plain text. It uses there different types of key choosing technique in first all used keys are different and in second two keys are same and one is different and in third all keys are same.

Triple-DES encryption uses a triple-length DATA key comprised of three 8-byte DES keys to encipher 8 bytes of data using this method:

Encipher the data using the first key
Decipher the result using the second key
Encipher the second result using the third key
The procedure is reversed to decipher data that has been triple-DES enciphered:

Decipher the data using the third key
Encipher the result using the second key
Decipher the second result using the first key


