<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=25D366&center=true&vCenter=true&width=500&lines=Ws_Checker;Ultimate+WhatsApp+%26+Telegram+Gateway" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Node.js-18%2B-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
  </a>
  <a href="https://t.me/Flask_Prime/">
    <img src="https://img.shields.io/badge/Telegram-Bot-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Security-Obfuscated-FF0000?style=for-the-badge&logo=javascript&logoColor=white" alt="Security" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20VPS-FF6C37?style=for-the-badge&logo=linux&logoColor=white" alt="Platform" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-MIT-7B3F00?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License" />
  </a>
</p>

---

## 📖 প্রজেক্ট পরিচিতি (About)

**Ws_Checker** — একটি **পেশাদার অটোমেশন গেটওয়ে** যা হোয়াটসঅ্যাপ ও টেলিগ্রামের শক্তিকে একত্রিত করে। এটি দিয়ে আপনি:

- ✅ **পেয়ারিং কোড** জেনারেট করতে পারেন
- ✅ **কিউআর কোড** স্ক্যান করে সেশন লোড করতে পারেন
- ✅ **টেলিগ্রাম বট** দিয়ে রিমোট কন্ট্রোল করতে পারেন

> 🔒 **নিরাপত্তা:** এই প্রজেক্টের সমস্ত সোর্স কোড **JavaScript-Obfuscator** দ্বারা ১০০% এনক্রিপ্ট করা হয়েছে, যা কপি বা রিভার্স ইঞ্জিনিয়ারিং প্রতিরোধ করে।

---

## ✨ মূল ফিচারসমূহ (Features)

| ফিচার | বিবরণ |
|-------|--------|
| ⚡ **Instant Pairing** | শুধু ফোন নম্বর দিলেই পেয়ারিং কোড তৈরি |
| 📸 **QR Scanner** | ওয়েব ইন্টারফেসে লাইভ QR কোড স্ক্যান |
| 🤖 **Telegram Bot** | বট দিয়ে লাইভ অ্যালার্ট, পোলিং ও মনিটরিং |
| 🖥️ **Modern UI** | রেস্পন্সিভ ড্যাশবোর্ড (main, pair, qr) |
| 📦 **Lightweight** | Termux, VPS, Railway—সব জায়গায় চলবে |
| 🔐 **Obfuscated Code** | সম্পূর্ণ কোড সুরক্ষিত ও এনক্রিপ্টেড |

---

## 📂 ফাইল স্ট্রাকচার (Structure)

```bash
📦mrfbcrete
 ┣ 📂public/               # ফ্রন্টএন্ড ফাইল (HTML, CSS, JS)
 ┃ ┣ 📜index.html
 ┃ ┣ 📜pair.html
 ┃ ┗ 📜qr.html
 ┣ 📜index.js              # 🔒 মেইন গেটওয়ে (Protected)
 ┣ 📜telegramBot.js        # 🔒 টেলিগ্রাম বট লজিক (Protected)
 ┣ 📜server.js             # 🔒 ওয়েব সার্ভার (Protected)
 ┣ 📜pair.js               # 🔒 পেয়ারিং হ্যান্ডলার (Protected)
 ┣ 📜qr.js                 # 🔒 QR সেশন হ্যান্ডলার (Protected)
 ┣ 📜mega.js               # 🔒 ক্লাউড ব্যাকআপ (Protected)
 ┣ 📜package.json          # ডিপেনডেন্সি লিস্ট
 ┗ 📜README.md             # প্রজেক্ট ডকুমেন্টেশন
```

---

## 🛠️ ইনস্টলেশন ও রান (Installation)

### Termux / VPS / Railway-এ চালানোর ধাপ:

```bash
# ধাপ ১: রিপোজিটরি ক্লোন করুন
git clone https://github.com/Soureahchakma/Ws_Checker.git

# ধাপ ২: প্রজেক্ট ডিরেক্টরিতে যান
cd Ws_Checker

# ধাপ ৩: প্রয়োজনীয় প্যাকেজ ইনস্টল করুন
npm install

# ধাপ ৪: অ্যাপ্লিকেশন রান করুন
node index.js
```

> 💡 **টিপ:** Railway বা অন্যান্য ক্লাউড প্ল্যাটফর্মে ডিপ্লয় করতে `package.json`-এর `start` স্ক্রিপ্ট ব্যবহার করুন।

---

## 🚀 ব্যবহারের নির্দেশনা (Usage)

1. **ওয়েব ইন্টারফেস:** ব্রাউজারে `http://localhost:3000` খুলুন।
2. **পেয়ারিং:** `pair` পেজে ফোন নম্বর দিয়ে কোড নিন।
3. **QR স্ক্যান:** `qr` পেজে স্ক্যান করে সেশন লোড করুন।
4. **টেলিগ্রাম বট:** আপনার বটের সাথে যোগাযোগ করে কমান্ড দিন।

---

## ⚙️ টেকনোলজি স্ট্যাক (Tech Stack)

<p align="left">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-404D59?style=flat&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Telegram_API-26A5E4?style=flat&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/badge/WhatsApp_Web.js-25D366?style=flat&logo=whatsapp&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript_Obfuscator-F7DF1E?style=flat&logo=javascript&logoColor=black" />
</p>

---

## ⚠️ গুরুত্বপূর্ণ সতর্কতা (Disclaimer)

- 🛑 এই টুল **শুধুমাত্র শিক্ষণীয় ও ব্যক্তিগত অটোমেশন** উদ্দেশ্যে তৈরি।
- 🛑 প্রজেক্টের কোনো ফাইল **এডিট বা ডিক্রিপ্ট** করার চেষ্টা করলে তা **ক্র্যাশ** বা **স্থায়ীভাবে অচল** হয়ে যেতে পারে।
- 🛑 দায়িত্ব অস্বীকার: এই টুল ব্যবহারে কোনো ক্ষতি হলে ডেভেলপার দায়ী নয়।

> 📌 **প্রয়োজনে সরাসরি ডেভেলপারের সাথে যোগাযোগ করুন।**

---

## 👨‍💻 ডেভেলপার পরিচিতি (Developer)

<p align="left">
  <img src="https://img.shields.io/badge/Name-Sadhan_Chakma-0A66C2?style=for-the-badge&logo=github&logoColor=white" /> <br />
  <img src="https://img.shields.io/badge/Role-Bot_Developer_%26_Technologist-FF6F00?style=for-the-badge&logo=code&logoColor=white" /> <br />
  <img src="https://img.shields.io/badge/Telegram-@Sadhan_chakma-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /> <br />
  <a href="https://github.com/Soureahchakma">
    <img src="https://img.shields.io/badge/GitHub-Soureahchakma-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a> <br />
  <a href="https://t.me/Flask_Prime">
    <img src="https://img.shields.io/badge/Telegram_Channel-@Flask_Prime-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" />
  </a> <br />
  <a href="https://t.me/WS_CheckerrBot">
    <img src="https://img.shields.io/badge/Demo_Bot-@WS_CheckerrBot-0088CC?style=for-the-badge&logo=telegram&logoColor=white" />
  </a>
</p>

---

<p align="center">
  <b>Made with ❤️ by Sadhan</b> <br />
  <sub>© 2026 Ws_Checker | All Rights Reserved</sub>
</p>
