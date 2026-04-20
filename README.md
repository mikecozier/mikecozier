<h1 align="center">Hello World! 👋 <br> I'm Michael Cozier</h1>

<div align="center">
  <img src="https://github.com/mikecozier/mikecozier/blob/main/newbanner.jpg" alt="banner">
</div>

<div align="center">

<h2>ALIS Systems Security Administrator @ Lockheed Martin</h2>
<h3>Cybersecurity • SIEM • Infrastructure Security • DevOps Automation</h3>

<p>
Army & NYPD veteran with 20+ years of operational experience, now focused on securing systems, <br>
automating infrastructure, and supporting mission-critical environments in the defense sector.
</p>

<p>
In 2025, I completed a DevOps internship at Rakuten Advertising where I:
<br>• Automated GCP IAM governance across 90+ projects
<br>• Built Terraform-based infrastructure workflows
<br>• Developed alerting pipelines with Slack & Cloud Monitoring
</p>

<p>
<b>🎓 Education</b><br>
B.S. Computer Security Technology, Farmingdale State College (GPA: 3.93)
</p>

<p>
<b>📜 Certifications</b><br>
Cisco CCNA • CompTIA Security+ • Google Associate Cloud Engineer
</p>

<p>
<b>🛠️ Technical Skills</b><br>
<b>Security & Systems:</b> Linux Hardening, RMF/STIG, Wazuh, Fail2Ban<br>
<b>SIEM & Monitoring:</b> Splunk, Prometheus, Grafana<br>
<b>Automation & IaC:</b> Ansible, Terraform, GitHub Actions<br>
<b>Containers & Networking:</b> Docker, Traefik, NGINX, DNS<br>
<b>IAM:</b> AWS IAM, GCP IAM, Active Directory
</p>

</div>



<h3>Featured Projects</h3>

<table align="center" width="85%">
  <tr>
    <td align="left">
      <b>Proxmox VM Provisioning & Secure Access Pipeline</b><br>
      Designed and implemented an end-to-end automation pipeline to provision, secure, and monitor virtual machines on Proxmox VE using Infrastructure as Code and CI/CD practices. The pipeline creates VMs from templates, configures secure SSH access using Vault-issued certificates, updates SSH client configuration, and automatically registers new hosts with Prometheus monitoring.<br>
      <b>Tech: </b>Proxmox VE, Terraform, Ansible, Jenkins, HashiCorp Vault (SSH CA), Prometheus<br>
      <b>Outcome: </b>Fully automated VM lifecycle with no manual provisioning, no static SSH keys, centralized access control, and immediate observability for every new system.<br>
      <b>GitHub: </b>
      <a href="https://github.com/mikecozier/proxmox-terraform-ansible-jenkins-create-vm" target="_blank">
        github.com/mikecozier/proxmox-terraform-ansible-jenkins-create-vm
      </a>
    </td>
  </tr>
</table>

<table align="center" width="85%">
  <tr>
    <td align="left">
      <b>Proxmox VM Decommissioning Pipeline (Jenkins)</b><br>
      Built a safety-first CI/CD pipeline to automate virtual machine decommissioning on Proxmox VE using the Proxmox REST API. The pipeline enforces strict validation and confirmation guardrails, cleans up monitoring dependencies, performs graceful shutdowns, and ensures complete resource removal without orphaned disks or stale configurations.<br>
      <b>Tech: </b>Jenkins (Declarative Pipeline), Proxmox VE REST API, Bash, Python, Prometheus, Docker Compose, SSH, jq<br>
      <b>Outcome: </b>Controlled, auditable VM deletion with dependency-aware cleanup, reduced human error, and enterprise-style safeguards for destructive infrastructure operations.<br>
      <b>GitHub: </b>
      <a href="https://github.com/mikecozier/proxmox-terraform-ansible-jenkins-delete-vm" target="_blank">
        github.com/mikecozier/proxmox-terraform-ansible-jenkins-delete-vm
      </a>
    </td>
  </tr>
</table>

