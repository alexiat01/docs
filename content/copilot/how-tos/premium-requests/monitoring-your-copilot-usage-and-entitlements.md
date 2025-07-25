---
title: Monitoring your Copilot usage and entitlements
shortTitle: Monitor usage and entitlements
intro: 'Learn how you can monitor your monthly usage of {% data variables.product.prodname_copilot_short %} and get the most value out of your {% data variables.product.prodname_copilot_short %} plan.'
permissions: 'Individual users on a paid {% data variables.product.prodname_copilot_short %} plan can view their own usage and entitlements. For {% data variables.copilot.copilot_business_short %} or {% data variables.copilot.copilot_enterprise_short %} plans, organization admins and billing managers can view usage reports for members.'
versions:
  feature: copilot
topics:
  - Copilot
redirect_from:
  - /copilot/managing-copilot/managing-copilot-as-an-individual-subscriber/monitoring-usage-and-entitlements/monitoring-your-copilot-usage-and-entitlements
  - /copilot/managing-copilot/monitoring-usage-and-entitlements/monitoring-your-copilot-usage-and-entitlements
  - /copilot/managing-copilot/understanding-and-managing-copilot-usage/monitoring-your-copilot-usage-and-entitlements
  - /copilot/how-tos/monitoring-your-copilot-usage-and-entitlements
---

You can track your monthly usage of premium requests to help you get the most value from your {% data variables.product.prodname_copilot_short %} plan.

> [!NOTE]
> Premium request counters reset on the 1st of each month at 00:00:00 UTC.

## Viewing premium request usage

There are multiple ways to view your premium request usage:

