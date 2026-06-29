# 🛠️ Практик Даалгавар — VibeCoding Сургалт

## Оролцогчдод зориулсан алхмуудын жагсаалт

---

## ✅ Алхам 1 — GitHub бүртгэл (10 мин)

**Хийх зүйл:**
1. [github.com](https://github.com) руу орно
2. "Sign up" → имэйл, нууц үг, username оруулна
3. Username нэрлэх дүрэм: **товч, мэргэжлийн, тоогүй**
   - ✅ Сайн: `munkh-dev`, `boldbaatar-codes`
   - ❌ Муу: `munkh1234`, `user_99`
4. Имэйл баталгаажуулна

**Шалгах асуулт:** `github.com/таны-нэр` хаягаар ороход профайл харагдаж байна уу?

---

## ✅ Алхам 2 — Repository үүсгэх (5 мин)

**Хийх зүйл:**
1. Нэвтэрсний дараа баруун дээр "+" → "New repository"
2. Name: `my-portfolio`
3. Public сонгох ✓
4. "Add a README file" чекбокс ✓
5. "Create repository" дарна

**ТРЮК:** Шинэ репозиторид орчихоод гарын дэвтэр дээр **"." (цэг)** дар → VS Code хөтчөөр нээгдэнэ!

---

## ✅ Алхам 3 — ViteJS төсөл (15 мин)

VS Code-ийн terminal дээр:

```bash
npm create vite@latest my-portfolio -- --template vanilla
cd my-portfolio
npm install
npm run dev
```

Хөтчөөр `http://localhost:5173` нээхэд "Vite + Vanilla" харагдана.

**AI Prompt (ChatGPT эсвэл Copilot-д өг):**
```
Надад энгийн portfolio хуудас хийгээд өг.
Дараах хэсгүүд байгаасай:
- Header: нэр + мэргэжлийн гарчиг
- About: 2 өгүүлбэр танилцуулга
- Skills: 3 ур чадвар card-аар
- Contact: имэйл линк
CSS-ийг мөн адил файлд байгаасай. Өнгө: хар дэвсгэр, нэг accent өнгө.
```

---

## ✅ Алхам 4 — GitHub-руу Push (5 мин)

```bash
git init
git remote add origin https://github.com/ТАНЫ-НЭР/my-portfolio.git
git add .
git commit -m "Portfolio эхний хувилбар"
git push -u origin main
```

GitHub дээр файлууд харагдаж байна уу? → ✓ Амжилттай!

---

## ✅ Алхам 5 — Vercel Deploy (5 мин)

1. [vercel.com](https://vercel.com) → "Sign up with GitHub"
2. "Add New Project" → `my-portfolio` сонгоно
3. Framework: Vite (автоматаар танина)
4. "Deploy" → 30-60 секунд хүлээнэ
5. URL авна: `my-portfolio.vercel.app`

**Туршилт:** URL-г мессенжерт явуулж, утсан дээрээ нээнэ!

---

## 🎯 Бонус Даалгаврууд

| Даалгавар | Хүнд байдал |
|-----------|-------------|
| Нэрийн хуудсан дээр зургаа нэм | ⭐ |
| Hover effect нэм | ⭐⭐ |
| GitHub Pages-ээр ч байршуул | ⭐⭐ |
| Custom domain (avaialble.mn) холбох | ⭐⭐⭐ |
| Dark/Light mode toggle нэм | ⭐⭐⭐ |

---

## 📌 Хэрэгтэй линкүүд

- GitHub: https://github.com
- VS Code Online: https://vscode.dev
- Vercel: https://vercel.com
- ViteJS: https://vitejs.dev
- ChatGPT: https://chat.openai.com

---

*Uvs ITHub · MorningTalk · #VibeCoding*
