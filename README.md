```bash
Last login: Thu Jul 23 08:34:14 on ttys002
visitor@github-portfolio:~$ ./load_profile.sh

Initializing system configuration...
[██████████████████████████████] 100% - Profile loaded successfully.

visitor@github-portfolio:~$ cat /etc/profile.d/developer.json

{
  "user": "Muhammad Razi Imran",
  "alias": "RaziImran",
  "status": "Coding & Shipping",
  "location": "Karachi, Pakistan",
  "core_languages": ["JavaScript", "TypeScript", "Python"],
  "frameworks": ["React", "Flask"],
  "tools": ["Git", "Docker", "VS Code", "Linux"]
}

visitor@github-portfolio:~$ curl -s [https://api.github.com/users/RaziImran/stats](https://api.github.com/users/RaziImran/stats)

Status: Online & Ready to Collaborate
Repositories: 15+ Public Repos
Focus: Full-Stack Development & Open Source

visitor@github-portfolio:~$ ping -c 1 social-links.sh

[+] CONNECTING TO CHANNELS:
 ├── [GitHub]    ---> [github.com/yourusername](https://github.com/RaziImran)
 ├── [LinkedIn]  ---> [linkedin.com/in/yourusername](https://linkedin.com/in/yourusername)
 └── [Website]   ---> yourwebsite.com

visitor@github-portfolio:~$ exit
logout
[Process completed]
