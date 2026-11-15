# BengalVolt — GitHub Pages

বাংলা ভাষার BengalVolt অনলাইন স্টোরফ্রন্ট। এটি সরাসরি GitHub Pages-এ চলে; কোনো build command বা framework দরকার নেই।

## GitHub-এ প্রকাশ

1. GitHub-এ repository তৈরি করুন।
2. ZIP-এর ভেতরের `index.html`, `.nojekyll`, `README.md` এবং সম্পূর্ণ `assets` ফোল্ডারটি repository-র root-এ আপলোড করুন। ZIP ফাইলটি নিজে আপলোড করবেন না।
3. repository-তে **Settings → Pages** খুলুন।
4. **Build and deployment → Source**-এ **Deploy from a branch** বেছে নিন।
5. Branch `main` এবং folder `/(root)` নির্বাচন করে **Save** দিন।
6. প্রকাশের URL একই Pages পাতায় দেখা যাবে। প্রথম প্রকাশে কয়েক মিনিট লাগতে পারে।

Repository-র ফাইলের গঠন এমন রাখুন:

```text
repository/
├── index.html
├── .nojekyll
├── README.md
└── assets/
    ├── hero-reference.jpg
    ├── family-reference.jpg
    ├── bangladesh-reference.jpg
    ├── cat-switch.jpg
    ├── cat-led.jpg
    ├── cat-breaker.jpg
    ├── cat-board.jpg
    ├── cat-cable.jpg
    ├── cat-fan.jpg
    ├── cat-pump.jpg
    ├── cat-accessories.jpg
    ├── prod-switch.jpg
    ├── prod-socket.jpg
    ├── prod-bulb.jpg
    ├── prod-mcb.jpg
    ├── prod-rccb.jpg
    └── prod-panel.jpg
```

## পণ্য ও ছবি বদলানো বা যোগ করা

`index.html`-এর নিচের দিকে `const products=[ ... ]` তালিকায় পণ্যের নাম, ধরন, দাম ও ছবির ফাইলের নাম আছে। নতুন ছবি `assets/`-এ আপলোড করে তালিকায় এভাবে item যোগ করুন:

```js
{name:'নতুন পণ্যের নাম',kind:'পণ্যের ধরন',price:'৳ ৫০০',image:'new-product.jpg'}
```

`image`-এ শুধু ফাইলের নাম দিন; ছবিটি `assets/` ফোল্ডারে রাখুন। পণ্য পরিবর্তন করলে তার সঠিক নাম, দাম ও নিজস্ব পণ্যের ছবি ব্যবহার করুন।

বর্তমান ছবিগুলো আপনার দেওয়া নকশার রেফারেন্স থেকে কেটে নেওয়া হয়েছে। মূল ছবির রেজোলিউশনের কারণে কিছু product thumbnail ছোট দেখাতে পারে; বিক্রির জন্য উচ্চ রেজোলিউশনের আসল product photo দিলে `assets/`-এ ফাইলটি রেখে তালিকার `image` মান বদলে দিন।

WhatsApp ও ফোন নম্বর `+8801707944636`। নম্বর বদলালে `index.html`-এ `8801707944636` খুঁজে নতুন নম্বর বসান।
