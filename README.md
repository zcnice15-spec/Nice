# Nice - Style & Name App

একটি শিক্ষামূলক Android অ্যাপ্লিকেশন যা ব্যবহারকারীদের নাম তৈরি করতে, বিভিন্ন স্টাইল প্রয়োগ করতে এবং সংরক্ষণ করতে দেয়।

## বৈশিষ্ট্য (Features)

✨ **নাম তৈরি করুন** - ব্যবহারকারীর নাম ইনপুট করুন  
🎨 **স্টাইল নির্বাচন** - বিভিন্ন রঙ, ফন্ট এবং ডিজাইন বেছে নিন  
💾 **সংরক্ষণ করুন** - তৈরি নামগুলি ডেটাবেসে সংরক্ষণ করুন  
📋 **ইতিহাস দেখুন** - আগে সংরক্ষিত সমস্ত নাম এবং স্টাইল দেখুন  
🗑️ **মুছুন** - সংরক্ষিত আইটেম মুছে ফেলুন

## প্রযুক্তি (Tech Stack)

- **ভাষা:** Kotlin
- **প্ল্যাটফর্ম:** Android
- **ডেটাবেস:** SQLite / Room
- **UI:** Material Design
- **Minimum SDK:** Android 24 (7.0)
- **Target SDK:** Android 34

## প্রকল্প কাঠামো (Project Structure)

```
Nice/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/nice/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── adapter/
│   │   │   │   ├── database/
│   │   │   │   └── model/
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── values/
│   │   │   │   └── drawable/
│   │   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── build.gradle.kts
└── README.md
```

## সেটআপ (Setup)

1. রিপোজিটরি ক্লোন করুন
```bash
git clone https://github.com/zcnice15-spec/Nice.git
cd Nice
```

2. Android Studio এ খুলুন

3. প্রজেক্ট সিঙ্ক করুন এবং চালান

## ব্যবহার (Usage)

1. অ্যাপ খুলুন
2. নাম টাইপ করুন
3. পছন্দের স্টাইল নির্বাচন করুন
4. **Save** বোতাম ক্লিক করুন
5. সংরক্ষিত আইটেমগুলি দেখতে **History** এ যান

## লাইসেন্স

MIT License - বিস্তারিতের জন্য LICENSE ফাইল দেখুন

## লেখক

zcnice15-spec

---

**নোট:** এটি একটি শিক্ষামূলক প্রকল্প যা Android ডেভেলপমেন্টের ভিত্তি শেখায়।
