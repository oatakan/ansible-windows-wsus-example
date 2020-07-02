# ansible-windows-wsus-example
This repo contains sample playbooks to set up WSUS on Windows. Here are some of the example use cases implemented:

- provision test VMs to VMware, Azure, AWS, Red Hat Virtualization, OpenShift environments
- check and generate HTML update compliance report
- email compliance report
- update Windows systems to latest approved patches via WSUS server
- configure Windows systems to pull updates from a WSUS server
- install WSUS server
- configure WSUS server
- enable auto-approval on WSUS server
- pull report from WSUS server and email
- pull credentials from cyberark

## Example implementation of patching and reporting with Ansible Tower

![Image 1](docs/images/step-1.png)

![Image 1](docs/images/step-2.png)

![Image 1](docs/images/step-3.png)
