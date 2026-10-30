<<<<<<< HEAD
# 🎮 Helenboo Survivor

**Helenboo Survivor** คือเกมเว็บเบราว์เซอร์แนว Roguelite Survivor (สไตล์ Vampire Survivors) ในธีมภาพแบบ **Simple Shape** (เรขาคณิตคลีนๆ น่ารัก สดใส) พัฒนาด้วย **HTML5 Canvas, CSS3 และ JavaScript แบบ Single File (ไฟล์เดียวจบ)** ไม่ต้องติดตั้ง dependencies หรือ build tools ใดๆ สามารถเปิดเล่นได้ทันที และนำไป Deploy ขึ้น **GitHub Pages** ได้ฟรีใน 1 นาที!

---

## ✨ จุดเด่นของเกม (Features)

- **🎨 ดีไซน์ Simple Shape**: ตัวละคร **Helenboo** ทรงกลมน่ารักมีมงกุฎและแก้มชมพู ต่อสู้กับฝูงศัตรูรูปทรงเรขาคณิต (สามเหลี่ยม, สี่เหลี่ยม, ข้าวหลามตัด, แปดเหลี่ยม) พร้อมเอฟเฟกต์แสงนีออนและอนุภาคระเบิด (Particle Effects)
- **⚔️ ระบบอาวุธ Auto-Attack อัตโนมัติ**:
  - `Star Wand (คฑาดาว)`: ยิงลูกศรเวทมนตร์รูปสามเหลี่ยมติดตามศัตรูที่ใกล้ที่สุด
  - `Orbiting Stars (ดาวหมุน)`: สร้างดวงดาวหมุนวนรอบตัวฟาดฟันศัตรู
  - `Holy Aura (ออร่าศักดิ์สิทธิ์)`: ปล่อยคลื่นพลังวงแหวนผลักและสร้างความเสียหายรอบตัว
  - `Cross Boomerang (กางเขนบิน)`: ขว้างกางเขนหมุนทะลวงศัตรูแล้วบินย้อนกลับ
  - `Thunderbolt (สายฟ้าฟาด)`: สายฟ้าฟาดแบบสุ่มสร้างความเสียหายมหาศาล
- **🛡️ ระบบอัปเกรดสถานะ (Passives)**:
  - `Swift Boots`: เพิ่มความเร็วในการเดิน
  - `Vitality Heart`: เพิ่ม Max HP และฟื้นฟูเลือดอัตโนมัติ
  - `Power Crystal`: เพิ่มพลังโจมตีทุกอาวุธ
  - `Magnet Ring`: เพิ่มระยะดูดอัญมณี EXP
- **👾 ระบบเวฟศัตรูและบอสยักษ์ (Boss Fights)**: มีฝูงศัตรูหลากชนิด พร้อมบอสยักษ์แปดเหลี่ยมที่จะโผล่ออกมาสร้างความท้าทายทุกนาที
- **🔊 ระบบเสียงสังเคราะห์ในตัว (Web Audio API)**: สังเคราะห์เสียงเอฟเฟกต์ ยิง, ฟัน, เก็บเพชร, อัปเลเวล, ระเบิด โดยไม่ต้องใช้ไฟล์เสียง MP3/WAV ภายนอก ทำให้โหลดเร็ว ไม่มีปัญหาลิขสิทธิ์หรือลิงก์เสีย
- **📱 รองรับทั้ง PC และ มือถือ (Responsive & Touch Controls)**:
  - PC: ควบคุมด้วยปุ่ม `W A S D` หรือ `Arrow Keys`
  - Mobile / Tablet: มี Virtual Joystick ปรากฏบนหน้าจอสัมผัสอัตโนมัติ

---

## 🕹️ การควบคุม (Controls)

| ปุ่ม | คำสั่ง |
|------|--------|
| `W A S D` หรือ `ลูกศร` | บังคับการเดินของ Helenboo |
| `ระบบสัมผัส (Touch Screen)` | แตะแล้วลากเพื่อควบคุมด้วย Virtual Joystick |
| `P` หรือ `Esc` | หยุดเกมชั่วคราว (Pause) |
| `M` | เปิด/ปิดเสียง (Mute/Unmute) |

