# flashblade-tools
There are many great open source tools available for managing Pure Storage FlashBlade. They're spread across multiple github accounts (often based on support level). This page is intended to be a cheat sheet to help users easily find scripts. 
_____

# Configuring & Managing FlashBlade
- [FlashBlade Zero Touch Provisioning (remote provisioning)](https://github.com/PureStorage-OpenConnect/zero-touch-provisioner)
- [FlashBlade Ansible Collections](https://galaxy.ansible.com/purestorage/flashblade)
  - [FlashBlade Ansible playbook examples](https://github.com/PureStorage-OpenConnect/ansible-playbook-examples/tree/master/flashblade)
- [FlashBlade PowerShell toolkit](https://github.com/PureStorage-OpenConnect/flashblade-powershell-toolkit)
- [Purity//FB REST API docs](https://purity-fb.readthedocs.io/en/latest/)
- [FlashBlade REST Python SDK](https://github.com/purestorage/purity_fb_python_client)


# Monitoring FlashBlade 
- [Pure exporter to Prometheus (python-based, Pure-led)](https://github.com/PureStorage-OpenConnect/pure-exporter)
  - includes example Grafana dashboards
- [PSO-analytics: metrics on PSO-managed storage in a K8s cluster](https://github.com/joshuarobinson/pso-analytics)
- [Nagios plugins & extensions](https://github.com/PureStorage-OpenConnect/nagios-plugins)
- [Pure exporter to Prometheus (go-based, customer-led)](https://github.com/manahl/prometheus-flashblade-exporter)


# FlashBlade in Kubernetes
- [PSO Helm charts -- full support via Pure Support](https://github.com/purestorage/helm-charts)
- [indroductory examples of using FlashBlade + PSO](https://github.com/joshuarobinson/flashblade-pso)
- [kit to deploy JupyterHub on FlashBlade in K8s](https://github.com/PureStorage-OpenConnect/ai-platform/)
- [examples of elasticsearch on FlashBlade in K8s](https://github.com/joshuarobinson/elasticsearch_k8s_examples)


# Performance testing 
- [Running s5cmd to benchmark object storage](https://github.com/joshuarobinson/s5cmd_benchmarking)
- [Running fio on FlashBlade in K8s](https://github.com/joshuarobinson/fio-kubernetes)
- [AIRI performance tools](https://github.com/PureStorage-OpenConnect/AIRI/tree/master/network-validation-tools)

_____

There's also a Slack team for the Pure Storage Code() developer community. Pure Storage customers can join the Slack team following instructions in [this post](https://blog.purestorage.com/join-the-pure-storage-code-slack-team/).
