## **Resolving a Domain Mapping Conflict**

#### **Situation**
A developer was attempting to connect a subdomain to WordPress.com, but the connection wizard repeatedly reported that an existing CNAME record already existed. The customer believed the issue was caused by a stale DNS cache within WordPress.com.

#### **Task**
Determine whether the connection failure was caused by a DNS caching issue or a domain configuration conflict, and identify the appropriate corrective action before considering escalation.

#### **Actions**
* Reviewed the website's existing domain configuration.
* Verified that the root domain was already mapped to the site.
* Confirmed with the customer that only the subdomain was intended to remain connected.
* Determined that the existing root domain mapping, rather than stale DNS, was preventing the subdomain from being connected.
* Outlined the corrective steps to remove the unnecessary root domain mapping and reconnect only the required subdomain.
* Recommended escalating the issue only if the connection problem persisted after the configuration change.

#### **Result**
The investigation identified a domain mapping conflict as the true cause of the connection failure, eliminating the need for unnecessary infrastructure troubleshooting or escalation. The customer received a clear path to resolve the issue by correcting the domain configuration rather than pursuing a DNS cache investigation.

#### **Skills Demonstrated**
* DNS troubleshooting
* Domain mapping expertise
* Developer communication
* Systematic root cause analysis

---
⬅️ **Return to [Domains and DNS](./README.md)** 

