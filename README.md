# Afyniti Bot

**Versi:** 1.0.0 · **Harga:** Rp 100.000 (~$6) · **Kontak pembelian:** [@rmndkyl](https://t.me/rmndkyl)

Bot automation untuk project Afyniti ($WRP) - XP farming + daily check-in.

## Kebutuhan

| Item | Detail |
|---|---|
| Runtime | Node.js 18+ |
| Wallet | EVM / sesuai chain proyek (kamu sendiri) |
| Proxy | opsional (1 proxy per akun) |
| Captcha | tidak perlu |
| Akses | akun proyek yang kamu kelola sendiri |

## Pembayaran

E-Wallet: DANA / GoPay / ShopeePay · Bank: BCA / Seabank · Crypto: contact for wallet address.
Pembeli menghubungi [@rmndkyl](https://t.me/rmndkyl), kirim bukti transfer, lalu terima license key.

---

🌐 **Website:** https://afyniti.xyz

## Fitur

- Menu interaktif + `--daily` mode
- SIWE authentication (Sign-In with Ethereum)
- Auto complete quests (check-in, follow, CMC post)
- Multi-ecosystem (Afyniti, Amua, Telos, Efdot, Futurist)
- Real-time XP tracking

## Requirements

- Node.js v16+
- npm

## Setup

```bash
cd ~/LYID-BOTS/afyniti-bot
npm install
```

## Konfigurasi

3. **config.json** - Konfigurasi bot (referral code, delays, dll)

## Jalankan

```bash
# Menu interaktif
node index.js

# Auto daily mode
node index.js --daily
```

## Menu

1. Run all wallets (daily tasks) - Jalankan daily task untuk semua wallet
2. Run single wallet - Jalankan untuk 1 wallet saja
3. Check stats - Cek XP dan quests semua wallet
4. Public stats - Statistik platform Afyniti
5. Exit

## Chain Info

- Chain: Telos EVM (Chain ID: 40)
- RPC: https://rpc.telos.net/
- Token: $WRP

## Catatan

- Bot otomatis complete daily check-in dan quest yang bisa di-automate
- Quest yang butuh action manual (post tweet, join Discord) di-skip
- Delay random anti-detection sudah diatur di config.json

## Support

Telegram: @layerairdrop
Discord: discord.gg/ZK2NVkfSNn

## 💰 Harga

| Lisensi | Harga | Fitur |
|---------|-------|-------|
| **Single** | Rp 100.000 / ~$6 | 1 device, lifetime |
| **Bundle (3 bot)** | Rp 100.000 / ~$16 | Pilih 3 bot, hemat 20% |
| **Pro (semua bot)** | Rp 100.000 / ~$70 | Semua bot + update, hemat 30% |

**Cara beli:** Chat [@OG_LYID_bot](https://t.me/OG_LYID_bot) di Telegram → /buy

**Bayar pakai:**
- 🇮🇩 DANA / GoPay / ShopeePay / BCA / Seabank
- 🌐 Crypto (USDT/SOL/ETH)

## 🔧 Troubleshooting

| Masalah | Solusi |
|---------|--------|
| `Cannot find module` | Jalankan `npm install` di folder bot |
| `insufficient balance` | Pastikan wallet punya cukup token untuk gas |
| `429 Too Many Requests` | Tunggu 30-60 detik, bot auto-retry |
| Bot diam/tidak jalan | Cek `config.json` — pastikan API key valid |
| License invalid | Chat [@OG_LYID_bot](https://t.me/OG_LYID_bot) → /verify |

**Butuh bantuan?** Join [Discord](https://discord.gg/ZK2NVkfSNn) atau chat [@layerairdrop](https://t.me/layerairdrop)
