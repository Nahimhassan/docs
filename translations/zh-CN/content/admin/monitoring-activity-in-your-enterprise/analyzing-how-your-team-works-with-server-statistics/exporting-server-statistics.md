---
title: Exporting Server Statistics
shortTitle: Export Server Statistics
intro: 'You can use your own tools to analyze your {% data variables.product.prodname_ghe_server %} usage over time by downloading your {% data variables.product.prodname_server_statistics %} metrics in a CSV or JSON file.'
versions:
  feature: server-statistics
redirect_from:
  - /early-access/github/analyze-how-your-team-works-with-server-statistics/exploring-server-statistics
---

{% data reusables.server-statistics.release-phase %}

You can download up to the last 365 days of {% data variables.product.prodname_server_statistics %} data in a CSV or JSON file. 此数据（包括有关存储库、问题和拉取请求的汇总指标）可以帮助您预测组织的需求，了解团队的工作方式，并显示您从 {% data variables.product.prodname_ghe_server %} 中获得的价值。

Before you can download this data, you must enable {% data variables.product.prodname_server_statistics %}. 更多信息请参阅“[为企业启用 {% data variables.product.prodname_server_statistics %}](/admin/configuration/configuring-github-connect/enabling-server-statistics-for-your-enterprise)”。

To preview the metrics available to download, see "[About {% data variables.product.prodname_server_statistics %}](/admin/monitoring-activity-in-your-enterprise/analyzing-how-your-team-works-with-server-statistics/about-server-statistics)."

To download these metrics, you must be an enterprise owner or organization owner on {% data variables.product.prodname_ghe_cloud %}.
  - If {% data variables.product.product_location %} is connected to an enterprise account on {% data variables.product.prodname_ghe_cloud %}, see "[Downloading metrics from your enterprise account](#downloading-metrics-from-your-enterprise-account)."
  - If {% data variables.product.product_location %} is connected to an organization on {% data variables.product.prodname_ghe_cloud %}, see "[Downloading metrics from your organization](#downloading-metrics-from-your-organization)."

要了解有关 {% data variables.product.prodname_github_connect %} 的更多信息，请参阅“[关于 {% data variables.product.prodname_github_connect %}](/admin/configuration/configuring-github-connect/about-github-connect)”。

## Downloading metrics from your enterprise account

1. 在 {% data variables.product.prodname_ghe_cloud %} 的右上角，单击您的个人资料照片，然后单击 **Your enterprises（您的企业）**。 ![Drop down menu with "Your enterprises" option](/assets/images/help/enterprises/enterprise-admin-account-settings.png)

2. Next to your desired enterprise account, click **Settings**. ![Settings button next to Enterprise admin account](/assets/images/help/enterprises/enterprise-admin-account-settings-button.png)

3. On the left, click **GitHub Connect**. ![GitHub Connect option under enterprise admin account](/assets/images//help/enterprises/enterprise-admin-github-connect.png)

{% data reusables.server-statistics.csv-download %}

## Downloading metrics from your organization

1. In the top-right corner of {% data variables.product.prodname_ghe_cloud %}, click your profile photo, then click **Your organizations**. ![Drop down menu with "Your organizations" option](/assets/images/help/enterprises/github-enterprise-cloud-organizations.png)

2. In the list of organizations, next to the organization that's connected to {% data variables.product.product_location %}, click **Settings**. ![Settings button next to {% data variables.product.prodname_ghe_cloud %} organization](/assets/images/help/enterprises/settings-for-ghec-org.png)

3. On the left, click **GitHub Connect**. ![GitHub Connect option in an organization account settings left sidebar](/assets/images/help/enterprises/github-connect-option-for-ghec-org.png)

{% data reusables.server-statistics.csv-download %}
