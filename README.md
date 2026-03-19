# 🎂 Happy Birthday มุก — FastAPI Web App

## วิธีรัน

### 1. ติดตั้ง dependencies
```bash
pip install -r requirements.txt
```

### 2. รัน server
```bash
python main.py
```

หรือใช้ uvicorn โดยตรง:
```bash
uvicorn main:app --reload --host 0.0.0.0 --port 8000
```

### 3. เปิดเว็บ
ไปที่ http://localhost:8000 ได้เลย 🌸

---

## ฟีเจอร์

- 🎁 **Surprise overlay** — คลิกเปิดกล่องของขวัญ
- 🎉 **Confetti animation** — หลังเปิดซัพไพรส์
- 🕯️ **22 เทียน** — คลิก "เป่าเค้ก" ให้เทียนดับพร้อมกัน
- 💖 **Floating hearts** — หัวใจลอยตลอดเวลา
- 📋 **22 เหตุผล** ที่มุกพิเศษ
- 🌸 **Theme สีชมพู/rose** สวยงาม

## โครงสร้างไฟล์
```
happy_birthday_muk/
├── main.py           ← FastAPI app
├── requirements.txt  ← dependencies
├── README.md         ← ไฟล์นี้
└── templates/
    └── index.html    ← Birthday page
```
