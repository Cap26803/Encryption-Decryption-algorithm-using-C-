# Encryption-Decryption-using-CPP
Encrypt any text with ease, and decrypt with a unique key. 

![image](https://github.com/Cap26803/Encryption-Decryption-using-CPP/assets/106472393/3d6cce9a-6cb1-4dd1-a166-0cc0f4b13baf)

# Class EncryptorDecryptor

**Description:** This is an abstract base class that defines the interface for encryption and decryption operations. It declares two pure virtual functions, `encrypt` and `decrypt`, which are meant to be overridden by derived classes.

**Responsibilities:** Provides an interface for encryption and decryption operations.

---

# Class XORCipher

**Description:** This derived class inherits from `EncryptorDecryptor` and implements encryption and decryption using the XOR cipher algorithm with a secret key.

**Responsibilities:** Performs encryption and decryption using the XOR cipher algorithm.

---

# Class CommonAlgorithm

**Description:** This derived class also inherits from `EncryptorDecryptor` and implements encryption and decryption using a common algorithm where each character of the message is shifted by 1.

**Responsibilities:** Performs encryption and decryption using a common algorithm.
