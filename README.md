# Homelab Infrastructure

Self-hosted services running on home server with WireGuard VPN.

## Services

- **Caddy**: Reverse Proxy
- **Vaultwarden**: Self-hosted password manager
- **Immich**: Photo cloud

## Setup

1. Clone repo
2. Copy `.env.example` to `.env` in each service
3. Fill in your values
4. `docker compose up -d`

## Security

- All services accessible only via WireGuard VPN
- Firewall blocks external access
- Secrets managed via .env files (not committed)
