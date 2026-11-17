# WordPress VPS Hosting at RackNerd: What $1.83/mo Buys, Which Plan a WooCommerce Store Needs, and the No-Refund Rule to Read First (Full Plan Table)

RackNerd sells WordPress-capable KVM VPS from **$1.83/mo** on a 12-month prepay, which comes to **$21.96 up front**, and the renewal price stays at $1.83 instead of jumping. Every plan is unmanaged: root SSH, one IPv4, a 1 Gbps port, SSD storage and RackNerd's own ctrl panel are included, and you install WordPress yourself, either through a one-click app or over SSH.

Two facts decide whether this host fits you. You need to be comfortable running a Linux web stack, and RackNerd states plainly in its knowledgebase that it does not offer refunds or a money-back guarantee. Below is every plan with its real annual and three-year cost, what backups and control panels cost elsewhere so you can budget them here, and where the line sits between your job and the host's.

> **Quick pick:** one small WordPress site fits the 2 GB KVM at **$3.00/mo ($36 a year)**. A WooCommerce store or several sites needs the 4 GB KVM at **$5.00/mo ($60 a year)**. 👉 [Check the current RackNerd annual VPS specials](https://bit.ly/RacKnerd)

## All five RackNerd VPS plans compared

RackNerd's current specials run from 1 GB to 8 GB of RAM, all on the same KVM platform, all billed 12 months at a time. The per-month figure only applies if you pay the full year upfront.

| Plan | vCPU / RAM | SSD | Bandwidth | Price (12-month prepay) | Order |
| --- | --- | --- | --- | --- | --- |
| 1 GB KVM VPS | 1 vCPU / 1 GB | 20 GB | 3 TB | $1.83/mo · $21.96 up front | [Order 1 GB](https://bit.ly/RacKnerd) |
| 2 GB KVM VPS | 2 vCPU / 2 GB | 35 GB | 5 TB | $3.00/mo · $36.00 up front | [Order 2 GB](https://bit.ly/RacKnerd) |
| 4 GB KVM VPS | 3 vCPU / 4 GB | 60 GB | 7 TB | $5.00/mo · $60.00 up front | [Order 4 GB](https://bit.ly/RacKnerd) |
| 6 GB KVM VPS | 6 vCPU / 6 GB | 100 GB | 12 TB | $7.50/mo · $90.00 up front | [Order 6 GB](https://bit.ly/RacKnerd) |
| 8 GB KVM VPS | 7 vCPU / 8 GB | 150 GB | 20 TB | $10.00/mo · $120.00 up front | [Order 8 GB](https://bit.ly/RacKnerd) |

Those five plans are the ones RackNerd currently lists on its specials page and that independent pricing trackers have recorded without change since late October. Stock rotates, so confirm the RAM, disk and price on the order page before you pay.

## What every plan includes, and what it doesn't

The platform underneath is identical across the range. The differences are RAM, disk and bandwidth.

| Item | What you get |
| --- | --- |
| Virtualization | KVM, full root SSH access |
| Control panel | ctrl, RackNerd's own panel, included with every VPS special |
| ctrl features | Reboot, OS reinstall, HTML5 VNC console, one-click apps, network firewall rules, root password reset, plan upgrades |
| IP addresses | 1 IPv4 included per server |
| Network port | 1 Gbps |
| Storage | SSD |
| Operating systems | CentOS, Rocky Linux, AlmaLinux, Fedora, Debian, Ubuntu; custom ISO installs on request via support ticket |
| One-click apps | AdminBolt, CyberPanel, CloudPanel, Docker with Portainer, Ollama, n8n and others |
| Backups | Not listed as an included service |
| Management | Unmanaged. You own the OS, the stack and the WordPress install |
| Refunds | None, per RackNerd's knowledgebase |
| Support | 24/7 for the platform itself |

WordPress is not a separate product line here. RackNerd's own documentation points WordPress users at the one-click CyberPanel or CloudPanel images, or a manual install over SSH. That is the whole setup story: no WordPress-specific dashboard, no staging button, no plugin update automation.

Bandwidth deserves a note because it is unusually generous. The cheapest plan ships 3 TB a month, which is more than most small WordPress sites move in a year. Disk is the constraint you will hit first, not traffic.

## The real cost: year one versus year four

RackNerd's specials renew at the same rate you sign up for, so the 4 GB plan costs $60 in year one, $60 in year two, $60 in year three. A four-year run on that box totals **$240**, roughly $5/mo the entire way.

Compare the pattern most budget hosts use. Hostinger's KVM 1 lists at $6.49/mo, paid as $155.76 for 24 months, then renews at $11.99/mo for the same term, an increase of about 85%. Its KVM 4 goes from $12.99/mo to $28.99/mo on renewal, an increase of about 123%. Run the arithmetic on Hostinger's KVM 1 over four years: $155.76 for the first two years plus roughly $287.76 for the next two, about $443 total. RackNerd's 4 GB plan over the same four years is $240, with more RAM, more disk and 7 TB of monthly bandwidth instead of 4 TB. Hostinger counters with NVMe storage, free weekly backups and a free domain for a year, which is why the two are worth comparing on total cost rather than sticker price.

The catch on the RackNerd side is cash flow. You pay $60 up front for the 4 GB plan, not $5 a month. Five plans times a year of prepay is a small sum, but it is a sum you cannot get back.

## Add-ons that quietly change the total

A cheap VPS stays cheap only if you avoid the metered extras. Three of them matter for WordPress.

**Backups.** RackNerd's specials page does not list a backup service, so treat backups as your responsibility from day one. Budget a few dollars a year for off-site storage and automate a nightly database dump plus a weekly full copy. For scale, Atlantic.Net charges 20% of the server price for daily cloud backups with a $1.00 monthly minimum, which on a $60/year server would be about $12 a year. Whatever you choose, the cost is real and it is not in the $5/mo sticker.

**Control panel.** A cPanel license is where budget VPS projects blow their budget. Atlantic.Net lists cPanel from $23/mo, and Liquid Web includes InterWorx while selling cPanel and Plesk as paid add-ons at checkout. At $23/mo, a panel license costs more in four months than RackNerd's 4 GB server costs in a year. CyberPanel and CloudPanel are free, install in one click from ctrl, and handle multiple WordPress sites, SSL certificates and PHP versions. Start there.

**Extra IP addresses.** One IPv4 is included. Atlantic.Net charges $3.65/mo for each additional public IPv4, and IPv6 addresses are free there. RackNerd does not publish additional-IP pricing on the specials page, so if you need a second address for a mail server or an SSL edge case, ask support before ordering. Most WordPress sites never need one.

If you can run a stack without a paid panel, the 4 GB plan plus your own backup storage lands near **$6/mo all-in**. 👉 [Start with the 4 GB KVM plan](https://bit.ly/RacKnerd)

## Is this managed WordPress hosting? No

RackNerd's VPS specials are unmanaged. Support covers the platform: the node, the network, the panel, provisioning problems. Everything above the operating system is yours, which means WordPress core and plugin updates, PHP version upgrades, caching rules, database tuning, security hardening, fail2ban, SSL renewal and backups.

InMotion's support tiers show where that line usually falls. Its Premier Care Advanced Product Support covers server-level issues such as PHP configuration, database connection errors and server-level caching, while WordPress application tuning and high-traffic stability sit in a separate paid service. On an unmanaged RackNerd box, both halves are yours.

What this means in practice: if a plugin update breaks your checkout at 11pm, you are the one restoring a backup. If you would rather not be, a managed plan at two to ten times the price is the honest answer, and RackNerd is the wrong purchase.

## What an uptime guarantee actually covers

Hosting SLAs measure infrastructure, not your WordPress installation. Liquid Web's 100% guarantee is written as "your network and power are available 100% of the time." Atlantic.Net's 100% SLA covers network uptime, hardware replacement and infrastructure uptime, backed by a money-back guarantee. InMotion advertises 99.99% server uptime with triple failover redundancy.

None of those numbers promise that your site stays up after a bad plugin update, a full disk or an exhausted PHP worker pool. RackNerd's specials page sells on price, the ctrl panel and the 1 Gbps port rather than an uptime percentage, and support is positioned around platform help. Judge it on what it does publish, and keep your own monitoring in place.

Sizing follows the same logic. Concurrency on WordPress is limited by PHP workers, and each worker consumes RAM. A 1 GB box with a lean LEMP stack and page caching handles a small blog. A WooCommerce store with a cart, checkout and a few plugins runs out of RAM before it runs out of disk, which is why 4 GB is the realistic floor for a shop.

## Read the refund policy twice

RackNerd's knowledgebase answers the refund question directly: per its terms of service, it does not offer refunds or a money-back guarantee. Immediate cancellation starts a termination countdown, and prepaid money does not come back. Account credit sitting in your wallet is not refundable either.

This is the single biggest difference between RackNerd and hosts that advertise a 90-day money-back window, such as InMotion. At $21.96 for the entry plan the risk is small. At $120 for the 8 GB plan it is worth thinking about before you click, not after.

Two ways to manage it. RackNerd also sells its standard KVM line on monthly billing, which third-party trackers list from about $2.24/mo, so you can rent the platform for a month and test your stack before committing to a year. And keep off-site backups from day one, because a host with strict cancellation rules is a bad place to learn that lesson.

Third-party write-ups of the policy also describe administrative fees of $125 to $250 when a payment dispute is tied to a service suspended for abuse. Whatever the details, disputing a charge is a worse path than testing monthly first.

👉 [Compare the plans before you prepay a year](https://bit.ly/RacKnerd)

## Who should skip RackNerd

Skip it if you want someone else to handle WordPress updates and security, if you need NVMe storage for a database-heavy store, if your site needs more than 8 GB of RAM on a single box, if you require a refund window because you are not sure the host will work out, or if you want cPanel bundled in the price. RackNerd's range tops out at 8 GB, and its storage is regular SSD rather than NVMe.

Data center choice matters more than usual here because the price is the same everywhere. Locations include Los Angeles, San Jose, Seattle, Dallas, Chicago, New Jersey, Atlanta, Amsterdam and Strasbourg. Pick the one closest to your readers; a European audience on a Los Angeles box will feel the latency on every admin page load.

## How to choose in one minute

- **One blog, under ~10k visits a month, caching plugin installed** → 1 GB at $1.83/mo, or 2 GB at $3.00/mo if you want headroom for PHP workers.
- **Two to five small WordPress sites on CyberPanel or CloudPanel** → 2 GB at $3.00/mo, moving to 4 GB once disk passes 25 GB.
- **WooCommerce, membership site or a site with heavy plugins** → 4 GB at $5.00/mo. This is the plan most readers should buy.
- **Agencies consolidating a dozen low-traffic sites, or self-hosted AI tools alongside WordPress** → 6 GB at $7.50/mo or 8 GB at $10.00/mo. Note that 8 GB is the minimum for some of the AI one-click apps, not a WordPress requirement.

Before you pay, confirm four things on the order page: the 12-month term and the exact upfront amount, that the renewal price matches the signup price, which data center you selected, and that you have an off-site backup plan ready. Then install CyberPanel or CloudPanel from ctrl and migrate with a plugin rather than by hand.

👉 [Pick your data center and order the RackNerd plan that fits](https://bit.ly/RacKnerd)
