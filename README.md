# ifs24032-pabwe2026-sk-p5-vue

Delcom Auction - aplikasi lelang online (Vue 3, JavaScript, Pinia, Tailwind CSS v4, Vitest).

## Menjalankan

```bash
bun install
cp .env.example .env   # sesuaikan jika perlu
bun run dev            # http://localhost:3000
```

## Pengujian

```bash
bun run test:coverage  # threshold 100% (statements, branches, functions, lines)
```

Laporan coverage: `coverage/lcov.info`.

## Deploy (Vercel)

Nama project Vercel: `ifs24032-pabwe2026-sk-p5-vue` agar URL sesuai batas prefix penilaian.
Build command `bun run build`, output `dist`. `vercel.json` sudah berisi SPA rewrite dan security headers.
