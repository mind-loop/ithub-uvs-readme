# 🚀 VibeCoding Portfolio — README & AI Prompt Guide

> **Сургалтын workflow:** GitHub repo үүсгэ → README дээр "." дар → github.dev нээгдэнэ → `index.html` үүсгэ → AI prompt-г ашиглан код авна → Vercel deploy

---

## ⚡ Step 1 — GitHub Repository Setup

1. Go to [github.com](https://github.com) → **New repository**
2. Name: `my-portfolio`
3. ✅ Public · ✅ Add a README file
4. **Create repository**
5. Press **`.`** (dot) on your keyboard → github.dev opens instantly

---

## 🤖 Step 2 — AI Prompt (Copy → Paste to ChatGPT / Copilot)

> Copy the prompt below, fill in your `[...]` values, then paste into ChatGPT or GitHub Copilot Chat.

---

```
You are an expert front-end developer. Create a complete, single-file portfolio website using only HTML and CSS (no frameworks, no JavaScript required).

The file must be named index.html and include all CSS inside a <style> tag.

=== PERSONAL INFORMATION ===
Name:         [YOUR FULL NAME]
Title:        [YOUR JOB TITLE / ROLE]  
             e.g. "Software Engineer" | "UI/UX Designer" | "CS Student"
Location:     [YOUR CITY, COUNTRY]
Email:        [YOUR EMAIL]
GitHub:       https://github.com/[YOUR-USERNAME]
LinkedIn:     https://linkedin.com/in/[YOUR-USERNAME]   (delete if not applicable)
Bio:          [2–3 sentences about yourself and what you do]

=== SKILLS ===
(List 4–8 skills with proficiency level: Beginner / Intermediate / Advanced)
Skill 1:  [e.g. Python — Advanced]
Skill 2:  [e.g. HTML/CSS — Advanced]
Skill 3:  [e.g. JavaScript — Intermediate]
Skill 4:  [e.g. Git & GitHub — Intermediate]
Skill 5:  [e.g. Figma — Beginner]

=== PROJECTS ===
(Add 1–3 projects. Delete rows you don't need.)
Project 1:
  Title:       [PROJECT NAME]
  Description: [1–2 sentences about what it does]
  Tech stack:  [e.g. HTML, CSS, JavaScript]
  Live URL:    [https://... or delete this line]
  GitHub URL:  [https://github.com/... or delete this line]

Project 2:
  Title:       [PROJECT NAME]
  Description: [1–2 sentences about what it does]
  Tech stack:  [e.g. Python, Flask]
  Live URL:    [https://... or delete this line]
  GitHub URL:  [https://github.com/... or delete this line]

=== DESIGN PREFERENCES ===
Color scheme: [e.g. Dark with purple accent / Light minimal / Blue & white]
Style:        [e.g. Modern & clean / Creative / Corporate / Minimalist]
Font feel:    [e.g. Technical / Friendly / Professional]

=== SECTIONS TO INCLUDE ===
✅ Hero — name, title, short bio, contact buttons
✅ Skills — visual skill cards or progress bars
✅ Projects — cards with description, tech stack, links
✅ Contact — email link, GitHub, LinkedIn icons (use emoji or simple text icons)
✅ Footer — copyright line

=== TECHNICAL REQUIREMENTS ===
- Single file: index.html with <style> embedded (no external CSS files)
- Mobile responsive using CSS media queries
- Smooth scroll behavior
- Hover effects on cards and buttons
- Clean semantic HTML5 structure
- NO JavaScript required (pure CSS interactions only)
- NO external libraries or CDN links

Output ONLY the complete index.html file. No explanation, no markdown code blocks.
```

---

## 📋 Step 3 — Өөрийн мэдээллийг бөглөх жишээ

```
Name:         Пүрэв Баасанхүү
Title:        Full-Stack Developer & CS Graduate
Location:     Ulaanbaatar, Mongolia
Email:        purevsuren@example.com
GitHub:       https://github.com/purevsuren-dev
Bio:          I am a Computer Science graduate from MUST University (2019).
              I build web applications and love combining AI tools with
              modern development workflows to ship products faster.

Skills:
  Python       — Advanced
  JavaScript   — Intermediate
  HTML/CSS     — Advanced
  Git & GitHub — Advanced
  VS Code      — Advanced

Projects:
  Project 1:
    Title:       Personal Portfolio
    Description: A responsive portfolio website built with HTML, CSS,
                 and deployed via Vercel in under 1 hour.
    Tech stack:  HTML, CSS, GitHub, Vercel
    GitHub URL:  https://github.com/purevsuren-dev/my-portfolio

Color scheme: Dark background with cyan/teal accent
Style:        Modern & clean, developer-focused
Font feel:    Technical but approachable
```

---

## 🖥️ Step 4 — github.dev дээр файл үүсгэх

1. AI-н гаргасан кодыг **бүгдийг нь** copy хийнэ
2. github.dev дээр зүүн талын Explorer → **New File** → `index.html`
3. Paste хийнэ → **Ctrl+S** хадгална
4. Source Control (⎇) → `+` → Commit message: `"Add portfolio"` → **Commit & Push**

---

## 🚀 Step 5 — Vercel Deploy

1. [vercel.com](https://vercel.com) → **Sign up with GitHub**
2. **Add New Project** → `my-portfolio` сонгоно
3. Framework: **Other** (HTML file тул)
4. **Deploy** → 30 секунд → URL авна 🎉

---

## ✅ Амжилтын шалгуур

| Алхам | Шалгах зүйл |
|-------|-------------|
| GitHub repo | `github.com/таны-нэр/my-portfolio` ажиллаж байна |
| github.dev | `index.html` файл үүссэн, код харагдаж байна |
| Vercel | `my-portfolio.vercel.app` хөтчөөр нээгдэж байна |
| Утсан дээр | URL нээхэд portfolio харагдаж байна 📱 |

---

*Uvs ITHub · MorningTalk · #VibeCoding · #GitHub · #WebDev*