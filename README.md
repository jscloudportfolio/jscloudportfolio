- 👋 Hi, I’m @jscloudportfolio
- 👀 I’m interested in ...Cloud Security
- 🌱 I’m currently learning ...IT Project Management, AWS Cloud Solutions Architect Associate, Cloudflare, Security+ 
- 💞️ I’m looking to collaborate on ...I'm a newbie hear just learning by doing, breaking things, trying to fix them and will reach out to the community for help and will give back where I can to help others coming after me!
- 📫 How to reach me ...working on this...
- 😄 Pronouns: ... he/him
- ⚡ Fun fact: ... idk at the moment - working on this lol
- ⚡ See my first project below!
<!---
jscloudportfolio/jscloudportfolio is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

**Project Purpose:** I wanted to get hands-on experience with Cloudflare's DNS service. I learned so much through this project! I wanted to share with you what I did.

******My Project (What I built)**:****
I created and hosted a static website on Github. I then pointed the site to my Cloudflare registered domain and set up the DNS records to be able to optimize my site with Cloudflare services.

**My Github Pages Static website:** https://jscloudportfolio.github.io/

**My Cloudflare Registered Domain:** jstechportfolio.com

**The web address I will send people to in order to view my site:** www.jstechportfolio.com This site will be updated in the near future to showcase my resume and links to technical projects. I have to learn more about writing using Jekyll markdown syntax to do so.

**STEPS BREAKDOWN**

**1.** Created a github repository and set it to 'public'. Link to my public github repository online that I will use for future projects after this one: js cloud portfolio.github.io
**2.** Created a simple static blog website using githubs "Pages" feature on the repository. (I learned that Github Pages uses Jekyll as the backend for its free website creation service. I was trying to write with html and spent an hour figuring out how to write in Jekyll and get the code to run!:-)!
**3.** Created a free Cloudflare account at https://www.cloudflare.com/plans/free/  **(woohoo!⚡)**
**4.** Registered the Domain - jstechportfolio.com ($10.44 per year)
**5.** Went into the settings of my Github Pages blog site and found the 'custom domain section' which provided me with the 4 IP Address that I needed to point Cloudflare to.
**6.** Returned to Cloudflare domain dashboard to update my DNS settings for jstechportfolio.com
**7.** Created 5 DNS records (4 "A"  records for the github IP Addresses, 1 "CNAME" record for www.jsloudportfolio.github.io - note: jscloudportfolio is my github username)
**8.** Saved each record.
**9.** Went back to github to run a DNS Check within the settings tab. Status: "DNS Check Successful"
**10.** I confirmed my DNS updates have taken effect via this DNS Lookup Tool - - https://dnschecker.org/#A/www.jstechportfolio.com- https://dnschecker.org/all-dns-records-of-domain.php?query=www.jstechportfolio.com%2F&rtype=ALL&dns=google

**Notes:** 
- Forgive me if I am using the wrong terminology here - But believe the A name DNS records resolved within a few minutes however the 'CNAME' record is still not showing up on the look up tool.
- Next I would like to make sure HTTPS is enabled for my site. I am not sure how to do this but it looks like github has some directions for that. I am wondering if that is the benefit of routing my site to cloudflare..the HTTPS security will be enabled automatically through Cloudflares security service? 
