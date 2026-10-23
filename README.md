# Bandhan Apparel Ltd. (Official Website)

Premium 100% Export-Oriented Ready-Made Garments (RMG) Manufacturer from Dhaka, Bangladesh.

---

## 🚀 cPanel 1-Click Deployment Guide (cPanel Git™ Version Control)

এই প্রজেক্টটি cPanel-এর **Git™ Version Control** দিয়ে খুব সহজে এক ক্লিকেই লাইভ এবং আপডেট করার জন্য কনফিগার করা হয়েছে।

### প্রথমবার সেটআপ করার নিয়ম (First Time Setup):
1. **cPanel**-এ লগইন করুন।
2. **Files** সেকশন থেকে **Git™ Version Control**-এ ক্লিক করুন।
3. **Create** বাটনে ক্লিক করুন।
4. তথ্যগুলো পূরণ করুন:
   - **Clone URL:** `https://github.com/gonjotech/bandhanapparelltd.com.git`
   - **Repository Path:** `repositories/bandhanapparelltd` (অথবা সরাসরি `public_html`)
   - **Repository Name:** `bandhanapparelltd`
5. **Create** বাটনে ক্লিক করে ক্লোন সম্পন্ন করুন।

---

### এক ক্লিকে লাইভ আপডেট করার নিয়ম (1-Click Update):
পরবর্তীতে যখনই GitHub-এ কোনো নতুন কোড পুশ হবে:
1. cPanel > **Git™ Version Control**-এ যান।
2. আপনার রিপোজিটরির ডানপাশে **Manage** বাটনে ক্লিক করুন।
3. **Pull or Deploy** ট্যাবে ক্লিক করুন।
4. **Update from Remote** বাটনে ক্লিক করুন (এটি GitHub থেকে লেটেস্ট কোড টেনে নিয়ে আসবে)।
5. এরপর **Deploy HEAD Commit** বাটনে ক্লিক করুন (রিপোজিটরির `.cpanel.yml` ফাইল স্বয়ংক্রিয়ভাবে সব ফাইল `public_html`-এ লাইভ করে দেবে)।

---

## 📁 প্রজেক্ট স্ট্রাকচার
- `index.html` — মূল ওয়েবসাইট (হিরো স্লাইডার, প্রোডাক্ট ট্যাক্সনমি, বায়ার্স, মেশিনারি, কোয়ালিটি, আরএফকিউ)
- `.cpanel.yml` — cPanel ডিপ্লয়মেন্ট কনফিগারেশন ফাইল
- `bandhan logo.jpg` — অফিসিয়াল ফ্যাক্টরি লোগো
- `*.jpg / *.png` — ম্যানেজমেন্ট ও ফ্যাক্টরি ইমেজ
- `.htaccess` — সার্ভার রাউটিং ও ক্যাশিং কনফিগারেশন
