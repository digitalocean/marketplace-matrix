# Getting started after deploying Matrix

## Create your new server

Keep in mind when selecting a monthly plan that the more resources you can
provide, the better the chat quality will be. 2GB+ RAM is highly recommended.

## Setting up DNS

1. Login to your DNS provider
2. Add the following DNS records:
  A Record: `yourdomain.com -> your_droplet_public_ipv4`
  A Record: `matrix.yourdomain.com -> your_droplet_public_ipv4`
  A Record: `chat.yourdomain.com -> your_droplet_public_ipv4`
3. Wait approximately 5 minutes for the records to populate
4. When https://chat.yourdomain.com in your browser loads, DNS setup is complete

## Login

1. Login to your server via SSH: `ssh root@your_droplet_public_ipv4`
