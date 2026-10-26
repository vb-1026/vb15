Viloyatga Boramiz — server bilan ishlaydigan loyiha

Talab: Node.js 18 yoki yangiroq.

Ishga tushirish (Windows):
1. ZIP faylni to‘liq chiqarib oling.
2. Shu papkada terminal/PowerShell oching.
3. npm start buyrug‘ini kiriting (yoki node server.js).
4. Brauzerda http://localhost:3000 ni oching.

API va ma’lumotlar:
- GET /api/health — server holati
- POST /api/accounts — foydalanuvchi ma’lumotlarini saqlash
- GET/POST /api/drivers — haydovchi e’lonlarini olish/saqlash
- GET/POST /api/bookings — bronlarni olish/yaratish
- DELETE /api/bookings/:id — bronni bekor qilish
- Ma’lumotlar data.json faylida saqlanadi.

MUHIM:
- Saytni file:// orqali emas, http://localhost:3000 orqali oching.
- Server ma’lumotlarni bir xil serverga ulangan foydalanuvchilar o‘rtasida ulashadi.
- Internetga chiqarish uchun Node.js qo‘llaydigan hostingga joylash va doimiy disk/database sozlash kerak.
- Bu boshlang‘ich backend: production uchun parol/OTP autentifikatsiyasi, email/telefon tasdiqlash, HTTPS, rate limit va haqiqiy ma’lumotlar bazasi qo‘shilishi kerak.
- Karta to‘lovi hozir ulanmagan. Karta raqami/CVV kiritmang.
- Haydovchi e’lonlari serverga jo‘natilishi uchun haydovchi profilidagi e’lonni saqlash amali backend API bilan integratsiya qilinishi kerak.
