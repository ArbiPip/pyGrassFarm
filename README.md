# pyGrassFarm&Reger 🔹


Discover the latest `<crypto/>` moves in my Telegram Channel: https://t.me/+zwYmIO6tBJVkOTQy 

Cheapest [proxies and servers](https://teletype.in/@web3enjoyer/4a2G9NuHssy) which fits for  on [grass.io](https://app.getgrass.io/register/?referralCode=8PAl7wCGN3Sfgpk).

![image](https://i.imgur.com/e4X1k5J.png)


### What is bot for?
   - Create Accounts
   - Farm Points
   - Check Points

> You can put as many proxies as u can, bot uses database and will load up proxies from extra ones

🔹**To say thanks for work: 0x05b84C97167cda9C7D8c77d7E1698ce9B4F9B393**


## Quick Start 📚
   1. To install libraries on Windows click on `INSTALL.bat` (or in console: `pip install -r requirements.txt`).
   2. To start bot use `START.bat` (or in console: `python main.py`).

### Options 📧

1. CREATE ACCOUNTS:
 - In `data/config.py` put `REGISTER_ACCOUNT_ONLY = True`
 - Provide emails and passwords (OPTIONAL) and proxies to register accounts as below!

  ![image](https://github.com/MsLolita/grass/assets/58307006/67740c9b-07d6-4f78-a87d-27b09c0303e8)

2. FARM POINTS:
 - in `data/config.py` put `REGISTER_ACCOUNT_ONLY = False`
 - Provide emails and passwords and proxies to register accounts as shown below!

### Configuration 📧

1. Accounts Setup 🔒

   Put in `data/accounts.txt` accounts in format email:password (grass_farm1@gmail.com:grssPassword1$)
   
   ![image](https://github.com/MsLolita/grass/assets/58307006/2f8bacaa-0212-49fe-b362-fe764230f47c)

2. Proxy Setup 🔒

   Configure your proxies with the *ANY* (socks, http/s, ...) format in `data/proxies.txt` 🌐

   ![Proxy Configuration](https://github.com/MsLolita/VeloData/assets/58307006/a2c95484-52b6-497a-b89e-73b89d953d8c)

## Quick Start By Docker
   1. Install Docker-CE: `curl -sSL -k https://get.docker.com | sh`
   2. Install Docker Compose: `curl -L "https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose`
   3. Clone Source Code: `git clone https://github.com/MsLolita/grass.git`
   4. Configuration: Modify `data/accounts.txt` and `data/proxies.txt`
   5. Start Container: `docker-compose up -d`

   PS: Could see more configuration in `docker-compose.yml`
