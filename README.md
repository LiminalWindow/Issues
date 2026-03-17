# Issues
Permanent archive of Liminal Window magazine issues, including publication files and cryptographic verification records.

# Liminal Window — Issue Archive

This repository serves as the permanent public archive for issues of *Liminal Window*.

Each issue includes:

• The original publication file  
• A cryptographic SHA256 verification hash  
• A blockchain timestamp (OpenTimestamps proof)

These records allow anyone to verify the authenticity and integrity of the publication files.

---

## Issue 1

**Liminal Window — Vol. 1, No. 1**  
*State of Intent*

Publication Date: March 15, 2026

Files:

• Liminal-Window- Vol.1-No.1.pdf  
• Liminal-Window- Vol.1-No.1.pdf.ots  
• ISSUE-01-VERIFICATION.txt

---

## Verification

Windows:
certutil -hashfile "Liminal-Window- Vol.1-No.1.pdf" SHA256


Compare the output to the recorded SHA256 value.

If the values match, the file is authentic.
