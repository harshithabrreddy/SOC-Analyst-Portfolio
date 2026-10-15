#  Harshitha BR | SOC Analyst Portfolio

A personal portfolio website for an entry-level **SOC Analyst (L1/L2)** and blue team candidate. It brings together my security projects, blog posts, education, certifications and learning roadmap in one page.

**Live site:** _add your Netlify or Vercel link here after you publish_

## About me

I am a cybersecurity enthusiast with a B.Tech in Computer Science and Cybersecurity, building blue team skills through hands-on labs and projects. I want to start in a Security Operations Center and grow toward detection engineering.

**Roles I am targeting:** SOC Analyst L1/L2, Cybersecurity Analyst, Blue Team Analyst, Incident Response trainee, and threat hunting beginner roles.

## What is on the site

| Section | What it shows |
|---|---|
| Home | A replay of my SSH brute-force lab, showing how a detection rule turns failed logins into an alert |
| About | Short introduction, education summary and target roles |
| Case files | Three projects with what I did, the detection logic and links to each repository |
| Blog and SOC notes | Beginner-friendly write-ups with a table of contents and key takeaways |
| Toolkit | The tools I have used, grouped by job |
| Experience and certifications | A 2026 timeline with my internship, training and badge |
| Education and learning | B.Tech details and my TryHackMe learning path |
| Resources | Platforms and references I recommend |
| Roadmap | My short, mid and long term goals |
| Contact | Email, phone, LinkedIn and GitHub |

## Projects featured

- **SSH Brute-Force Detection and Investigation:** a Python detector that raises a HIGH severity alert for 5 or more failed SSH logins from one IP within 60 seconds, with MITRE ATT&CK mapping (T1110.001) and an incident report. [Repository](https://github.com/harshithabrreddy/SSH-brute-force-detection-and-investigation-lab)
- **Failed Login Detection in Splunk:** Windows Security logs sent to Splunk Enterprise and searched with SPL for failed logons (Event ID 4625) and successful logons (Event ID 4624). [Repository](https://github.com/harshithabrreddy/Failed-Login-Detection-Using-Splunk)
- **Phishing Email Analysis:** analysis of a phishing sample, identifying the fake sender, suspicious URL, urgency language, malicious attachment and social engineering tactics. [Repository](https://github.com/harshithabrreddy/Phishing-Email-Analysis)

## Blog posts

- Setting Up a SOC Home Lab as a Beginner
- SSH Brute-Force Detection Using Ubuntu
- How I Investigate a Phishing Email

## Skills and tools

- **SIEM and log analysis:** Splunk, Windows event logs, Linux auth logs
- **Threat intelligence:** VirusTotal, MITRE ATT&CK
- **Network analysis:** Wireshark, Nmap
- **Web security testing:** Burp Suite
- **Systems and scripting:** Kali Linux, Ubuntu, Python
- **Practice platforms:** TryHackMe, Hack The Box

## Certifications and experience

- Cybersecurity Fundamentals, IBM SkillsBuild (issued 21 March 2026)
- Cyber Security Certification Training, Skillogic (16 Feb to 30 Apr 2026, 40 hours)
- Cybersecurity intern, Digitdefence (16 Mar to 16 Jul 2026)

## Tech used to build the site

- A single `index.html` file with plain HTML, CSS and JavaScript
- No frameworks, no build step and no dependencies
- Fonts (Archivo and JetBrains Mono) loaded from Google Fonts
- Responsive layout for phone, tablet and desktop
- Keyboard-friendly navigation, and animation that respects the reduced-motion setting

## Run it locally

1. Download or clone this repository.
2. Open `index.html` in any web browser.

```bash
git clone https://github.com/harshithabrreddy/soc-portfolio.git
cd soc-portfolio
# then open index.html in your browser
```

## Deploy it

The site is a static page, so any static host works.

- **Netlify:** sign in with GitHub, choose Add new project, import this repository and click Deploy.
- **Vercel:** import this repository and deploy with the default settings.
- **GitHub Pages:** in the repository go to Settings, then Pages, choose the main branch and the root folder, and save.

## Updating the content

All content is inside `index.html`. Open it on GitHub, click the pencil icon, edit the text, and commit. Netlify and Vercel republish automatically.

## Contact

- **Email:** harshithabrreddy@gmail.com
- **LinkedIn:** [www.linkedin.com/in/brharshitha](www.linkedin.com/in/brharshitha)
- **GitHub:** [github.com/harshithabrreddy](https://github.com/harshithabrreddy)

I am open to SOC Analyst L1 and entry-level cybersecurity roles.
