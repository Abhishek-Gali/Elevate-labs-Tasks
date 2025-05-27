# Phishing Email Analysis (Task 2)

## 🔍 Target URL
- https://edulab.co.zw/wp-content/docs/IKAOUEdAU2SaUsXU4EUapsioeqYuI5eTroMoeY1ao5oWDoLUeOeO1I7UAEoAoOaVMUe2eEuoN8EADamOGIeAkAlaEoEEFi96IEaa7EIi8iUoeOa68TGiApiuw5UaNEu4Uu3a5EPeOi9Ooi3Euiq61azIxCga5EOi2u7xO6A1inH/Y3plY2guYnJhbmNoQHBrb2JwLnBs



---

## 🧪 Objective
To investigate and identify phishing indicators in a suspicious email link using free tools and manual inspection methods.

---

## 🛠 Tools Used

- **PhishTank** — To verify phishing status of the URL.
- **MxToolbox** — For SSL certificate inspection.
- **EasyDMARC** — To check URL redirection and risk level.
- **Browser Inspection** — For identifying phishing behavior visually.

---

## ⚠️ Key Findings

### 1. **Confirmed Phishing Link**
- Submitted to PhishTank and verified as an active phishing attempt.

### 2. **SSL Certificate Deception**
- SSL certificate is valid, but the certificate issuer is unrelated to the claimed brand.
- Attackers use valid certs to build trust.

### 3. **Suspicious URL Structure**
- Long and encoded URL path likely designed to obfuscate malicious intent.
- EasyDMARC flagged the URL as “Suspicious”.

### 4. **Credential Harvesting Form**
- The link opens a fake login form asking for email and password.
- Domain (`edulab.co.zw`) does not match the supposed brand (`pkobp.pl`).
- No legitimate authentication flow or branding.

---

## 📎 Screenshots

- `mxtoolbox_ssl.png` — Shows SSL certificate details.
- `phishtank_verification.png` — URL verified as phishing.
- `easydmarc_suspicious.png` — EasyDMARC flagged the URL.
- `screenshot_login_form.png` — Screenshot of phishing login form.

---

## 📘 Conclusion

This task demonstrates how phishing sites can:
- Mimic legitimate services
- Use valid SSL certificates to trick users
- Attempt to steal credentials via fake forms

Understanding these traits is essential to identifying and defending against phishing attacks in real-world scenarios.

---

## 📤 Submission
All findings, screenshots, and this report have been uploaded as part of the internship assignment.
