## **Resolving Admin Access Issue Through Domain Configuration**

#### **Situation**

A customer was unable to access their website's admin dashboard through their custom domain (`cartystore.com/wp-admin`). They believed that Jetpack had become disconnected and that WordPress.com was no longer recognizing the site. The inability to receive password reset emails reinforced the customer's belief that the website itself was broken.

#### **Task**

Determine the true cause of the admin access issue, verify whether it was related to Jetpack connectivity or another configuration problem, and provide the correct recovery path without leading the customer through unnecessary troubleshooting.

#### **Actions**

* Reviewed the website's hosting and domain configuration.
* Confirmed that the site was hosted on WordPress.com under its generated WordPress.com subdomain.
* Verified that the custom domain had never been configured as the site's Primary Domain.
* Determined that this configuration caused administrative requests to continue routing through the WordPress.com subdomain rather than the custom domain.
* Explained why the reported symptoms did not indicate a Jetpack connectivity issue.
* Guided the customer to access the admin dashboard using the WordPress.com subdomain.
* Provided instructions for setting the custom domain as the site's Primary Domain.
* Advised reconnecting Jetpack only if it remained necessary after correcting the domain configuration.
* Shared the relevant documentation explaining how to change the site's Primary Domain.

#### **Result**

The investigation identified the site's Primary Domain configuration as the root cause of the admin access issue, eliminating the need for unnecessary Jetpack troubleshooting. The customer received a clear recovery path that addressed the underlying configuration problem and corrected an initial, AI-generated assumption about the source of the issue.

#### **Skills Demonstrated**

* Account access troubleshooting
* Root cause analysis
* WordPress.com domain management
* Hosting architecture knowledge
* Correcting AI-generated assumptions

⬅️ **Return to [Identity & Security Access Recovery](./README.md)**
