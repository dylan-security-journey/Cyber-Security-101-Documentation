# Cryptography & Data Security

---

## 1. Security Standards
- **PCI DSS (Payment Card Industry Data Security Standard)** → Industry standard for securing **credit card information**.

![PCI DSS](https://github.com/user-attachments/assets/70ad7b57-a242-4563-818b-dd1b35318595)

---

## 2. Classical Cryptography
- **Caesar Cipher** → Simple substitution cipher, shifts characters.

![Caesar Cipher](https://github.com/user-attachments/assets/75f1e4e8-3d97-4ac8-8fce-25b528a83c9a)

---

## 3. Symmetric Encryption
- Same key used for **encryption** and **decryption**.  
- Example algorithms: **AES (Advanced Encryption Standard, 2001)**.  
- Efficient, but requires secure key sharing.  

![Symmetric Encryption](https://github.com/user-attachments/assets/ca15c93e-d8c7-4359-9952-4439e2c6f383)

---

## 4. Asymmetric Encryption
- Uses **public key** (encrypt) and **private key** (decrypt).  
- Solves key distribution problem.  
- Example: RSA, GPG.  

![Asymmetric Encryption](https://github.com/user-attachments/assets/0fa337d5-6ca9-4b71-9f37-a530f3a0638e)

---

## 5. Key Exchange
- **Diffie-Hellman** → Securely exchange keys over insecure channels.  

![Diffie-Hellman](https://github.com/user-attachments/assets/ca49bd44-f748-4d79-80a6-4ab03b123f8b)

---

## 6. AES (Advanced Encryption Standard)
- Established **2001**.  
- Considered the modern encryption standard.  
- Used in SSL/TLS, VPNs, and disk encryption.

![AES](https://github.com/user-attachments/assets/27986e9e-e7be-4a9b-8cd2-39fe5e4426be)

---

## 7. XOR Operation
- **Properties**: Commutative & Associative.  
- Used in many ciphers.

![XOR](https://github.com/user-attachments/assets/7b6e0c6f-a891-454c-af35-70bc4a717ee8)

---

## 8. Hashing
- **One-way function** (cannot decrypt).  
- Used for **integrity** and **password storage**.  
- Larger hash size → more secure.  
- **Hash collisions** occur when two inputs produce same hash.  

![Hash Example](https://github.com/user-attachments/assets/efc37b3e-be82-4549-9cad-49f2b7e121ce)

### Enhancements
- **Salting** → Add random data to passwords before hashing (prevents rainbow table attacks).  
- **Shadow File** → Stores password hashes in Linux systems.  

![Shadow File](https://github.com/user-attachments/assets/413d44c7-7194-49af-bcd5-aa2d507da394)

---

## 9. Password Cracking
- **Dictionary Attack** → Compare hashes to dictionary words.  
- **John the Ripper** → Popular hash-cracking tool.  
- **Base64** → Encoding (not encryption) → changes representation, not security.  

![Dictionary Attack](https://github.com/user-attachments/assets/e8c89db2-fd0e-4184-a359-f1f079b98574)

---

## 10. GPG (GNU Privacy Guard)
- Tool for encryption & decryption.  
- Process:  
  1. Import key.  
  2. Decrypt message.  
- Supports **symmetric and asymmetric encryption**.  

![GPG Example](https://github.com/user-attachments/assets/84b8e6f2-0f98-4572-a1bd-914145808d53)

---

## 11. Key Takeaways
- **Encryption vs Hashing**:  
  - Encryption = **two-way** (decryptable with key).  
  - Hashing = **one-way** (cannot be reversed).  
- **Best Practices**:  
  - Use **AES** for encryption.  
  - Use **SHA-256+ with salt** for hashing passwords.  
  - Avoid outdated algorithms (MD5, DES, RC4).  
  - Replace cleartext protocols (Telnet, FTP) with secure versions.  

![Summary](https://github.com/user-attachments/assets/bf4da805-ac1b-4335-afa7-66d587e1f806)

<img width="2010" height="611" alt="image" src="https://github.com/user-attachments/assets/1e1c55e6-bea1-46f2-8c8d-312b2ef70af0" />

<img width="1164" height="470" alt="image" src="https://github.com/user-attachments/assets/89735e37-c87d-452f-9550-ac0d91da22c7" />

<img width="1157" height="536" alt="image" src="https://github.com/user-attachments/assets/c3880e1e-3950-4dce-b2f7-047a569ea349" />

<img width="817" height="359" alt="image" src="https://github.com/user-attachments/assets/c719ca09-2ee9-43f9-976d-f6127ea90176" />

<img width="1484" height="615" alt="image" src="https://github.com/user-attachments/assets/032ab461-7d57-4fbf-be32-21196aa90743" />




















