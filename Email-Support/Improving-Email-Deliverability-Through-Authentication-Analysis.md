## **Improving Email Deliverability Through Authentication Analysis**

#### **Situation**

A customer using an external email provider could successfully send emails to most recipients but found that messages sent to larger groups of Gmail users were being blocked. They had already configured an SPF record and wanted to understand why the issue persisted.

#### **Task**

Determine whether the delivery issue originated from WordPress.com DNS, the external email provider, or Gmail's sender requirements, and provide a structured plan to improve email deliverability without making unsupported assumptions.

#### **Actions**

* Reviewed the customer's DNS configuration for existing email authentication records.
* Verified that an SPF record was present and identified that a DMARC record had not been configured.
* Explained how SPF, DKIM, and DMARC work together to authenticate outbound email and improve sender trust.
* Clarified that while DMARC is not always required for lower email volumes, implementing it could improve Gmail's confidence in the sending domain.
* Provided step-by-step guidance for adding a DMARC record through WordPress.com DNS.
* Recommended that the external email provider verify:

  * Reverse DNS (PTR) configuration.
  * DKIM signing.
  * Sending limits and policies.
* Suggested testing email delivery with a smaller group of Gmail recipients after the recommended changes were implemented.
* Offered WordPress.com Professional Email as an alternative option for improving deliverability without presenting it as the only solution.

#### **Result**

The investigation narrowed a broad email delivery problem into specific, actionable improvements involving both DNS authentication and the external email provider's configuration. Rather than continuing to focus solely on SPF, the customer received a comprehensive plan that included implementing DMARC and verifying the external email provider's reverse DNS (PTR), DKIM signing, and sending limits to improve Gmail deliverability.

#### **Skills Demonstrated**

* DNS troubleshooting
* Email authentication (SPF, DKIM, DMARC)
* Cross-provider diagnostics
* Customer education
* Clear technical communication


---
⬅️ **Return to [Email Support](./README.md)**
