# Ragnarok ZERO — Affix Rating Tool

[![Hits](https://hits.sh/github.com/l3ank0187/ro-zero-affix-rating.svg)](https://hits.sh/github.com/l3ank0187/ro-zero-affix-rating/)

> เครื่องมือคำนวณคะแนนออปชั่น (Affix) สำหรับ Ragnarok ZERO แบบ 1-10 ดาว  
> A web-based affix rating calculator for Ragnarok ZERO with 1-10 star scoring.

---

## 🌐 Live Demo

- **GitHub Pages:** [https://l3ank0187.github.io/ro-zero-affix-rating/](https://l3ank0187.github.io/ro-zero-affix-rating/)
- **Custom Domain:** [https://rozg.online/](https://rozg.online/)

---

## ✨ Features

| ฟีเจอร์ | Feature |
|---------|---------|
| 🎮 รองรับอุปกรณ์หลายชนิด (Armor, Garment, Shoes, Weapon) | Supports multiple equipment types |
| ⭐ คำนวณคะแนน 1-10 ดาว อัตโนมัติ | Automatic 1-10 star rating |
| 🌏 รองรับ 2 ภาษา (ไทย / English) | Bilingual support (TH/EN) |
| 📊 แสดง % Roll เทียบกับค่าสูงสุด | Shows % Roll vs max value |
| 🎨 UI สวยงามด้วย Tailwind CSS | Beautiful UI with Tailwind CSS |
| ⚡ ทำงานฝั่ง Client ไม่ต้อง Server | Client-side only, no server needed |

---

## 🚀 Tech Stack

- **HTML5** — Semantic markup
- **Tailwind CSS** — Utility-first CSS framework
- **Vanilla JavaScript** — No framework needed
- **Cloudflare Pages** — Edge deployment
- **GitHub Pages** — Static hosting

---

## 🛠️ How to Use / วิธีใช้งาน

1. เลือก **แหล่งที่มาของ affix** (Monster Drop / MVP Drop)  
   Select **Affix Source** (Monster Drop / MVP Drop)

2. เลือก **ชนิดอุปกรณ์** (Armor / Garment / Shoes / Weapon)  
   Select **Equipment Type** (Armor / Garment / Shoes / Weapon)

3. เลือกออปชั่นที่ได้จากแต่ละช่อง  
   Select options from each slot

4. ระบบจะคำนวณคะแนนและระดับดาวให้ทันที!  
   The system will calculate the score and star rating instantly!

---

## 🌏 Language Switching / การสลับภาษา

กดปุ่ม **TH / EN** มุมขวาบนของหน้าเว็บเพื่อสลับภาษา  
Click the **TH / EN** button at the top right to switch languages.

---

## 📁 Project Structure

```
ro-zero-affix-rating/
├── index.html          # Main application file
├── README.md           # This file
└── .github/
    └── workflows/      # CI/CD (if any)
```

---

## 📝 Calculation Formula / สูตรคำนวณ

คะแนนคิดจาก % Roll ที่ได้ เทียบกับค่าสูงสุด ถ่วงน้ำหนักตามช่องและ Pool  
Score is calculated from % Roll compared to max value, weighted by slot and pool.

```
Score = Σ( (Roll_Value / Max_Value) × Slot_Weight × Pool_Multiplier )
```

---

## 🤝 Contributing

1. Fork โปรเจกต์นี้ / Fork this project
2. สร้าง branch ใหม่ / Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit การเปลี่ยนแปลง / Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push ไปที่ branch / Push to the branch (`git push origin feature/AmazingFeature`)
5. เปิด Pull Request / Open a Pull Request

---

## 📜 License

[MIT](LICENSE) © [l3ank0187](https://github.com/l3ank0187)

---

## 🙏 Credits

- **Ragnarok ZERO** — Gravity Interactive, Inc.
- **Tailwind CSS** — [tailwindcss.com](https://tailwindcss.com)
- **Prompt Font** — Google Fonts

---

<p align="center">
  Made with ❤️ for Ragnarok ZERO players
</p>
