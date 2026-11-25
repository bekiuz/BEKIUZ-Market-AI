# BEKIUZ Market AI

O‘zbek tilida marketplace va ijtimoiy tarmoqlar uchun mahsulot e’lonini tayyorlaydigan yengil web-yordamchi.

## Hozirgi imkoniyatlar

- Mahsulot nomi, narxi, kategoriyasi, holati, xususiyatlari va auditoriyasini kiritish.
- Instagram, Telegram, Marketplace yoki Universal formatni tanlash.
- Cloudflare Worker orqali AI e’lon matnini yaratish.
- AI xizmati ishlamasa, kiritilgan faktlardan lokal shablon asosida e’lon tayyorlash.
- Hashtaglar, tayyor matn preview'i, nusxalash va TXT fayl sifatida yuklab olish.
- Formani tozalash va mobil ekranga mos ko‘rinish.

## Ishga tushirish

Statik web-app: `index.html` faylini brauzerda oching yoki GitHub Pages orqali joylashtiring.

## AI integratsiyasi

Brauzer quyidagi Cloudflare Worker manziliga `action: "market"` so‘rovi yuboradi:

`https://soft-glade-3782odiy-ai-tutor.bekiuz67.workers.dev`

Worker ishlamasa, ilova lokal generatorga qaytadi. AI javobining mavjudligi Worker holati, model limiti va tarmoq ulanishiga bog‘liq. Mahsulot faktlarini e’lonni joylashdan oldin tekshiring.

## Hozircha mavjud bo‘lmagan imkoniyatlar

- Mahsulot rasmini AI orqali tahlil qilish.
- E’lonlarni akkauntda yoki serverda saqlash.
- Marketplace akkauntlariga bevosita e’lon joylash.
- Bir nechta foydalanuvchi uchun jamoaviy boshqaruv.

## Keyingi bosqich

Rasm asosida tavsif, marketplace formatlari bo‘yicha aniq shablonlar, e’lonlar tarixi va foydalanuvchi akkauntlari.

Repo: https://github.com/bekiuz/BEKIUZ-Market-AI
