# Telegram X — Random APK Builder

Har safar build qilganingizda **yangi nom va package ID** bilan APK yaratadi.
Bir telefonga **10 tagacha** alohida Telegram X o'rnatish mumkin.

## Ishlatish

1. GitHub'da Actions → **Build Random Telegram X APK** → **Run workflow**
2. Ixtiyoriy: o'z nomingizni kiriting (bo'sh qolsa random bo'ladi)
3. ~40-60 daqiqa kuting
4. **Artifacts** bo'limidan APK yuklab oling
5. Telefoningizda o'rnating

## Secrets (ixtiyoriy)

Agar o'z Telegram API kalitlaringizni ishlatmoqchi bo'lsangiz:
- `Settings → Secrets → Actions` ga boring
- `TELEGRAM_API_ID` va `TELEGRAM_API_HASH` qo'shing
- https://my.telegram.org dan olish mumkin