* [View current usage directly within your IDE](#viewing-usage-in-your-ide)
* [View current usage in your {% data variables.product.prodname_copilot_short %} settings](#viewing-usage-in-your-copilot-settings)
* [Download a {% data variables.product.prodname_copilot_short %} premium request usage report](#downloading-a-copilot-premium-request-usage-report)

If you reach your limit for premium requests, you will be notified with a message in each of the {% data variables.product.prodname_copilot_short %} interfaces you use.

### Viewing usage in your IDE

If you're using {% data variables.product.prodname_copilot_short %} in an editor, you can view your usage directly in the editor. For example, in {% data variables.product.prodname_vscode %}, you can view information about features included in your plan, your progress towards any limits on your plan, and the date your allowance resets.

![Screenshot of the {% data variables.product.prodname_copilot_short %} current usage window in {% data variables.product.prodname_vscode %}. The "Code completions" and "Chat messages" bars indicate they are included with the user's {% data variables.product.prodname_copilot_short %} plan. The "Premium requests" bar indicates the user has used 99.5% of their allowance, and that it will reset on June 30, 2025.](/assets/images/help/copilot/vscode-current-usage.png)

You can access usage information in the following IDEs.

* **In {% data variables.product.prodname_vscode %}**, click the {% data variables.product.prodname_copilot_short %} icon ({% octicon "copilot" aria-hidden="true" aria-label="copilot" %}) in the status bar.
* **In {% data variables.product.prodname_vs %}**, click the {% data variables.product.prodname_copilot_short %} icon ({% octicon "copilot" aria-hidden="true" aria-label="copilot" %}) in the top right corner, then click **{% data variables.product.prodname_copilot_short %} Consumptions**.
* **In JetBrains IDEs**, click the {% data variables.product.prodname_copilot_short %} icon ({% octicon "copilot" aria-hidden="true" aria-label="copilot" %}) in the status bar, then select **View quote usage**.
* **In Xcode**, click the {% data variables.product.prodname_copilot_short %} icon ({% octicon "copilot" aria-hidden="true" aria-label="copilot" %}) in the menu bar.
* **In Eclipse**, click the {% data variables.product.prodname_copilot_short %} icon ({% octicon "copilot" aria-hidden="true" aria-label="copilot" %}) in the status bar at the bottom of Eclipse.

### Viewing usage in your {% data variables.product.prodname_copilot_short %} settings

You can view your premium request usage at any time from your {% data variables.product.prodname_copilot_short %} settings page on {% data variables.product.prodname_dotcom_the_website %}.

1. In the upper-right corner of any page on {% data variables.product.prodname_dotcom %}, click your profile picture.
1. Click **{% octicon "copilot" aria-hidden="true" aria-label="copilot" %} Your {% data variables.product.prodname_copilot_short %}**.
1. Under "Usage," view the "Premium requests" progress bar to see the percentage of your premium request quota used for the current month.

### Downloading a {% data variables.product.prodname_copilot_short %} premium request usage report

The premium request usage report includes all premium request usage, both within and beyond the allowance. By contrast, other metered billing reports only reflect costs for premium requests beyond the allowance.

>[!NOTE]
> For organizations and enterprises, only admins can download a usage report to understand {% data variables.product.prodname_copilot_short %} usage across their business. Individual members of the organization or enterprise cannot download the report for themselves.

1. Navigate to your account.

   In the upper-right corner of any page on {% data variables.product.prodname_dotcom %}, click your profile picture. Then:
   * For **individual accounts**, click **{% octicon "gear" aria-hidden="true" aria-label="gear" %} Settings**.
   * For **organizations**, click **{% octicon "organization" aria-hidden="true" aria-label="organization" %} Your organizations**.
   * For **enterprises**, click **Your enterprise**, or click **Your enterprises** then click the enterprise you want to view.
1. Navigate to your billing settings.
   * For **individual accounts**, in the "Access" section of the sidebar, click **{% octicon "credit-card" aria-hidden="true" aria-label="credit-card" %} Billing & Licensing**, then click **Overview**.
   * For **organizations**, click **{% octicon "gear" aria-hidden="true" aria-label="gear" %} Settings**. Then, in the "Access" section of the sidebar, click **{% octicon "credit-card" aria-hidden="true" aria-label="credit-card" %} Billing & Licensing**, then click **Usage**.
   * For **enterprises**, click **{% octicon "credit-card" aria-hidden="true" aria-label="credit-card" %} Billing & Licensing**, then click **{% octicon "graph" aria-hidden="true" aria-label="graph" %} Usage**.
1. Download a CSV usage report.
   * For **individual accounts**, in the sidebar under "Billing & Licensing," select **Usage**. Then click **Get usage report**, choose the report type and time frame, and click **Email me the report**.
   * For **organizations**, click the **Get usage report** drop down, then click **{% data variables.product.prodname_copilot_short %} premium requests usage report**.
   * For **enterprises**, click the **Get usage report** drop down, then click **{% data variables.product.prodname_copilot_short %} premium requests usage report**.

   The report contains {% data variables.product.prodname_copilot_short %} premium request usage from the past 45 days. Typically the report will be emailed to you within 30 minutes.

## Optimizing usage of premium requests

You can use the following strategies to maximize the value of your premium requests:

* **Choose the right model for the task**. Some models are better suited to different tasks. If you're using a premium request, you can strategically choose which model you use to get the best result from {% data variables.product.prodname_copilot_short %}. See [AUTOTITLE](/copilot/using-github-copilot/ai-models/choosing-the-right-ai-model-for-your-task).

* **Setting a budget**. Set a budget to track your overages and receive alerts when you reach 75%, 90%, or 100% of your budget. See [AUTOTITLE](/billing/managing-your-billing/preventing-overspending#managing-budgets-for-your-personal-account).

  >[!NOTE]
  > By default, all budgets are set to zero and premium requests over the allowance are rejected unless a budget has been created.

* **Monitor your usage regularly**. Check your usage in your {% data variables.product.github %} account settings to see how many premium requests you’ve used. This helps you plan how much you can use for the rest of the month.

* **Upgrade if needed**. If you find yourself consistently hitting your monthly allowance, consider upgrading to a plan with more premium requests included.

* **Avoid retrying large prompts unnecessarily**. Submitting the same long or complex prompt multiple times may use more premium requests. Try rephrasing or simplifying your request when needed.

## Managing premium request billing with multiple {% data variables.product.prodname_copilot_short %} licenses

If you have {% data variables.product.prodname_copilot_short %} licenses from multiple standalone organizations or enterprises, you must define which entity is charged for your use of premium requests. Until you define a billing entity, all premium requests you make will be rejected.

In the {% data variables.product.prodname_copilot_short %} feature settings for your personal account, a **Usage billed to** dropdown is displayed in the "Billing" section if you are assigned {% data variables.product.prodname_copilot_short %} licenses by two or more enterprises or standalone organizations.

![Screenshot of the {% data variables.product.prodname_copilot_short %} feature settings. The "Usage billed to" dropdown is open.](/assets/images/help/billing/copilot-billing-entity-dropdown.png)

You can change your billing entity selection at any time. All subsequent premium requests are billed to the newly selected entity.
