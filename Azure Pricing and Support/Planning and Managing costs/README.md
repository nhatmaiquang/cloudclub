# Planning and Managing costs

## The pricing calculator tool

The **_Pricing Calculator_** is a tool that helps you estimate the cost of Azure products. It displays Azure products in categories, and you choose the Azure products you need and configure them according to your specific requirements. Azure then provides a detailed estimate of the costs associated with your selections and configurations.

**Note**: The pricing calculator provides estimates, **_not_** actual price quotes. Actual prices may vary depending upon the date of purchase, the payment currency you are using, and the type of Azure customer you are.

Get a new estimate from the pricing calculator by adding, removing, or reconfiguring your selected products. You also can access pricing details, product details, and documentation for each product from the pricing calculator.

![alt text](https://training.future-proof.net/assets/courseware/v1/807e2cc4142a48f0f0a0516c0b83e1a9/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-pricing-calculator-estimate.png)

The options that you can configure in the pricing calculator vary between products, but basic configuration options include:

- **_Region_**. Lists the regions from which you can provision a product. Southeast Asia, central Canada, the western United States, and Northern Europe are among the possible regions available for some resources.

- **_Tier_**. Sets the type of tier you wish to allocate to a selected resource, such as Free Tier, Basic Tier, etc.

- **_Billing Options_**. Highlights the billing options available to different types of customer and subscriptions for a chosen product.

- **_Support Options_**: Allows you to pick from included or paid support pricing options for a selected product.

- **_Programs and Offers_**. Allows you to choose from available price offerings according to your customer or subscription type.

- **_Azure Dev/Test Pricing_**. Lists the available development and test prices for a product. Dev/Test pricing applies only when you run resources within an Azure subscription that is based on a Dev/Test offer.

**Note**: For more information about the pricing calculator, refer to [Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/).

## Total Cost of Ownership (TCO) Calculator

The **_Total Cost of Ownership_** (TCO) Calculator is a tool that you use to estimate cost savings you can realize by migrating to Azure. To use the TCO calculator, complete the three steps that the following sections explain.

![alt text](https://training.future-proof.net/assets/courseware/v1/ef06975222df92ab79b6444444070423/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-TCO-calculator-steps.png)

### Step 1: Define your workloads

Enter details about your on-premises infrastructure into the TCO calculator according to four groups:

- **_Servers_**. Enter details of your current on-premises server infrastructure.
- **_Databases_**. Enter details of your on-premises database infrastructure in the **Source** section. In the **Destination** section, select the corresponding Azure service you would like to use.
- **_Storage_**. Enter the details of your on-premises storage infrastructure.
- **_Networking_**. Enter the amount of network bandwidth you currently consume in your on-premises environment.

### Step 2: Adjust assumptions

Adjust the values of key assumptions that the TCO calculator makes, which might vary between customers. To improve the accuracy of the TCO calculator, you should adjust the values so they match the costs of your current on-premises infrastructure. The assumption values you can adjust include:

- Storage costs
- IT labor costs
- Hardware costs
- Software costs
- Electricity costs
- Virtualization costs
- Datacenter costs
- Networking costs
- Database costs

### Step 3: View the report

![alt text](https://training.future-proof.net/assets/courseware/v1/e462a2b413672af2aee5e342fb14429d/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-TCO-calculator-report.png)

The TCO calculator generates a detailed report based on the details you enter and the adjustments you make. The report allows you to compare the costs of your on-premises infrastructure with the costs using Azure products and services to host your infrastructure in the cloud.

**Note**: For more information about the TCO Calculator, refer to [Total Cost of Ownership (TCO) Calculator](https://azure.microsoft.com/en-us/pricing/tco/).

## Minimizing costs

The following best practice guidelines can help minimize your Azure costs.

### Perform cost analyses

Plan your Azure solution wisely. Carefully consider the products, services, and resources you need, and read the relevant documentation to understand how each of your choices are metered and billed. Additionally, you should calculate your projected costs by using the Azure Pricing and Total Cost of Ownership (TCO) calculators, only adding the products, services, and resources you need.

### Monitor usage with Azure Advisor

![alt text](https://training.future-proof.net/assets/courseware/v1/3549c9fd9b7446243b128aad6dd14a77/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-monitor-usage-costs.png)

In an efficient architecture, provisioned resources match the demand for those resources. The **_Azure Advisor_** feature identifies unused or under-utilized resources, and you can implement its recommendations by removing unused resources and configuring your resources to match your actual demand.

**Note**: For more information about Azure Advisor, refer to [Azure Advisor](https://azure.microsoft.com/en-us/services/advisor/).

### Use spending limits

Free trial customers and some credit-based Azure subscriptions can use the **_Spending Limits_** feature. Azure provides the Spending Limits feature to help prevent you from exhausting the credit on your account within each billing period. If you have a credit-based subscription and you reach your configured spending limit, Azure suspends your subscription until a new billing period begins.

The spending limit feature is not available for customers who aren't using credit-based subscriptions, such as Pay-As-You-Go subscribers.

**Note**: For more information on Azure spending limits, refer to [Understand Azure spending limit and how to remove it](https://docs.microsoft.com/en-us/azure/billing/billing-spending-limit).

**Note**: Azure spending limits are not the same as Subscription, Service, or Resource Group limits and quotas. For more information, refer to [Azure subscription and service limits, quotas, and constraints](https://docs.microsoft.com/en-us/azure/azure-subscription-service-limits).

### Use Azure Reservations

**_Azure Reservations_** offer discounted prices on certain Azure products and resources. To get a discount, you reserve products and resources by paying in advance. You can pre-pay for one year or three years of use of Virtual Machines, SQL Database Compute Capacity, Azure Cosmos Database Throughput, and other Azure resources.

Azure Reservations are only available to Enterprise or CSP customers and for Pay-As-You-Go subscriptions.

**Note**: For more information on Azure Reservations, refer to [What are Azure Reservations?](https://docs.microsoft.com/en-us/azure/billing/billing-save-compute-costs-reservations)

![alt text](https://training.future-proof.net/assets/courseware/v1/31602ac0d9d2eff2517a3a41cc6d4e1f/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-azure-reservations-savings.png)

### Choose low-cost locations and regions

The cost of Azure products, services, and resources can vary across locations and regions, and if possible, you should use them in those locations and regions where they cost less.

**Note**: Some resources are metered and billed according to how much outgoing network bandwidth they consume (egress). **_You should provision connected resources that are bandwidth metered in the same region_** to reduce egress traffic between them.

### Research available cost-saving offers

Keep up-to-date with the latest Azure customer and subscription offers, and switch to offers that provide the greatest cost-saving benefit.

Go to the [Azure Updates page](https://azure.microsoft.com/en-us/updates/) for information about the latest updates to Azure products, services, and features, as well as product roadmaps and announcements.

### Apply tags to identify cost owners

**_Tags_** help you manage costs associated with the different groups of Azure products and resources. You can apply tags to groups of Azure products and resources to organize billing data. For example, if you run several virtual machines for different teams, you can use tags to categorize costs by department, such as Human Resources, Marketing, or Finance, or by environment, such as Production or Test. Tags make it easy to identify groups that generate the biggest Azure costs, so you can adjust your spending accordingly.

**Note**: For more information about tags, refer to [Use tags to organize your Azure resources](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags).

## Azure Cost Management

**_Cost Management_** is an Azure product that provides a set of tools for monitoring, allocating, and optimizing your Azure costs.

![alt text](https://training.future-proof.net/assets/courseware/v1/292c7becf9ce3ef0d61fe40299c4e619/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-cost-vs-budget.png)

The main features of the Azure Cost Management toolset include:

- **_Reporting_**. Generate reports using historical data to forecast future usage and expenditure.
- **_Data enrichment_**. Improve accountability by categorizing resources with tags that correspond to real-world business and organizational units.
- **_Budgets_**. Create and manage cost and usage budgets by monitoring resource demand trends, consumption rates, and cost patterns.
- **_Alerting_**. Get alerts based on your cost and usage budgets.
- **_Recommendations_**. Receive recommendations to eliminate idle resources and to optimize the Azure resources you provision.
- **_Price_**. Free to Azure customers.

**Note**: For more information about Cost Management, refer to [Cost Management](https://azure.microsoft.com/en-us/services/cost-management/).
