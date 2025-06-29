# Phishing Email Analysis Report

**Sender Analysis:**
- Display name is “PayPal Support” but the actual email address is support@paypa1.com (note the misspelled “paypal”).

**Header Analysis:**
- (Example) SPF failed; sender IP does not match PayPal’s known mail servers.

**Suspicious Links:**
- Link text: "Login to PayPal"
- Actual URL: http://malicious-site.com/paypal-login (hover reveals mismatch)

**Language Analysis:**
- Urgent wording like "Immediate Action Required" and "Failure to act within 24 hours".

**Spelling/Grammar Errors:**
- “acount” instead of “account” in the email body.

**Attachments:**
- Statement.pdf is included, which is suspicious as unexpected attachments often deliver malware.

**Summary of Indicators:**
✅ Spoofed sender email  
✅ Urgent and threatening language  
✅ Mismatched URL  
✅ Poor spelling/grammar  
✅ Suspicious attachment
