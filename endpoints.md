---

copyright:
  years:  2018, 2020
lastupdated: "2020-05-11"

keywords: LogDNA, IBM, Log Analysis, logging, config agent

subcollection: Log-Analysis-with-LogDNA

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:download: .download}
{:important: .important}
{:note: .note}

# Endpoints
{: #endpoints}

Review the connectivity options for interacting with {{site.data.keyword.la_full}}.
{:shortdesc}



## Connectivity options
{: #connectivity-options}

{{site.data.keyword.la_full_notm}} offers two connectivity options:

<dl>
    <dt>Public endpoints</dt>
        <dd>By default, you can connect to resources in your account over the {{site.data.keyword.cloud_notm}} public network. 
        </dd>
    <dt>Private endpoints</dt>
        <dd>For added benefits, you can also enable <a href="/docs/account?topic=account-vrf-service-endpoint#vrf" target="_blank" class="external"> virtual routing and forwarding (VRF)</a> and <a href="/docs/account?topic=account-vrf-service-endpoint" target="_blank" class="external"> service endpoints</a> for your infrastructure account. When you enable VRF for your account, you can connect to {{site.data.keyword.la_full_notm}} by using a private IP that is accessible only through the {{site.data.keyword.cloud_notm}} private network. To learn more about VRF, see <a href="/docs/resources?topic=direct-link-overview-of-virtual-routing-and-forwarding-vrf-on-ibm-cloud" target="_blank" class="external">Virtual routing and forwarding on {{site.data.keyword.cloud_notm}}</a>. To learn how to connect to {{site.data.keyword.la_full_notm}} by using a private endpoint, see <a href="/docs/Log-Analysis-with-LogDNA?topic=Log-Analysis-with-LogDNA-network#network_endpoints">Choosing a service endpoint</a>.
        </dd>
</dl>

[Learn more.](/docs/Log-Analysis-with-LogDNA?topic=Log-Analysis-with-LogDNA-network)

## API endpoints
{: #endpoints_api}

The following table shows the API endpoints:

| Region                   |  Public Endpoint                                   |
|--------------------------|----------------------------------------------------|
| `Chennai (in-che)`       | `https://api.in-che.logging.cloud.ibm.com`         |
| `Dallas (us-south)`      | `https://api.us-south.logging.cloud.ibm.com`       |
| `Frankfurt (eu-de)`      | `https://api.eu-de.logging.cloud.ibm.com`          |
| `London (eu-gb)`         | `https://api.eu-gb.logging.cloud.ibm.com`          |
| `Tokyo (jp-tok)`         | `https://api.jp-tok.logging.cloud.ibm.com`         |
| `Seoul (kr-seo)`         | `https://api.kr-seo.logging.cloud.ibm.com`         |
| `Sydney (au-syd)`        | `https://api.au-syd.logging.cloud.ibm.com`         |
| `Washington (us-east)`   | `https://api.us-east.logging.cloud.ibm.com`         |
{: caption="Table 1. Lists of public API endpoints for interacting with {{site.data.keyword.la_full_notm}} over {{site.data.keyword.cloud_notm}}'s public network" caption-side="top"}
{: #end-api-table-1}
{: tab-title="Public"}
{: tab-group="end-api"}
{: class="simple-tab-table"}
{: row-headers}

| Region                   | Private Endpoint                                       |
|--------------------------|--------------------------------------------------------|
| `Chennai (in-che)`       | `https://api.private.in-che.logging.cloud.ibm.com`   |
| `Dallas (us-south)`      | `https://api.private.us-south.logging.cloud.ibm.com`   |
| `Frankfurt (eu-de)`      | `https://api.private.eu-de.logging.cloud.ibm.com`      |
| `London (eu-gb)`         | `https://api.private.eu-gb.logging.cloud.ibm.com`      |
| `Tokyo (jp-tok)`         | `https://api.private.jp-tok.logging.cloud.ibm.com`     |
| `Seoul (kr-seo)`         | `https://api.private.kr-seo.logging.cloud.ibm.com`     |
| `Sydney (au-syd)`        | `https://api.private.au-syd.logging.cloud.ibm.com`     |
| `Washington (us-east)`   | `https://api.private.us-east.logging.cloud.ibm.com`     |
{: caption="Table 2. Lists of private API endpoints for interacting with {{site.data.keyword.la_full_notm}} over {{site.data.keyword.cloud_notm}}'s private network" caption-side="top"}
{: #end-api-table-2}
{: tab-title="Private"}
{: tab-group="end-api"}
{: class="simple-tab-table"}
{: row-headers}




## Ingestion endpoints
{: #endpoints_ingestion}

The following table shows the ingestion endpoints:

| Region                   |   Public Endpoint                                   |
|--------------------------|-----------------------------------------------------|
| `Chennai (in-che)`       | `https://logs.in-che.logging.cloud.ibm.com`       |
| `Dallas (us-south)`      | `https://logs.us-south.logging.cloud.ibm.com`       |
| `Frankfurt (eu-de)`      | `https://logs.eu-de.logging.cloud.ibm.com`          |
| `London (eu-gb)`         | `https://logs.eu-gb.logging.cloud.ibm.com`          |
| `Tokyo (jp-tok)`         | `https://logs.jp-tok.logging.cloud.ibm.com`         |
| `Seoul (kr-seo)`         | `https://logs.kr-seo.logging.cloud.ibm.com`    |
| `Sydney (au-syd)`        | `https://logs.au-syd.logging.cloud.ibm.com`         |
| `Washington (us-east)`   | `https://logs.us-east.logging.cloud.ibm.com`       |
{: caption="Table 3. Lists of public ingestion endpoints for interacting with {{site.data.keyword.la_full_notm}} over {{site.data.keyword.cloud_notm}}'s public network" caption-side="top"}
{: #end-ing-table-3}
{: tab-title="Public"}
{: tab-group="end-ing"}
{: class="simple-tab-table"}
{: row-headers}

| Region                   | Private Endpoint                                       |
|--------------------------|--------------------------------------------------------|
| `Chennai (in-che)`       | `https://logs.private.in-che.logging.cloud.ibm.com`  |
| `Dallas (us-south)`      | `https://logs.private.us-south.logging.cloud.ibm.com`  |
| `Frankfurt (eu-de)`      | `https://logs.private.eu-de.logging.cloud.ibm.com`     |
| `London (eu-gb)`         | `https://logs.private.eu-gb.logging.cloud.ibm.com`     |
| `Tokyo (jp-tok)`         | `https://logs.private.jp-tok.logging.cloud.ibm.com`    |
| `Seoul (kr-seo)`         | `https://logs.private.kr-seo.logging.cloud.ibm.com`    |
| `Sydney (au-syd)`        | `https://logs.private.au-syd.logging.cloud.ibm.com`    |
| `Washington (us-east)`   | `https://logs.private.us-east.logging.cloud.ibm.com`  |
{: caption="Table 4. Lists of private ingestion endpoints for interacting with {{site.data.keyword.la_full_notm}} over {{site.data.keyword.cloud_notm}}'s private network" caption-side="top"}
{: #end-ing-table-4}
{: tab-title="Private"}
{: tab-group="end-ing"}
{: class="simple-tab-table"}
{: row-headers}


## Syslog public endpoints
{: #endpoints_syslog}

The following table shows the API endpoints:

| Region                   |  Public Endpoint                                   |
|--------------------------|----------------------------------------------------|
| `Chennai (in-che)`       | `syslog://syslog-a.in-che.logging.cloud.ibm.com`          |
| `Dallas (us-south)`      | `syslog://syslog-a.us-south.logging.cloud.ibm.com`          |
| `Frankfurt (eu-de)`      | `syslog://syslog-a.eu-de.logging.cloud.ibm.com`             |
| `London (eu-gb)`         | `syslog://syslog-a.eu-gb.logging.cloud.ibm.com`             |
| `Tokyo (jp-tok)`         | `syslog://syslog-a.jp-tok.logging.cloud.ibm.com`            |
| `Seoul (kr-seo)`         | `syslog://syslog-a.kr-seo.logging.cloud.ibm.com`            |
| `Sydney (au-syd)`        | `syslog://syslog-a.au-syd.logging.cloud.ibm.com`            |
| `Washington (us-east)`   | `syslog://syslog-a.us-east.logging.cloud.ibm.com`          |
{: caption="Table 5. Lists of Syslog endpoints" caption-side="top"}
{: #end-syslog-table-5}
{: tab-title="Syslog"}
{: tab-group="end-syslog"}
{: class="simple-tab-table"}
{: row-headers}

| Region                   |  Public Endpoint                                   |
|--------------------------|----------------------------------------------------|
| `Chennai (in-che)`       | `syslog-tls://syslog-a.in-che.logging.cloud.ibm.com`          |
| `Dallas (us-south)`      | `syslog-tls://syslog-a.us-south.logging.cloud.ibm.com`          |
| `Frankfurt (eu-de)`      | `syslog-tls://syslog-a.eu-de.logging.cloud.ibm.com`             |
| `London (eu-gb)`         | `syslog-tls://syslog-a.eu-gb.logging.cloud.ibm.com`             |
| `Tokyo (jp-tok)`         | `syslog-tls://syslog-a.jp-tok.logging.cloud.ibm.com`            |
| `Seoul (kr-seo)`         | `syslog-tls://syslog-a.kr-seo.logging.cloud.ibm.com`            |
| `Sydney (au-syd)`        | `syslog-tls://syslog-a.au-syd.logging.cloud.ibm.com`            |
| `Washington (us-east)`   | `syslog-tls://syslog-a.us-east.logging.cloud.ibm.com`          |
{: caption="Table 6. Lists of Syslog-TLS endpoints" caption-side="top"}
{: #end-ing-syslog-6}
{: tab-title="Syslog-TLS"}
{: tab-group="end-syslog"}
{: class="simple-tab-table"}
{: row-headers}


