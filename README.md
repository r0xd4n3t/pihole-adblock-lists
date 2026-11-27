<a id="top"></a>

<h1 align="center">Pi-hole Adlists</h1>

<p align="center">
  <strong>Curated and maintained adlists for <a href="https://pi-hole.net/">Pi-hole</a></strong><br>
  A cleaner way to block ads, trackers, spam, and unwanted domains across your entire network.
</p>

<p align="center">
  <kbd>
    <img src="https://raw.githubusercontent.com/r0xd4n3t/pihole-adblock-lists/main/img/adsx.png" alt="Pi-hole Adlists Banner">
  </kbd>
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/r0xd4n3t/pihole-adblock-lists?style=flat-square" alt="Last Commit">
  <img src="https://img.shields.io/github/stars/r0xd4n3t/pihole-adblock-lists?style=flat-square&color=brightgreen" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/r0xd4n3t/pihole-adblock-lists?style=flat-square&color=brightgreen" alt="GitHub Forks">
  <img src="https://img.shields.io/badge/Pi--hole-Compatible-blue?style=flat-square" alt="Pi-hole Compatible">
  <img src="https://img.shields.io/badge/License-MIT-success?style=flat-square" alt="MIT License">
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#why-use-this-repository">Why Use This Repository</a> •
  <a href="#whats-included">What’s Included</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#update-schedule">Update Schedule</a> •
  <a href="#contributing">Contributing</a>
</p>

---

## Overview

This repository provides a curated collection of adlists for use with [Pi-hole](https://pi-hole.net/), the widely trusted network-level DNS sinkhole.

Instead of manually collecting and maintaining multiple upstream blocklists, this project offers a single, easy-to-use source that can be added directly to your Pi-hole deployment.

The goal is simple:

- Reduce ads across your network
- Minimize trackers and telemetry
- Block spam and unwanted domains
- Simplify adlist management
- Keep the source list clean and practical

---

## Why Use This Repository

Managing adlists manually can become messy over time. Different lists may overlap, disappear, break format, or become outdated.

This repository helps by providing:

### Centralized management
A single source URL you can import into Pi-hole.

### Easier maintenance
No need to manually track multiple list locations.

### Better consistency
Useful, public adlists grouped into one maintained file.

### Faster deployment
Quick setup for new Pi-hole installations.

---

## What is Pi-hole?

[Pi-hole](https://pi-hole.net/) is a DNS-based network-wide blocker that prevents known advertising, tracking, telemetry, and malicious domains from resolving.

Because filtering happens at the DNS level, protection can extend across many devices on your network, including:

- PCs and laptops
- Smartphones and tablets
- Smart TVs
- IoT devices
- Consoles and streaming devices

---

## What’s Included

This repository references reputable public sources such as:

- **StevenBlack's hosts**  
  https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts

- **YouTube Ads Blocklist**  
  https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/crowed_list.txt

- **PolishFiltersTeam KADhosts**  
  https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt

- **FadeMind Hosts Extras (Spam)**  
  https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts

- **Additional upstream lists**  
  More sources may be added, removed, or adjusted over time to keep the aggregated list useful and relevant.

---

## Quick Start

Use the following URL in your Pi-hole adlists configuration:

```text
https://raw.githubusercontent.com/r0xd4n3t/pihole-adblock-lists/main/pihole_adlists.txt
```

### Setup Steps

1. Open your Pi-hole admin dashboard
2. Navigate to **Group Management**
3. Click **Adlists**
4. Paste the URL above into the adlist field
5. Click **Add**
6. Run **Update Gravity**

Once gravity is updated, Pi-hole will begin applying the domains from this repository during DNS filtering.

---

## Recommended Workflow

For best results:

- Add the repository URL to Pi-hole
- Update gravity after changes
- Monitor your Pi-hole query logs
- Whitelist legitimate services when necessary
- Review list behavior periodically in shared or production environments

---

## Update Schedule

The file below is automatically maintained and updated:

```text
pihole_adlists.txt
```

Update frequency:

- **Daily**
- **Scheduled at 12:00 AM**

This helps keep the list aligned with upstream changes and reduces the need for manual maintenance.

---

## Important Notes

- Some third-party sources may occasionally become unavailable
- Certain upstream lists may change format or be deprecated
- Aggressive filtering can break legitimate websites or app features
- Always validate behavior before broad deployment in business or family environments

This repository aims to be practical and useful, but final tuning should always match your environment.

---

## Contributing

Contributions are welcome.

You can help by:

- Suggesting reliable upstream adlists
- Reporting broken or outdated list sources
- Improving documentation
- Submitting pull requests for enhancements

Please ensure any new source is:

- Publicly accessible
- Relevant to Pi-hole usage
- Reasonably maintained
- Not obviously abandoned or broken

---

## License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for full details.

---

## References

- [Pi-hole Official Website](https://pi-hole.net/)
- [Pi-hole Documentation](https://docs.pi-hole.net/)
- [Pi-hole GitHub Repository](https://github.com/pi-hole/pi-hole)

---

## Support the Project

If this repository helps your Pi-hole deployment:

- Star the repository
- Share it with other Pi-hole users
- Suggest improvements
- Contribute better source lists

---

<p align="center">
  <a href="#top">Back to Top</a>
</p>