---

## 🚀 วิธีเปิดเล่นบนเครื่องของคุณ (Local)

1. ดาวน์โหลดหรือ clone โฟลเดอร์นี้
2. ดับเบิลคลิกเปิดไฟล์ `index.html` บนเบราว์เซอร์ใดก็ได้ (Chrome, Edge, Safari, Firefox)
3. กดปุ่ม **"เริ่มเล่นเกม (START)"** แล้วลุยได้ทันที!

---

## 🌐 วิธีการ Deploy ขึ้น GitHub Pages (ฟรี 100%)

คุณสามารถนำโค้ดชุดนี้ไปสร้างเป็นเว็บไซต์ที่ทุกคนทั่วโลกเข้าเล่นผ่านลิงก์ได้ โดยทำตามขั้นตอนดังนี้:

### ขั้นตอนที่ 1: เตรียม Git และ Push ขึ้น GitHub

เปิด Terminal หรือ PowerShell ในโฟลเดอร์นี้ แล้วรันคำสั่ง:

```bash
# 1. สร้าง git repository
git init

# 2. เพิ่มไฟล์ทั้งหมดเข้า git
git add .

# 3. commit ไฟล์
git commit -m "Initial release of Helenboo Survivor game"

# 4. เปลี่ยน branch หลักเป็น main
git branch -M main

# 5. เชื่อมต่อไปยัง GitHub Repository ของคุณ (เปลี่ยน YOUR_USERNAME และ REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# 6. Push ไฟล์ขึ้น GitHub
git push -u origin main
```

*(หมายเหตุ: ต้องสร้าง Repository เปล่าบน [GitHub.com](https://github.com/new) ก่อนนะครับ)*

---

### ขั้นตอนที่ 2: เปิดใช้งาน GitHub Pages

1. ไปที่หน้า GitHub Repository ของคุณ
2. คลิกที่แท็บ **Settings** (รูปฟันเฟืองด้านบน)
3. ที่เมนูด้านซ้าย เลือกหัวข้อ **Pages**
4. ในส่วน **Build and deployment > Source**:
   - เลือกเป็น **Deploy from a branch**
   - Branch: เลือก **`main`** และโฟลเดอร์เป็น **`/(root)`**
5. กดปุ่ม **Save**
6. รอประมาณ 1-2 นาที คุณจะได้ลิงก์เว็บไซต์ เช่น:
   `https://YOUR_USERNAME.github.io/REPO_NAME/`
7. สามารถแชร์ลิงก์นี้ให้เพื่อนๆ เข้ามาเล่นได้ทันทีทั้งบนคอมพิวเตอร์และมือถือ!

---

## 📁 โครงสร้างโปรเจกต์ (Project Structure)

```text
├── index.html        # ไฟล์เกมหลัก (รวม HTML, CSS, JavaScript, Web Audio API ไว้ในไฟล์เดียว)
├── README.md         # คู่มือการเล่นและการ Deploy
└── .gitignore        # ไฟล์สำหรับละเว้นไฟล์ที่ไม่จำเป็นในการขึ้น Git
```

---

## 💡 ลิขสิทธิ์และการปรับแต่ง (Customization)

โค้ดนี้สร้างขึ้นเป็น Open Source คุณสามารถนำไปปรับแต่งค่าต่างๆ ได้อย่างอิสระในไฟล์ [index.html](file:///c:/เกม%20vampire/index.html):
- เปลี่ยนสีและรูปทรงของตัวละครในฟังก์ชัน `render()` และ `drawPreview()`
- ปรับแต่งพลังโจมตี/ความเร็วของอาวุธในวัตถุ `UPGRADES`
- ปรับสมดุลศัตรูในคลาส `Enemy`
=======
# helenboo_game
>>>>>>> 21be39642a1da78ff63d33481abcef3723d1085d
