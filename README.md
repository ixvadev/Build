# `npm run build` Haqida To'liq Ma'lumot

`npm run build` buyrug'i JavaScript/Node.js loyihalarida ishlab chiqarish uchun dastur yoki veb-saytni tayyorlash jarayonini ifodalaydi. Quyida ushbu jarayonning barcha asosiy jihatlari tushuntirilgan.

## `npm run build` Nima?

`npm run build` buyrug'i loyihaning ishlab chiqarish versiyasini yaratish uchun ishlatiladi. Bu jarayon davomida dastur manba kodi ishlab chiqarish muhitiga mos formatga o'zgartiriladi. Odatda bu quyidagi qadamlarni o'z ichiga oladi:

- **JavaScript fayllarini birlashtirish va optimallashtirish.**
- **CSS fayllarini minifikatsiya qilish.**
- **Rasmlar va boshqa statik resurslarni optimallashtirish.**
- **Zamonaviy JavaScript (ES6+) kodingizni eski formatga (ES5) transpilyatsiya qilish.**

## Build Jarayoni Komponentlari

### 1. **JavaScript Fayllarini Birlashtirish va Bundling**
   - **Webpack**, **Rollup**, yoki **Parcel** kabi vositalar JavaScript fayllarini bitta yoki bir nechta paketlarga birlashtiradi.
   - Bu jarayon kodingizni birlashtirib, undan ortiqcha kodlarni olib tashlaydi va yuklash vaqtini tezlashtiradi.

### 2. **Transpilyatsiya**
   - **Babel** kabi transpilyatorlar zamonaviy JavaScript (ES6+) kodini eski brauzerlar bilan mos keladigan formatga (ES5) o'zgartiradi. Bu, brauzerlar orasida maksimal moslashuvchanlikni ta'minlaydi.

### 3. **CSS Fayllarini Minifikatsiya Qilish**
   - Build jarayonida CSS fayllari minifikatsiya qilinadi, ya'ni ularning hajmi kamaytiriladi va ular tezroq yuklanadi. Bu jarayon CSS fayllaridan ortiqcha bo'shliqlar va kommentlarni olib tashlaydi.

### 4. **Statik Resurslarni Optimallashtirish**
   - Rasmlar, shriftlar va boshqa statik resurslar build jarayonida optimallashtiriladi. Bu, fayl hajmlarini kamaytirish va ularning yuklanish vaqtini tezlashtirish uchun amalga oshiriladi.

### 5. **HTML Fayllarni Tayyorlash**
   - HTML fayllar, agar kerak bo'lsa, build jarayonida optimallashtiriladi. Bu yerda `index.html` kabi fayllar ichidagi skript va uslublar fayllariga havolalar to'g'ri yo'naltiriladi va kerakli atributlar qo'shiladi.

## Build Jarayonini Ishga Tushirish

Build jarayonini ishga tushirish uchun quyidagi buyruqni terminalda bajarish kerak:

```bash
npm run build
