---
date: 2022-02-11
title: How does our road map look like? Which clouds do we plan to expand to?
image: images/blog/02.jpg
author_info:
  name: Jens F.
  image: images/author/jens.png
author: jens
draft: false

---
<!-- Solch eine Folie am Ende des Pitch Decks erzeugt Glaubwürdigkeit. Hier solltet ihr zeigen was ihr bis zum Status Quo alles erreicht und unternommen habt, um eure Idee zu validieren. Genauso interessant ist es auch zu wissen, was eure nächsten Schritte sind bzw. sein könnten. Solltet ihr bis dato schon Erfolge oder relevante Zahlen, wie Umsatz, Anzahl Kunden und/oder Nutzer, etc. generiert haben: platziert sie präsent auf dieser Folie. -->

## Cloud-init support and 12 months free tier

### Oracle Cloud Infrastructure (already adopted)

- 2% global market share, 19 cities
- [Fixed startup discount](https://www.oracle.com/de/startup/) of 500 USD
- `oci_core_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/oci/latest/docs/resources/core_instance))

### Amazon EC2 (already adopted)

- 33% global market share, 21 cities
- [Fixed startup discount](https://aws.amazon.com/de/activate/founders/) of 1350 USD
- `aws_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/instance))

### Microsoft Azure

- 18% global market share, 52 cities
- Only B2B startups can receive credits beyond the free account
- `azurerm_linux_virtual_machne` ([Official API](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/linux_virtual_machine))
- Public IP address attribute: `public_ip_address`

### Alibaba Cloud

- 6% global market share, 22 cities
- [Startups can apply for](https://www.alibabacloud.com/de/startup/join-us) up to 10k USD
- `alicloud_instance` ([Verified API](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs/resources/instance))
- Public IP address attribute: `public_ip`

## Cloud-init support and 1 month free tier

### IBM Cloud

- 5% global market share, 8 cities
- [Startups can apply for](https://developer.ibm.com/startups/) up to 12k USD
- `ibm_compute_vm_instance` ([Community API](https://registry.terraform.io/providers/IBM-Cloud/ibm/latest/docs/resources/compute_vm_instance))
- Public IP address attribute: `ipv4_address`

### OVH Cloud

- 11 cities
- [Startups can apply for](https://startup.ovhcloud.com/en/starters/) up to 10k EUR
- `openstack_compute_instance_v2` ([Verified API](https://registry.terraform.io/providers/terraform-provider-openstack/openstack/latest/docs/resources/compute_instance_v2))
- Public IP address attribute: `access_ip_v4`

### Digital Ocean
- 11 cities
- Only approved accelerators
- `digitalocean_droplet` ([Verified API](https://registry.terraform.io/providers/digitalocean/digitalocean/latest/docs/resources/droplet))
- Public IP address attribute: `ipv4_address`

### OpenTelekomCloud

- 2 cities
- [Startups can apply for](https://telekomhilft.telekom.de/t5/TechBoost/ct-p/techboost) 15k EUR
- `opentelekomcloud_compute_instance_v2` ([Community API](https://registry.terraform.io/providers/opentelekomcloud/opentelekomcloud/latest/docs/resources/compute_instance_v2))
- Public IP address attribute: `access_ip_v4`

### Yandex.Cloud

- 3 cities
- [Startups can apply for](https://cloud.yandex.com/cloud-boost) up to 12k USD
- `yandex_compute_instance` ([Community API](https://registry.terraform.io/providers/yandex-cloud/yandex/latest/docs/resources/compute_instance))
- Public IP address attribute: `network_interface.0.nat_ip_address`

## Cloud-init support but no free tier with sufficient RAM allowance

### Google Compute Engine

- 9% global market share, 3 cities
- Only approved accelerators
- `google_compute_instance` ([Official API](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/compute_instance))
- Public IP address attribute: `network_interface.0.access_config.0.nat_ip`

### TencentCloud

- 2% global market share, 15 cities
- No startup program
- `tencentcloud_instance` ([Verified API](https://registry.terraform.io/providers/tencentcloudstack/tencentcloud/latest/docs/resources/instance))
- Public IP address attribute: `public_ip`