# Home Photo Server

A self-hosted photo management server using [PhotoPrism](https://photoprism.app/), running on Ubuntu Server with Docker and an external HDD. This setup is optimized for long-term photo archiving, organization, and easy hardware migration.

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
