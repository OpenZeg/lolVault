# .lol Vault v2

.lol Vault v2 is a secure, offline client-side encryption tool built as a **single HTML file**.

It uses **AES-256-GCM** with **PBKDF2 (250,000 iterations)** and optional **keyfile 2FA**.  
Encrypt images, videos, and any files locally — no server, no tracking, no data leaving your device.

Strong, simple, and fully auditable.

### Try It
- **Online demo**: [style.zeg.com.au/lol](https://style.zeg.com.au/lol)
- **Strongly recommended**: Download from GitHub and run it offline for maximum security.

### Features
- AES-256-GCM authenticated encryption
- PBKDF2 key derivation (250k iterations)
- Optional keyfile as second factor
- Batch encryption support
- Media preview after decryption
- Custom `.lol` binary format
- Completely client-side & offline

### Security Note
This tool is only as strong as your passphrase + keyfile handling. Use a strong unique passphrase and keep the keyfile separate from the encrypted files.

---

**License**  
Apache License 2.0 (credit appreciated)
