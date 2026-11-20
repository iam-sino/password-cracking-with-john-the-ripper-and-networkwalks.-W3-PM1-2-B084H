# password cracking with john-the-ripper and networkwalks. W3-PM1-2-B084H
Hands on cybersecurity practical documenting password hash extraction, PDF password cracking, dictionary attacks, and password recovery using John the Ripper (JTR), Johnny GUI, and NetworkWalks tools.



## 1. Project Overview

This project documents a hands-on cybersecurity practical involving password recovery using two different approaches:

1. John the Ripper (JTR) through Johnny GUI.
2. NetworkWalks password cracking tools.

The exercises focused on extracting password hashes from encrypted PDF files, performing dictionary attacks, and successfully recovering the corresponding passwords.

Screenshots are included to demonstrate each stage of the practical.

## 2. Objectives

- Understand password hashing and password-protected PDF files.
- Extract PDF password hashes.
- Configure and use John the Ripper.
- Perform dictionary-based password attacks.
- Use NetworkWalks hash extraction and password-cracking tools.
- Analyse successful password recovery results.
- Document practical activities with screenshots.

## 3. Tools and Technologies

| Tool | Purpose |
|---|---|
| Johnny GUI | Graphical interface for John the Ripper |
| John the Ripper Jumbo | Password auditing and recovery |
| OnlineHashCrack | PDF hash extraction |
| NetworkWalks Hash Calculator | Hash generation and PDF hash extraction |
| NetworkWalks Password Cracker | Dictionary-based password recovery |

---

# 4. Practical One: John the Ripper (JTR)

## Step 1: Configuring Johnny

Johnny GUI was launched and configured to use the John the Ripper Jumbo executable.

The application successfully detected the installed JTR version.

**Evidence: JTR i.png**

![Johnny Configuration](JTR%20i.png)

## Step 2: Extracting the PDF Hash

A password-protected PDF training file was submitted to OnlineHashCrack's PDF hash extractor.

The tool successfully extracted the PDF password hash.

The extracted hash was then prepared for use with John the Ripper.

**Evidence: JTR ii.png**

![PDF Hash Extraction](JTR%20ii.png)

## Step 3: Password Recovery

The extracted PDF hash was loaded into Johnny GUI.

John the Ripper processed the hash and successfully recovered the password.

**Recovered Password:** `good-luck`

**Evidence: JTR iii.png**

![JTR Recovery Result](JTR%20iii.png)

## Practical One Result

The password recovery exercise was successful.

This demonstrated how an extracted PDF hash can be processed using John the Ripper to recover a password.

---

# 5. Practical Two: NetworkWalks Academy

## Step 1: Extracting the PDF Hash

The NetworkWalks Hash Calculator was opened.

The encrypted PDF training file was uploaded, and the tool successfully extracted a compatible PDF password hash.

**Evidence: NW i.png**

![NetworkWalks Hash Calculator](NW%20i.png)

## Step 2: Setting Up the Dictionary Attack

The extracted PDF hash was entered into the NetworkWalks Password Cracker.

The built-in dictionary option was selected.

The tool displayed a built-in wordlist containing 100 candidate passwords.

**Evidence: NW ii.png**

![Dictionary Attack Setup](NW%20ii.png)

## Step 3: Executing the Attack

The dictionary attack was initiated.

The tool tested candidate passwords against the extracted hash until it identified a match.

The attack successfully recovered the password.

**Recovered Password:** `password1`

The results screen showed a successful match after 91 of 100 attempts.

**Evidence: NW iii.png**

![Successful Password Recovery](NW%20iii.png)

## Practical Two Result

The dictionary attack successfully recovered the PDF password.

This demonstrated how dictionary attacks use predefined password lists to identify matching passwords.

---

# 6. Capture The Flag (CTF) Results

During the practical exercises, NetworkWalks training flags were successfully captured.

**Flag One:**

`nw{cybersecurity_flag_captured_2608}`

**Flag Two:**

`nw{networkwalks_flag1_is_270021_1}`

The completion screenshots are included as evidence.

**Evidence: JTR RESULT.png**

![CTF Completion](JTR%20RESULT.png)

**Evidence: RESULT.png**

![Flag Capture](RESULT.png)

---

# 7. Summary of Results

| Practical | Tool | Result |
|---|---|---|
| 1 | John the Ripper / Johnny | Successful |
| 2 | NetworkWalks | Successful |
| 2 | Dictionary Attack | Successful |
| 2 | CTF Flag Capture | Successful |

### Recovered Passwords

- JTR: `good-luck`
- NetworkWalks: `password1`

Both exercises were completed successfully.

---

# 8. Key Learning Outcomes

Through these practical exercises, I gained hands-on experience in:

- Understanding password hashes.
- Extracting password hashes from encrypted PDF files.
- Configuring John the Ripper through Johnny GUI.
- Understanding dictionary-based password attacks.
- Using wordlists for password auditing.
- Analysing password recovery results.
- Documenting cybersecurity practical exercises.
- Understanding the importance of strong passwords.

## 9. Conclusion

This practical provided valuable hands-on experience with password recovery techniques using John the Ripper and NetworkWalks Academy tools.

Both exercises were completed successfully, demonstrating the importance of understanding password security, hash extraction, dictionary attacks, and password auditing.

The screenshots included in this repository provide evidence of the processes performed and their successful outcomes.

## 10. Ethical Considerations

All activities documented in this repository were performed as part of cybersecurity training.

Password auditing and recovery techniques should only be used on files and systems owned by the tester or where explicit authorisation has been granted.

This repository is intended for educational purposes and responsible cybersecurity practice.
