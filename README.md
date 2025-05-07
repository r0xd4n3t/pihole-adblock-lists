<a id="top"></a>

#

<h1 align="center">Pi-hole Adlists</h1>

<p align="center"> 
  <kbd>
    <img src="https://raw.githubusercontent.com/r0xd4n3t/pihole-adblock-lists/main/img/adsx.png" alt="Pi-hole Adlists">
  </kbd>
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/r0xd4n3t/pihole-adblock-lists?style=flat" alt="Last Commit">
  <img src="https://img.shields.io/github/stars/r0xd4n3t/pihole-adblock-lists?color=brightgreen" alt="GitHub Stars">
  <img src="https://img.shields.io/github/forks/r0xd4n3t/pihole-adblock-lists?color=brightgreen" alt="GitHub Forks">
</p>

## Overview

This repository hosts a collection of adlists for use with [Pi-hole](https://pi-hole.net/), a powerful network-wide ad blocker.

## About Pi-hole

Pi-hole is a network-level advertisement and internet tracker blocking application that acts as a DNS sinkhole. It blocks ads, tracking, and other undesirable content before it reaches your devices, providing a cleaner and safer browsing experience.

## Adlists

- **StevenBlack's hosts:** [View List](https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts)
- **YouTube Ads Blocklist:** [View List](https://raw.githubusercontent.com/kboghdady/youTube_ads_4_pi-hole/master/crowed_list.txt)
- **PolishFiltersTeam KADhosts:** [View List](https://raw.githubusercontent.com/PolishFiltersTeam/KADhosts/master/KADhosts.txt)
- **FadeMind's Hosts Extras:** [View List](https://raw.githubusercontent.com/FadeMind/hosts.extras/master/add.Spam/hosts)

...and more.

## Usage Instructions

Follow these steps to add the adlists to your Pi-hole setup:

1. Access your Pi-hole web interface.
2. Navigate to **Group Management** in the left sidebar.
3. Select **Adlists** under the desired group.
4. Add the following URL to the list of adlists:

https://raw.githubusercontent.com/r0xd4n3t/pihole-adblock-lists/main/pihole_adlists.txt

5. Click **Save** and then **Update** to apply the changes.
6. Enjoy an ad-free browsing experience!

**Note:** The `pihole_adlists.txt` file is automatically updated daily at 12 AM to ensure your adlists remain current and effective.

For more details on using Pi-hole, refer to the [official documentation](https://pi-hole.net/) and [GitHub repository](https://github.com/pi-hole/pi-hole).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

We welcome contributions! Feel free to submit a pull request to add new adlists or make improvements.

---

**Reminder:** Regularly update your adlists to keep your Pi-hole up-to-date and effective at blocking ads.

For more information, visit the [Pi-hole official documentation](https://pi-hole.net/) and the [Pi-hole GitHub repository](https://github.com/pi-hole/pi-hole).

<p align="center"><a href="#top">Back to Top</a></p>
