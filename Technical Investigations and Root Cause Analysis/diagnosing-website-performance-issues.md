# Diagnosing Website Performance Issues

## Situation
A customer reported that their WordPress.com website loaded quickly over mobile data but was consistently slow when accessed through fixed broadband connections across multiple ISPs in Turkey.
Previous troubleshooting had already ruled out common website-level causes, including Jetpack Site Accelerator configuration. The issue had become part of a longer-running investigation involving WordPress.com engineering because the symptoms suggested ISP-specific traffic handling rather than a problem with the customer's website.

## Task
Review the existing investigation, determine whether new evidence pointed to improvements or remaining infrastructure issues, avoid disrupting the customer's production website with unnecessary troubleshooting, and provide engineering with actionable diagnostic feedback.

## Actions
* Reviewed the complete support history to avoid repeating troubleshooting that had already been performed.
* Recognized that the investigation had progressed beyond normal site-level diagnostics and formed part of a broader infrastructure investigation.
* Analyzed the customer's latest testing results and identified that recent infrastructure changes had partially improved performance.
* Determined that:
text-heavy pages were now loading normally,
image-heavy pages continued to experience delays,
membership login functionality remained affected.
* Recommended re-enabling Jetpack Site Accelerator after it had previously been disabled solely for diagnostic purposes, explaining that it could once again provide CDN and image optimization benefits.
* Deliberately avoided recommending that the customer disable their production membership plugin, recognizing that doing so would unnecessarily disrupt live users without producing meaningful diagnostic value.
* Consolidated the customer's findings into a structured engineering update, clearly distinguishing resolved behaviour from remaining issues to support ongoing infrastructure analysis.

## Result
* The customer confirmed that recent platform changes had improved overall performance, with text-based pages loading correctly while the remaining issues were isolated to image-heavy content and membership login functionality.
* The investigation provided engineering with high-quality diagnostic evidence demonstrating that the problem was not fully resolved but had narrowed significantly. Rather than restarting troubleshooting or making unnecessary changes to the customer's live website, the support interaction advanced a long-running infrastructure investigation by identifying exactly which components continued to be affected.

## Skills Demonstrated
* Infrastructure troubleshooting
* CDN optimization
* Networking fundamentals
* Root cause analysis
* Engineering collaboration
* Technical communication
* Customer expectation management
* Long-running incident management


⬅️ **Return to [Technical Investigations And Root Cause Analysis](./README.md)**
