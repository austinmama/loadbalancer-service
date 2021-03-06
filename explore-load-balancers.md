---

copyright:
  years: 2017, 2018
lastupdated: "2018-08-07"

keywords: load balancer, compare, explore

subcollection: loadbalancer-service

---

{:shortdesc: .shortdesc}
{:new_window: target="_blank_"}
{:codeblock: .codeblock}
{:pre: .pre}
{:screen: .screen}
{:tip: .tip}
{:note: .note}
{:important: .important}
{:download: .download}
{:row-headers .row-headers}

# Exploring IBM load balancers
{: #explore}

IBM© Cloud offers several load balancing solutions to choose from. The table below compares the load balancing solutions to help you choose the one that's right for you. To learn more about the individual offering, click its name in the table.

Scroll to the right to view the rest of the table!
{: important}


|        | [{{site.data.keyword.loadbalancer_full}}](/docs/loadbalancer-service?topic=loadbalancer-service-getting-started)| [Local Load Balancer](/docs/local-load-balancer?topic=local-load-balancer-alb-end-of-marketing-announcement) <sup>1</sup>| [Local Load Balancer](/docs/local-load-balancer?topic=local-load-balancer-alb-end-of-marketing-announcement) (Dedicated) <sup>1</sup>| [Citrix NetScaler](/docs/citrix-netscaler-vpx?topic=citrix-netscaler-vpx-getting-started) VPX/MPX (Standard)| [Citrix NetScaler](/docs/citrix-netscaler-vpx?topic=citrix-netscaler-vpx-getting-started) VPX/MPX (Platinum) |
|------- | :------: | :------: | :------: | :------: | :------: |
|**Public VIP**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Private VIP**|![Checkmark icon](../../icons/checkmark-icon.svg)||![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Layer 4 LB**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Layer 7 LB**|![Checkmark icon](../../icons/checkmark-icon.svg)|Cookie Persistence|Cookie Persistence|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Health Checks**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Horizontal Scaling**|![Checkmark icon](../../icons/checkmark-icon.svg)|||| |
|**SSL Offload**|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg)|![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Management**|via IBM Portal|via IBM Portal|via IBM Portal|Self-manage (Vendor GUI)|Self-manage (Vendor GUI) |
|**High Availability**|Built-in|Built-in|Optional|Optional|Optional |
|**Advance LB (TCP Optimization, Compress, Caching, WAF)**||||Limited|![Checkmark icon](../../icons/checkmark-icon.svg)|
|**Global LB (GLB)**|||||![Checkmark icon](../../icons/checkmark-icon.svg) |
|**Pricing**|Usage-based|Monthly Flat|Monthly Flat|Monthly Flat|Monthly Flat |
{: row-headers}
{: class="comparison-table"}
{: caption="A comparison of IBM's load balancer offerings" caption-side="top"}
{: summary="This table all of IBM's load balancer offerings, and provides links to their documentation."}

<sup>1</sup> - Effective June 01, 2019, IBM Cloud will no longer market or sell our Local Load Balancer service. As a customer, you can still receive support for this service until its End of Support date, which has yet to be announced. A 90-day EOS notification email will be sent at a later date. Customers are encouraged to upgrade to our latest full-featured load balancing offering: [{{site.data.keyword.loadbalancer_full}}](/docs/loadbalancer-service?topic=loadbalancer-service-getting-started).
