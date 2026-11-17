## Hi, I'm Gabriel 👋

**IT Infrastructure & Network Analyst** in São Paulo, Brazil. I run the entire IT of a manufacturing company with multiple sites on my own: network and security, servers and virtualization, monitoring, service desk and endpoint management. I also build the tools that are missing.

My rule of thumb: **monitor everything, automate what repeats, and prove it works** (a backup that was never restored is just a hope).

### What I work with

| Area | Tools |
|---|---|
| Network & security | Fortinet FortiGate, SD-WAN, IPsec site-to-site VPNs, VLANs, RADIUS / captive portal |
| Servers & virtualization | Proxmox VE, Windows Server, Active Directory, GPO, Entra ID, SQL Server, RDS, Synology NAS |
| Monitoring & observability | Zabbix, Grafana, InfluxDB, PostgreSQL |
| Endpoint & service management | GLPI, Tactical RMM, Kaspersky Security Center, Windows LAPS, Chocolatey |
| Automation & development | PowerShell, Python, C# / .NET, ASP.NET Core, React + TypeScript, REST APIs, Docker |

### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [proxmox-backup-monitor](https://github.com/gabrielsilva-it/proxmox-backup-monitor) | Checks every minute that each VM is backed up on time, and restores backups at night into isolated VMs to prove they boot | Python · Proxmox · Zabbix · Grafana |
| [grafana-glpi-alerting](https://github.com/gabrielsilva-it/grafana-glpi-alerting) | Turns Grafana alerts into service-desk tickets with a real lifecycle: follow-ups, auto-close, reopen, flood and VPN-tunnel correlation | Python · Flask · GLPI API |
| [fleet-coverage-dashboard](https://github.com/gabrielsilva-it/fleet-coverage-dashboard) | Uses Active Directory as the source of truth and shows which PCs are missing the RMM agent, the inventory agent or the antivirus | Python · LDAP · InfluxDB · Grafana |
| [windows-server-toolkit](https://github.com/gabrielsilva-it/windows-server-toolkit) | Read-only diagnostics and safe repairs for production Windows Servers (RDP logon hangs, zombie sessions, temp profiles, crashes) | PowerShell |
| [self-service-app-store](https://github.com/gabrielsilva-it/self-service-app-store) | Internal app store: employees install approved software without admin rights, controlled by AD groups | .NET 8 · React · WPF · Chocolatey |
| [sip-softphone](https://github.com/gabrielsilva-it/sip-softphone) | SIP softphone with echo cancellation, plus a self-hosted hub for directory, chat, presence, video meetings and AI call summaries | .NET 8 · SignalR · Jitsi · Whisper |

All projects run (or ran) in production. The public versions are generic: no company names, hosts or credentials.

### Certifications & education

- Fortinet Certified Associate in Cybersecurity · Fortinet Certified Fundamentals in Cybersecurity
- Technologist in Computer Networks (Estácio) · Systems Analysis and Development, in progress (Estácio)

### Contact

[LinkedIn](https://www.linkedin.com/in/gabriel-silva-5932a6182/)

---

<details>
<summary>🇧🇷 Em português</summary>

Sou **Analista de Infraestrutura e Redes de TI** em São Paulo. Cuido sozinho de toda a TI de uma indústria com várias unidades:

- redes e segurança (Fortinet);
- servidores e virtualização (Proxmox, Windows Server, AD);
- monitoramento (Zabbix e Grafana);
- service desk (GLPI) e gestão do parque.

Quando falta uma ferramenta, eu crio: os projetos acima nasceram de problemas reais do dia a dia e rodam em produção. As versões públicas são genéricas, sem dados da empresa.

</details>
