---
layout: hextra-home
description: Designs, automation, SONiC and operations, built and shared by engineers in the field.
cascade:
  width: wide
---

<div class="hx:mt-6 hx:mb-6">
{{< hextra/hero-headline >}}
  Community SONiC
{{< /hextra/hero-headline >}}
</div>

<div class="hx:mb-12">
{{< hextra/hero-subtitle >}}
  Tools, hardware list and guides
  <br/>built and shared by infra-owners running it in production.
{{< /hextra/hero-subtitle >}}
</div>

<div class="hx:mb-6">
{{< hextra/hero-button text="Join us" link="https://sonic.premday.org/usergroup/about/#join-us" >}}
</div>

<div class="hx:mt-6"></div>

{{< hextra/feature-grid cols="3" >}}
  {{< hextra/feature-card
    title="Community SONiC"
    subtitle="Getting started, hardware compatibility, configuration deep-dives and tooling, written by engineers running SONiC in production."
    class="premday_card"
    link="sonic"
  >}}

  {{< hextra/feature-card
    title="SONiC-ready hardware"
    subtitle="Curated list of Community SONiC hardware approved by infra-owners who have already bought and run the gear."
    class="premday_card"
    link="sonic/tested-platforms"
  >}}
  
  {{< hextra/feature-card
    title="Network Design"
    subtitle="Reference architectures, spine-leaf topologies, IP addressing conventions, VRF and VXLAN segmentation patterns."
    class="premday_card"
    link="networking/"
  >}}

  {{< hextra/feature-card
    title="Operations"
    subtitle="Monitoring, alerting, troubleshooting runbooks and change management patterns for production network infrastructure."
    class="premday_card"
    link="networking/"
  >}}

{{< /hextra/feature-grid >}}