<table align="center" width="85%">
  <tr>
    <td align="left">
      <b>DevOps Monitoring & Reverse Proxy Stack</b><br>
      Designed and implemented a production-style Docker Compose stack to provide secure ingress, observability, and centralized logging for a home lab / server environment. The project integrates Traefik as a reverse proxy with automatic HTTPS, Prometheus for metrics collection, Grafana for visualization, Loki and Promtail for log aggregation, and Pi-hole for DNS filtering. All services are routed through Traefik with TLS, rate limiting, security headers, and optional BasicAuth to mirror real-world DevOps infrastructure patterns.<br>
      <b>Tech: </b>Docker, Docker Compose, Traefik, Cloudflare DNS, Pi-hole, Prometheus, Grafana, Loki, Promtail, NGINX, Linux, TLS/ACME, Reverse Proxies, Observability<br>
      <b>Outcome: </b>Delivered a modular, secure, and fully observable containerized infrastructure showcasing best practices in reverse proxy design, monitoring, logging, and environment-based configuration, suitable for homelab and production-style DevOps demonstrations.<br>
      <b>GitHub: </b>
      <a href="https://github.com/mikecozier/docker-traefik-stack" target="_blank">
        github.com/mikecozier/docker-traefik-stack
      </a>
    </td>
  </tr>
</table>

<details>
  <summary><b>Additional Infrastructure & Monitoring Projects</b> (click to expand)</summary>
  <br>
  
<table align="center" width="85%">
  <tr>
    <td align="left">
      <b>Linux Server Monitoring with Prometheus & Grafana (Dockerized)</b><br>
      Designed and deployed a containerized infrastructure monitoring stack using Prometheus and Grafana to collect, store, and visualize real-time Linux server metrics. The project leverages Node Exporter for host-level observability, providing visibility into CPU, memory, disk, and network performance across a homelab environment.<br>
      <b>Tech: </b>Prometheus, Grafana, Node Exporter, Docker, Docker Compose, Linux, YAML<br>
      <b>Outcome: </b>Delivered a portable, production-style monitoring solution with persistent metrics storage and dashboard-driven visibility, forming a foundation for alerting, capacity planning, and incident response.<br>
      <b>GitHub: </b>
      <a href="https://github.com/mikecozier/Grafana_Prometheus_Setup" target="_blank">
        github.com/mikecozier/Grafana_Prometheus_Setup
      </a>
    </td>
  </tr>
</table>

<table align="center" width="85%">
  <tr>
    <td align="left">
      <b>Linux Server System Report & Alerting Script</b><br>
      Developed a comprehensive Bash-based system health reporting script for Linux servers that collects real-time operational metrics and emails a detailed status report. The script monitors connectivity, interfaces, resource utilization, temperatures, disk and inode usage, active users, and failed SSH login attempts to provide proactive visibility into server health and security.<br>
      <b>Tech: </b>Bash, Linux, lm-sensors, ifstat, journalctl, mutt, Cron, awk, grep, ps, df, free, uptime<br>
      <b>Outcome: </b>Automated daily server health reporting with early warning indicators for performance, storage, and security issues, reducing the need for manual system checks.<br>
      <b>GitHub: </b>
      <a href="https://github.com/mikecozier/Server-Stat-Script" target="_blank">
        github.com/mikecozier/Server-Stat-Script
      </a>
    </td>
  </tr>
</table>

</details>

<p>
I'm passionate about building secure, reliable systems — always learning, always building.
</p>

<p>
<a href="https://michaelcozier.com">michaelcozier.com</a> | 💬 <i>Let's connect!</i>
</p>

</div>


<p align="center">
  <a href="https://github.com/mikecozier">
    <img src="https://img.shields.io/github/followers/mikecozier" />
  </a>
  <a href="https://www.linkedin.com/in/michael-cozier">
    <img src="https://img.shields.io/badge/Linkedin-Michael_Cozier-blue" />
  </a>
</p>

<img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/devSouvik/devSouvik/master/gif3.gif">

- All of my projects are available at [https://github.com/mikecozier](https://github.com/mikecozier)  
- Ask me about **DevOps & Cloud DevOps**  
- How to reach me **michael@michaelcozier.com**

---

<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/michael-cozier" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
</p>

---

<h3 align="left">Languages and Tools:</h3>

<p align="left">
<b>Cloud:</b><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/googlecloud/googlecloud-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original.svg" width="40"/>
</p>

<p align="left">
<b>DevOps & Automation:</b><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vault/vault-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/terraform/terraform-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/ansible/ansible-original.svg" width="40"/>
</p>

<p align="left">
<b>Systems & Networking:</b><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" width="40"/>
</p>

<p align="left">
<b>Languages & Databases:</b><br>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bash/bash-original.svg" width="40"/>
</p>
