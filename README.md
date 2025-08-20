# Home-Made Family Video/Photo Server

Do you also have a mother or family member that not only insists on having embarrassing photos of you throughout your entire life... but constantly uses old hardrives and usb sticks to manage them? What if she had all of his/hers over 150,000 photos and videos accessable via a very friendly GUI and facial recognition via tensorflow? No need to make my embarrassment any harder for my mother! Needless to say, this repository includes instructions and the tools needed to create a working self-hosted media management server using [PhotoPrism](https://photoprism.app/), running on Ubuntu Server with Docker and an external HDD for long-term storage, and a faster SSD for the Docker Image. This setup is optimized for long-term photo archiving, organization, and easy hardware migration.

## Features
- AI-powered photo tagging & search
- Automatic nightly backups
- Organized by date, year, and location
- Remote access with secure authentication
- Dockerized for easy replication

## Hardware
- Zotac ZBOX CI327 nano
- Intel Celeron N3450, 8GB RAM
- Seagate 8TB external HDD (USB 3.0) — main photo archive storage
- Samsung 1TB SSD (USB 3.0) — active working storage & faster processing for imports
- Gigabit Ethernet connection

## Quick Start
```bash
git clone https://github.com/Verax-rgb/home-photo-server.git
cd home-photo-server
cp env.example .env
./scripts/install.sh
