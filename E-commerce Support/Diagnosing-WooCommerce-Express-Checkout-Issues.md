## **Diagnosing WooCommerce Express Checkout Issues**

#### **Situation**

A WooCommerce merchant reported inconsistent checkout behavior across their store. Some products displayed Google Pay without showing prices, Google Pay failed to launch checkout on certain products, while PayPal continued functioning normally. The customer had never knowingly enabled Google Pay and believed there was a problem with their payment configuration.

#### **Task**

Determine whether the inconsistent checkout behavior was caused by the payment gateway, product configuration, or WooCommerce Payments Express Checkout, and provide a solution that preserved the customer's existing checkout setup.

#### **Actions**

* Compared checkout behavior across multiple products to identify inconsistencies.
* Distinguished payment gateway behavior from individual product configuration issues.
* Verified that products and their pricing were configured correctly.
* Checked pricing across all product variations to rule out missing variation prices.
* Reviewed the WooCommerce Payments Express Checkout configuration.
* Identified that Google Pay had been automatically enabled through WooCommerce Payments Express Checkout.
* Explained how Express Checkout differs from the standard payment gateway and why Google Pay could appear independently.
* Guided the customer to disable only the Google Pay Express Checkout option rather than replacing or disabling the entire WooCommerce Payments gateway.
* Recommended clearing cached data and testing the checkout experience in an incognito browser session to verify the changes.

#### **Result**

The investigation identified that the inconsistent checkout behavior resulted from a combination of incomplete product configuration and Google Pay being automatically enabled through WooCommerce Payments Express Checkout. The customer received targeted configuration changes that preserved the existing payment gateway while eliminating the unwanted checkout behavior, avoiding unnecessary payment gateway replacement and providing a structured workflow for validating the fix.

#### **Skills Demonstrated**

* WooCommerce troubleshooting
* Payment gateway diagnostics
* Root cause analysis
* Customer education
* Structured troubleshooting

---
⬅️ **Return to [E-commerce Support](./README.md)**
