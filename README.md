# RackNerd Dedicated Server Pricing: Is the $139 Xeon Real, Which Config Fits Your Workload, and Does 15OFFDEDI Still Apply?

The cheapest true bare-metal machine in RackNerd's dedicated server lineup is **$139/month**: an Intel Xeon E3-1230 v2 with 16 GB RAM, a 480 GB SSD, 35 TB of metered traffic on a 1 Gbps port and 5 IPv4 addresses. If you don't need your own chassis, the hybrid dedicated line starts at **$39/month** for 2 vCores, 4 GB RAM and 120 GB of disk, provisioned in minutes and running on dedicated resources inside a shared physical host.

Those are the two numbers most people arrive looking for. What follows is the full set of plans across all five families, plus the parts that usually get skipped: how old the cheap Xeons actually are, why the IP count on three specific configs matters more than the CPU, how to compare three different bandwidth meters, delivery windows for each tier, and what to confirm with sales before you pay.

> **Quick picks**
> - Cheapest real metal for general hosting: **$139** E3-1230 v2 (16 GB / 480 GB SSD / 35 TB / 5 IPs).
> - Single-thread performance matters (game servers, compile jobs, latency-sensitive apps): **$219** Ryzen 5 7600 with DDR5 and NVMe.
> - Reselling VPS or need a lot of IPv4: **$349** Dual E5-2650 v2 Virtualization Node with **29 IPs**, or $399 for the E5-2680 v4 with **61 IPs**.
>
> 👉 [Check the current RackNerd dedicated server lineup and live cart prices](https://bit.ly/RacKnerd)

## Every RackNerd dedicated server plan, side by side

Prices in the third column are the listed monthly rates. The second figure applies 15% off and assumes the promo code is accepted at checkout; it is not a guarantee of the final invoice.

### Bare-metal Intel Xeon (US locations)

| Plan | RAM / Storage | Bandwidth / IPv4 | Monthly | Order |
| --- | --- | --- | --- | --- |
| Xeon E3-1230 v2 | 16 GB / 480 GB SSD | 35 TB @ 1 Gbps / 5 IPs | **$139** (≈ $118.15) | [Start with the $139 entry box](https://bit.ly/RacKnerd) |
| Xeon E3-1270 v3 | 32 GB / 2× 1 TB SSD | 35 TB @ 1 Gbps / 5 IPs | $169 (≈ $143.65) | [Order the E3-1270 v3](https://bit.ly/RacKnerd) |
| Dual E5-2650 v2 | 64 GB / 1 TB SSD | 100 TB @ 1 Gbps / 5 IPs | $199 (≈ $169.15) | [Get the dual E5-2650 v2](https://bit.ly/RacKnerd) |
| Dual E5-2650 v2 | 128 GB / 1 TB SSD + 3 TB HDD | 50 TB @ 1 Gbps / 5 IPs | $245 (≈ $208.25) | [Pick the 128 GB build](https://bit.ly/RacKnerd) |
| Dual E5-2650 v2 Virtualization Node | 256 GB / 4× 2 TB SSD | 100 TB @ 1 Gbps / **29 IPs** | **$349** (≈ $296.65) | [Deploy the 29-IP node](https://bit.ly/RacKnerd) |
| Dual E5-2680 v4 | 256 GB / 4× 2 TB SSD | 100 TB @ 1 Gbps / **61 IPs** | $399 (≈ $339.15) | [Order the 61-IP E5-2680 v4](https://bit.ly/RacKnerd) |
| Dual E5-2640 v2 Storage Special | 64 GB / 256 GB SSD + 10× 16 TB HDD | 200 TB @ 1 Gbps / 5 IPs | $479 (≈ $407.15) | [Grab the 160 TB storage server](https://bit.ly/RacKnerd) |

### AMD Ryzen (single socket, DDR5 on the current-gen parts)

| Plan | RAM / Storage | Bandwidth / IPv4 | Monthly | Order |
| --- | --- | --- | --- | --- |
| Ryzen 5 7600 | 64 GB DDR5 / 1 TB NVMe | 40 TB @ 1 Gbps / 1 IP | **$219** (≈ $186.15) | [Order the Ryzen 5 7600](https://bit.ly/RacKnerd) |
| Ryzen 7 7700 | 64 GB DDR5 / 1 TB NVMe | 40 TB @ 1 Gbps / 1 IP | $249 (≈ $211.65) | [Choose the Ryzen 7 7700](https://bit.ly/RacKnerd) |
| Ryzen 9 7900 | 64 GB DDR5 / 1 TB NVMe | 40 TB @ 1 Gbps / 1 IP | $269 (≈ $228.65) | [Pick the Ryzen 9 7900](https://bit.ly/RacKnerd) |
| Ryzen 9 5950X | 128 GB DDR4 / 2 TB NVMe | 40 TB @ 1 Gbps / 1 IP | $309 (≈ $262.65) | [Get the 5950X with 128 GB](https://bit.ly/RacKnerd) |
| Ryzen 9 7950X3D | 128 GB DDR5 / 1 TB NVMe | 40 TB @ 1 Gbps / 1 IP | $379 (≈ $322.15) | [Deploy the 7950X3D](https://bit.ly/RacKnerd) |
| Ryzen 9 7950X3D High RAM & NVMe | 192 GB DDR5 / 2× 3.84 TB NVMe | 40 TB @ 1 Gbps / 1 IP | $499 (≈ $424.15) | [Order the 192 GB DDR5 build](https://bit.ly/RacKnerd) |

### 10 Gbps unmetered (Los Angeles, New Jersey, London, Montreal only)

| Plan | RAM / Storage | Bandwidth / IPv4 | Monthly | Order |
| --- | --- | --- | --- | --- |
| Xeon E3-1230 v3 | 32 GB DDR3 / 1 TB SSD | 10 Gbps unmetered / 5 IPs | $599 (≈ $509.15) | [Take the $599 10 Gbps box](https://bit.ly/RacKnerd) |
| Xeon E-2136 | 32 GB DDR4 / 1 TB NVMe | 10 Gbps unmetered / 5 IPs | $799 (≈ $679.15) | [Order the E-2136 10 Gbps](https://bit.ly/RacKnerd) |
| Dual E5-2630 v4 | 64 GB DDR4 / 1 TB NVMe | 10 Gbps unmetered / 5 IPs | $950 (≈ $807.50) | [Select the dual E5-2630 v4](https://bit.ly/RacKnerd) |
| Dual E5-2695 v4 | 128 GB DDR4 / 2× 1 TB NVMe | 10 Gbps unmetered / 5 IPs | $1,399 (≈ $1,189.15) | [Deploy the 128 GB unmetered server](https://bit.ly/RacKnerd) |
| EPYC 7642 | 128 GB DDR4 / 2× 1 TB NVMe | 10 Gbps unmetered / 5 IPs | $1,699 (≈ $1,444.15) | [Get the EPYC 7642](https://bit.ly/RacKnerd) |
| EPYC 7702P | 128 GB DDR4 / 2× 1 TB NVMe | 10 Gbps unmetered / 5 IPs | $1,999 (≈ $1,699.15) | [Order the EPYC 7702P](https://bit.ly/RacKnerd) |

### Singapore (Asia)

| Plan | RAM / Storage | Bandwidth / IPv4 | Monthly | Order |
| --- | --- | --- | --- | --- |
| Xeon E-2286G | 64 GB DDR4 / 2× 4 TB HDD | 100 Mbps unmetered / 1 IP | $399 (≈ $339.15) | [Order the Singapore HDD build](https://bit.ly/RacKnerd) |
| Xeon E-2286G | 64 GB DDR4 / 2× 1 TB SSD | 100 Mbps unmetered / 1 IP | $399 (≈ $339.15) | [Pick the Singapore SSD build](https://bit.ly/RacKnerd) |
| Dual Xeon Silver 4214 | 128 GB DDR4 / 2× 1 TB SSD | 100 Mbps unmetered / 1 IP | $579 (≈ $492.15) | [Deploy the dual Silver 4214](https://bit.ly/RacKnerd) |

### Hybrid dedicated (virtualized slices, instant setup)

| Plan | RAM / Storage | Bandwidth / IPv4 | Monthly | Order |
| --- | --- | --- | --- | --- |
| Dual E5-2690, 2 vCore | 4 GB / 120 GB HDD | 5 TB @ 1 Gbps / 1 IP | **$39** | [Start at $39 with the hybrid entry](https://bit.ly/RacKnerd) |
| Dual E5-2690, 4 vCore | 8 GB / 250 GB HDD | 5 TB @ 1 Gbps / 1 IP | $59 | [Order the 8 GB hybrid](https://bit.ly/RacKnerd) |
| Dual E5-2690, 6 vCore | 16 GB / 500 GB HDD | 10 TB @ 1 Gbps / 1 IP | $79 | [Choose the 16 GB hybrid](https://bit.ly/RacKnerd) |
| Dual E5-2690, 8 vCore | 32 GB / 750 GB HDD | 10 TB @ 1 Gbps / 1 IP | $99 | [Get the 32 GB hybrid tier](https://bit.ly/RacKnerd) |

The hybrid table carries no promo column in RackNerd's published plan listings, so treat $39 as the number you'll see and confirm in the cart.

## What every bare-metal order includes

IPMI/KVM access ships with each dedicated server, which means you can reinstall the OS, force a reboot or repair a broken network config without opening a ticket. RackNerd's own FAQ puts it plainly: you're in full control at all times. Remote power cycling is available from the client panel as well.

Deployments span 20+ datacenters across North America, Europe and Asia, but stock for a specific configuration varies by location. The order form shows the datacenter your server will actually be built in, so check that field before you pay rather than assuming you'll land in Los Angeles.

Anything off-menu gets quoted by sales: different RAID layouts, more RAM, extra drives, additional IPv4, or several servers dropped into one VLAN for private networking. There's no self-serve configurator for that, so plan on an email exchange.

Windows images appear on the plan listings as bring-your-own-license, which means the OS cost sits outside the monthly figure.

## How old is the $139 Xeon, really

The E3-1230 v2 is Ivy Bridge, a 2012-era 4-core/8-thread part. The dual E5-2650 v2 boxes are Sandy Bridge-EP, older still in architecture terms. They're cheap because the platform is old, and that shows up in three places: no AVX-512, no AVX2 on the E3-1230 v2, and memory bandwidth and I/O that current silicon beats comfortably.

For a LAMP or nginx stack, a mail server, a DNS node, a database that fits in 16 GB, or a CI runner, none of that matters much. You get 5 IPv4 addresses, a 1 Gbps port and full out-of-band control for under $150 a month.

It matters when your workload is single-thread sensitive or vector-heavy. Game servers, compilation, anything that lives and dies by per-core clock speed will feel the gap between an Ivy Bridge core and a Zen 4 core. That's the case for the $219 Ryzen 5 7600, even though its spec sheet looks thinner on paper with a single IP and 40 TB of traffic.

One config in the Xeon list deserves a second look: the Dual E5-2680 v4 at $399 is Broadwell, roughly two generations newer than the E5-2650 v2, with AVX2 and DDR4. If you want a Xeon but not a museum piece, that's the one.

## IP count decides it for some buyers

Standard Xeon configs come with 5 IPv4 addresses. The Virtualization Node Special at $349 carries **29**, and the E5-2680 v4 at $399 carries **61**. Straight division puts those at roughly $12 and $6.54 per IP respectively, which is the kind of arithmetic that matters if you're spinning up a VPS reseller operation or running a lot of isolated services that each need their own address.

Extra IPv4 is scarce and priced accordingly almost everywhere, so a plan that bundles 61 addresses changes the effective cost of the whole box for that use case. Before ordering, ask sales two things: whether the allocation needs justification documents, and whether the addresses are usable on separate VLANs.

If you only need one address, don't pay for 61. The Ryzen plans ship with 1 IP and that's fine for a single application server.

## Three bandwidth meters, three different answers

Metered 1 Gbps is the default on the Xeon and Ryzen lines, with caps from 35 TB to 200 TB per month. Do the math on 35 TB and it works out to roughly 108 Mbps sustained around the clock, or about 3.2 days of full 1 Gbps before the cap. If your traffic pattern is bursty, you'll never notice. If you're pushing a steady stream of large files, you will.

Unmetered 10 Gbps starts at $599 and is limited to Los Angeles, New Jersey, London and Montreal. There's no overage billing because there's no meter; you share a 10 Gbps port. The theoretical ceiling is enormous, and the real constraint becomes what your applications can actually push. Video streaming, CDN origins and large dataset transfers are the workloads this tier exists for.

Singapore runs unmetered 100 Mbps. Saturate it 24/7 and you top out around 32 TB a month, slightly less than the 35 TB you'd get from the cheapest US box, but with zero overage risk and much lower latency into South and Southeast Asia and Australia. If your users are in Asia and your traffic is steady rather than spiky, that trade is usually worth it.

## Delivery windows by tier

Bare-metal Xeon servers are typically deployed in under 48 hours. The 10 Gbps tier can take up to 72 hours because the inventory pool is smaller, though many orders go out same-day. Hybrid servers activate within minutes of payment. Singapore stock is the thinnest of the group, so confirm the lead time if you're working against a deadline. RackNerd's own guidance is to contact sales before ordering when the timeline is tight.

## The 15OFFDEDI question

The code 15OFFDEDI circulates widely on third-party price sheets for RackNerd dedicated servers, described as 15% off recurring for the life of the service rather than a first-invoice discount. It does not appear on the FAQ and datacenter pages reviewed for this article, so the honest version is this: type it into the promo field at checkout, watch the total, and treat whatever the cart shows as the real price. If it applies, $139 becomes about $118.15 and $349 becomes about $296.65, every month, not just once.

If it doesn't apply, the listed prices are still competitive for what's in the box.

👉 [Try the code against a specific config and see the cart total](https://bit.ly/RacKnerd)

## Four things to confirm before you pay

1. **Datacenter and stock.** Configuration availability varies by location. The order form tells you where the server will be built; verify it matches the latency you need.
2. **Provisioning time.** Under 48 hours for standard bare metal, up to 72 for 10 Gbps, minutes for hybrid. Time-sensitive projects should get a confirmation from sales first.
3. **Console access.** Bare metal includes IPMI/KVM. Hybrid does not, offering instead a control panel with reboot, stop, boot, VNC, rescue and power-off. If your recovery plan depends on IPMI, hybrid won't cover it.
4. **Refund terms.** RackNerd does not publish a trial or refund window for dedicated servers on the pages reviewed here, unlike its shared hosting. Ask sales directly before committing a year of budget.

## Who shouldn't buy a RackNerd dedicated server

If you're hosting one small site, a staging environment or a side project, the **$39 hybrid** covers it and activates instantly. Buying metal for that workload means paying for capacity you'll never touch and waiting two days for it.

If your ceiling is $100 a month and you need a physical machine, RackNerd has nothing for you. The entry bare-metal price is $139 and the next step up is $169.

If you need current-generation single-thread performance below $200, the Ryzen line starts at $219. The cheap Xeons won't get you there.

## Picking the right config

Match the workload to the box rather than the other way around.

A single site or app with root access on real hardware: **$139** E3-1230 v2. Multi-threaded work that needs RAM and disk more than clock speed: **$199** dual E5-2650 v2 with 64 GB and 100 TB. Reselling VPS or running many isolated services: **$349** for 29 IPs, or **$399** for 61 IPs on newer silicon. Bulk storage: **$479** gets 160 TB, which is about $2.54 per TB per month at the discounted rate. Latency-sensitive or per-core-bound work: **$219** Ryzen 5 7600 upward. Bandwidth as the actual bottleneck: **$599** and up on 10 Gbps. Users concentrated in Asia: **$399** in Singapore.

Two final checks before checkout: confirm the datacenter shown on the order form, and confirm the promo total in the cart rather than assuming it.

👉 [Compare all RackNerd dedicated server configurations and place your order](https://bit.ly/RacKnerd)
