# KF-tbcrawler

# **ποΈ**Instroduction

KF-tbcrawlerμ λλ ν λ¦¬ κ΅¬μ‘°λ λ€μκ³Ό κ°μ΅λλ€:

```
tor-browser-crawler-master
βββ πbin
β   βββ tbcrawler.py
βββ πtbcrawler
β   βββ __init__.py
β   βββ common.py
β   βββ crawler.py #screenshot chapture
β   βββ dumputils.py
β   βββ log.py
β   βββ pytbcrawler.py
β   βββ torcontroller.py #Tor network interface
β   βββ style.css
βββ Dockerfile #docker container λ΄λΆμμ crawler μ€ν κ΄λ¦¬
βββ Entrypoint.sh #Docker containerμ μ€ν κ΄λ¦¬
βββ Makefile #buildμ run μ€μ 
βββ config.ini #batchesμ visits μ μ€μ 
βββ requirements.txt #νλ‘μ νΈ λ΄μ import ν  λΌμ΄λΈλ¬λ¦¬ κ΄λ¦¬
βββ setup.py
βββ sites.txt #Keywordlist
```

# **βοΈ**Settings

KeywordFingerprinting νλ‘μ νΈλ₯Ό μ¬μ©νκΈ° μν΄ λ€μκ³Ό κ°μ Docker μ€μ μ΄ νμν©λλ€:

### **Docker Ubuntu Linux installation**

```bash
sudo apt-get update
sudo apt-get install docker.io
sudo systemctl start docker
sudo systemctl enable docker
```

### Give permission to β/var/run/docker.sockβ

```bash
sudo chmod -R 777 /var/run/docker.sock
```

### Give permission to βhome/docker/tbcrawl/Entrypoint.shβ

```bash
sudo chmod +x Entrypoint.sh
```
