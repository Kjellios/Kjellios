I'm Kjell.
I build, break, and learn through hands-on infrastructure projects.

I use this GitHub to keep track of what I’ve worked on, what I’ve figured out, and what I’m still learning—mostly focused on cloud, automation, and networking.

---

## Projects

### [AWS-Hosted Static Website](https://github.com/Kjellios/website-portfolio)
**Dec 2023 – Present**

Built and deployed a static portfolio site on AWS using S3, Route 53, CloudFront, and ACM. Everything is managed from my local machine, with Terraform handling the infrastructure and GitHub Actions automating the deploy process through OIDC.

– **Cloud Infrastructure:** Set up S3, Route 53, CloudFront, and ACM using Terraform
– **CI/CD Automation:** GitHub Actions configured with OIDC for secure, tokenless deployment
– **Security & DNS:** Managed IAM roles, TLS certs, and custom domain records through Route 53
– **Content Delivery:** Used CloudFront for HTTPS delivery and global caching
– **Local Workflow:** Infrastructure and pipeline fully managed and deployed from my personal system

**Skills:** Terraform · GitHub Actions · IAM · Route 53 · CloudFront · S3 · SSL/TLS · CI/CD · IaC · DNS management · static website hosting

---

### [Pi-hole DNS Filtering on Raspberry Pi with Docker](https://github.com/kjellios/project-pihole-public)
**Dec 2024 – Present**

Set up a DNS filtering and ad-blocking solution using Pi-hole in Docker on a Raspberry Pi 3 running Raspberry Pi OS Lite. The system runs on my local network behind an ASUS mesh router and helps reduce ads, improve privacy, and give visibility into DNS traffic across a$

– **Dockerized Deployment:** Ran Pi-hole using `docker-compose` with `network_mode: host` for full DNS support
– **Persistent Storage:** Mounted `/etc/pihole` and `/etc/dnsmasq.d` to local Git-tracked volumes
– **Router Integration:** Configured an ASUS router to use the Pi as its primary DNS resolver
– **Privacy Hardening:** Limited domain logging, blocked external fallback, and restricted access
– **Access & Admin:** SSH enabled with public key authentication. Admin UI available at `http://pi.hole/`

**Skills:** Docker · Router administration · Raspberry Pi OS · Docker Compose · Bash scripting · privacy & security hardening · Linux CLI · DNS configuration · network troubleshooting

---

## About Me
- Based in Minneapolis
- 2024 cloud engineering AAS, Dunwoody College of Technology
- Academic Excellence Award, 4× Dean’s List
- Currently pursuing entry-level roles in IT support or cloud/DevOps
- Portfolio: [kjellhysjulien.com](https://kjellhysjulien.com)

---

## Certifications
- AWS Certified Cloud Practitioner
- Microsoft Azure Fundamentals

---

## Contact
[LinkedIn](https://www.linkedin.com/in/kjell-hysjulien)