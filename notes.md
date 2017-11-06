DOCKER AND CONTAINERS: THE BIG PICTURE
======================================


What are containers?
--------------------

- Historically, 1 application per 1 server
  - Issues:
    - Procurement lead times
    - Up-front capex
    - Ongoing opex

- Hypervisor Architecture (e.g. VMWare)
  - 1 hypervisor manages multiple VMs; 1 VM serves 1 application
  - big improvement, but still issues:
    - each VM is "dressed up" like an independent server
    - each VM requires its own resources
      - % of total processing power, % of total memory, % of total disc space
    - each VM requires its own Operating System (licensing costs?)

- Container Architecture (e.g. Docker)
  - Only 1 Operating System per server; 1 container serves 1 application
  - Containers are smaller and more efficient than VMs
  - Advantages:
    - Trims the fat required by resource-hungry VM/OS
    - No extra OS boot processes required by individual applications
  - Issues:
    - Less mature than hypervisor virtualization ecosystem