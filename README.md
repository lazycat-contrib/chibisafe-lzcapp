# Chibisafe (LazyCat LPK)

Self-hosted file hosting with albums, tags and a clean uploader.

- Upstream: https://github.com/chibisafe/chibisafe
- Images: `chibisafe/chibisafe-server` + `chibisafe/chibisafe` (mirror mode, digest-matched)
- License: MIT (full text in `content/licenses/LICENSE`)
- Containers: backend + frontend (Caddy from upstream compose is replaced by LZC upstreams)

## Notes
- Admin username is fixed `admin`; the password comes from a deploy param (random by default).
- No pre-seeded weak credential.
- Not yet verified on a real device.
