# Cryptography & Data Security

---

## 1. Security Standards
- **PCI DSS (Payment Card Industry Data Security Standard)** → Industry standard for securing **credit card information**.

<img src="https://github.com/user-attachments/assets/70ad7b57-a242-4563-818b-dd1b35318595" width="600" />

---

## 2. Classical Cryptography
- **Caesar Cipher** → Simple substitution cipher, shifts characters.

<img src="https://github.com/user-attachments/assets/75f1e4e8-3d97-4ac8-8fce-25b528a83c9a" width="600" />

---

## 3. Symmetric Encryption
- Same key used for **encryption** and **decryption**.  
- Example algorithms: **AES (Advanced Encryption Standard, 2001)**.  
- Efficient, but requires secure key sharing.  

<img src="https://github.com/user-attachments/assets/ca15c93e-d8c7-4359-9952-4439e2c6f383" width="600" />

---

## 4. Asymmetric Encryption
- Uses **public key** (encrypt) and **private key** (decrypt).  
- Solves key distribution problem.  
- Example: RSA, GPG.  

<img src="https://github.com/user-attachments/assets/0fa337d5-6ca9-4b71-9f37-a530f3a0638e" width="600" />

---

## 5. Key Exchange
- **Diffie-Hellman** → Securely exchange keys over insecure channels.  

<img src="https://github.com/user-attachments/assets/ca49bd44-f748-4d79-80a6-4ab03b123f8b" width="600" />

---

## 6. AES (Advanced Encryption Standard)
- Established **2001**.  
- Considered the modern encryption standard.  
- Used in SSL/TLS, VPNs, and disk encryption.

<img src="https://github.com/user-attachments/assets/27986e9e-e7be-4a9b-8cd2-39fe5e4426be" width="600" />

---

## 7. XOR Operation
- **Properties**: Commutative & Associative.  
- Used in many ciphers.

<img src="https://github.com/user-attachments/assets/7b6e0c6f-a891-454c-af35-70bc4a717ee8" width="600" />

---

## 8. Hashing
- **One-way function** (cannot decrypt).  
- Used for **integrity** and **password storage**.  
- Larger hash size → more secure.  
- **Hash collisions** occur when two inputs produce same hash.  

<img src="https://github.com/user-attachments/assets/efc37b3e-be82-4549-9cad-49f2b7e121ce" width="600" />

### Enhancements
- **Salting** → Add random data to passwords before hashing (prevents rainbow table attacks).  
- **Shadow File** → Stores password hashes in Linux systems.  

<img src="https://github.com/user-attachments/assets/413d44c7-7194-49af-bcd5-aa2d507da394" width="600" />

---

## 9. Password Cracking
- **Dictionary Attack** → Compare hashes to dictionary words.  
- **John the Ripper** → Popular hash-cracking tool.  
- **Base64** → Encoding (not encryption) → changes representation, not security.  

<img src="https://github.com/user-attachments/assets/e8c89db2-fd0e-4184-a359-f1f079b98574" width="600" />

---

## 10. GPG (GNU Privacy Guard)
- Tool for encryption & decryption.  
- Process:  
  1. Import key.  
  2. Decrypt message.  
- Supports **symmetric and asymmetric encryption**.  

<img src="https://github.com/user-attachments/assets/84b8e6f2-0f98-4572-a1bd-914145808d53" width="600" />

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

<img src="https://github.com/user-attachments/assets/bf4da805-ac1b-4335-afa7-66d587e1f806" width="600" />  
<img src="https://github.com/user-attachments/assets/1e1c55e6-bea1-46f2-8c8d-312b2ef70af0" width="600" />  
<img src="https://github.com/user-attachments/assets/89735e37-c87d-452f-9550-ac0d91da22c7" width="600" />  
<img src="https://github.com/user-attachments/assets/c3880e1e-3950-4dce-b2f7-047a569ea349" width="600" />  
<img src="https://github.com/user-attachments/assets/c719ca09-2ee9-43f9-976d-f6127ea90176" width="600" />  
<img src="https://github.com/user-attachments/assets/032ab461-7d57-4fbf-be32-21196aa90743" width="600" />





















