# phishing-email-analysis
Analysis of sample phishing emails: header and link inspection, threat-intelligence lookups, and incident reports with verdicts and recommended responses.  Topics to add: soc, phishing, email-security, threat-intelligence, incident-response, blue-team, cybersecurity
Phishing Email Analysis and Incident Report

Author: Inba Thamilan M Tools: Email header analysis, VirusTotal, URLScan, AbuseIPDB Status: In progress (started November 2026)

Objective

Analyse sample phishing emails the way a SOC L1 analyst would: check the sender and headers, inspect links and attachments safely, look up indicators of compromise (IOCs) in threat-intelligence tools, and write a short incident report with a verdict and recommended response.

Safety rules
Only sample emails from public phishing collections are used.
Links are never clicked and attachments are never opened on my main machine; indicators are checked using the online tools instead.
No personal data is included in the write-up.
Method for each email
Save the email and note its source.
Check the sender: display name versus actual address, look-alike domain, reply-to mismatch.
Read the headers: originating IP and SPF, DKIM and DMARC results.
Inspect where each link really points, without clicking.
Look up URLs, domains, file hashes and IP addresses on VirusTotal, URLScan and AbuseIPDB.
Decide a verdict (Phishing, Suspicious or Legitimate) and write the report.
Plan and progress
 Collect 4 or 5 sample phishing emails
 Analyse each email using the method above
 Write one incident report per email
 Add a summary table of all cases
 Add a short summary of lessons learned
Results

Incident reports and the summary table will be added here as each email is analysed.

Incident report format

Each report will include:

Case ID, email source, subject and sender
Originating IP and SPF, DKIM, DMARC results
Suspicious indicators found
IOC table (type, value, tool checked, result), with URLs written in defanged form
Verdict and recommended response
Skills practised

Email header analysis, phishing identification, IOC lookup with threat-intelligence tools, incident reporting.
