# Shivayogi-V-Hublikar
<img width="940" height="453" alt="image" src="https://github.com/user-attachments/assets/b5d98163-1fb2-44d2-b696-f8f3c369723f" />



Phishing Email Investigation Report
1. Sample Phishing Email
 Subject: Your account will be suspended – Immediate Action Required!
From: support@netflix-verification.com
Body:
“Dear Customer,
Your Netflix account has been flagged for suspicious activity. You must verify your account immediately or it will be suspended.
Click here to verify: http://netflix-security-check.com/login
Thank you,
Netflix Support Team.”
________________________________________
2. Examine Sender's Email Address
•	 Sender: support@netflix-verification.com
•	✅ Legitimate domain: netflix.com
•	❌ Spoofed domain: netflix-verification.com — this is not an official Netflix domain.
________________________________________
3. Check Email Headers (Use: https://mxtoolbox.com/EmailHeaders.aspx)
•	Analyze Return-Path, Received, and Reply-To fields.
•	 Header Discrepancy Found:
o	Return-Path: randomemail@xyz.ru
o	Reply-To: netflixhelp@gmail.com
•	❌ Mismatch indicates spoofing or relay via another domain.
________________________________________
4. Identify Suspicious Links or Attachments
•	Link in email: http://netflix-security-check.com/login
•	❗ Suspicious because:
o	Not HTTPS
o	Domain unrelated to netflix.com
•	No attachment found in this sample.
________________________________________
5. Urgent or Threatening Language
•	Examples from email:
o	“Your account will be suspended”
o	“Immediate action required”
o	“Verify immediately”
•	Designed to create panic and push quick action.
________________________________________
6. Mismatched URLs
•	Displayed URL: Click here to verify
•	Actual URL (hover): http://netflix-security-check.com/login
•	❌ Mismatch between expected Netflix domain and actual link.
________________________________________
7. Spelling or Grammar Errors
•	Errors Noticed:
o	“Your Netflix account has been flagged…” → passive voice, vague.
o	Overuse of formal words without personalization.
o	Awkward phrasing such as “verify your account immediately or it will be suspended.”
________________________________________
8. Summary of Phishing Traits Identified
Trait	Observed?	Details
Spoofed sender address	✅	netflix-verification.com
Mismatched domain/URL	✅	Hover link different from expected
Urgent or threatening language	✅	“Immediate action required”
Poor grammar or formatting	✅	Awkward sentence structure
Suspicious links	✅	Unsecure HTTP, fake domain
Suspicious email headers	✅	Mismatched return-path and reply-to


