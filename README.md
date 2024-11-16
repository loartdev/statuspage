[![Health Check](../../actions/workflows/health-check.yml/badge.svg)](../../actions/workflows/health-check.yml)

LoArt & Dev Services Status
==========================

A fork of [Statsig's Open-Source Status Page](https://github.com/statsig-io/statuspage), customized for LoArt & Dev Services.

**What is it?**
---------------

LoArt & Dev Services Status is a simple, zero-dependency, pure js/html status page based on GitHub Pages and Actions. It displays the current status of our services, providing a clear and easily consumable overview of our system's health.

**How does it work?**
---------------------

This project uses GitHub actions to wake up every hour and run a shell script (`health-check.sh`). The script runs `curl` on every URL in your config and appends the result of that run to a log file and commits it to the repository. The log is then pulled dynamically from `index.html` and displayed on the status page.

**Customizations and Features**
------------------------------

* [List any customizations or features you've added to the original project]

**Getting Started**
-------------------

1. Clone the repository: `git clone https://github.com/your-username/loart-dev-status.git`
2. Follow the setup instructions in the original project: [link to original project's setup instructions]
3. Customize the `health-check.sh` script to fit your needs

**Contributors**
---------------

* [LoArt & Dev (Simon Lopez)](https://loart.dev)
* Statsig's

**License**
----------

This project is licensed under [the original license].

**Acknowledgments**
------------------

This project is a fork of [Statsig's Open-Source Status Page](https://github.com/statsig-io/statuspage). We appreciate their work and contributions to the open-source community.
