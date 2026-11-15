# BengalVolt — GitHub Pages site

এটি সরাসরি GitHub Pages-এ প্রকাশযোগ্য বাংলা স্টোরফ্রন্ট। কোনো build command, framework বা install দরকার নেই। `index.html` এবং `assets/` একসঙ্গে repository-র root-এ রাখুন।

## GitHub-এ প্রকাশ

1. GitHub-এ একটি repository তৈরি করুন, যেমন `bengalvolt-storefront`।
2. এই প্যাকেজের ভেতরের সবকিছু—`index.html`, `.nojekyll`, `README.md` এবং সম্পূর্ণ `assets` ফোল্ডার—repository-র root-এ আপলোড করুন। ফোল্ডারের গঠন যেন এমন থাকে:

   ```text
   repository/
   ├── index.html
   ├── .nojekyll
   ├── README.md
   └── assets/
       ├── hero-safety.svg
       ├── mcb.svg
       ├── led-bulb.svg
       ├── switch-socket.svg
       ├── cable.svg
       ├── panel-board.svg
       └── led-panel.svg
   ```

3. GitHub repository-তে **Settings → Pages** খুলুন।
4. **Build and deployment**-এর **Source** হিসেবে **Deploy from a branch** বেছে নিন।
5. Branch `main` এবং folder `/(root)` বেছে **Save** করুন।
6. Pages সেটিংসে সাইটের URL দেখা যাবে। প্রথম প্রকাশে কয়েক মিনিট লাগতে পারে।

## পণ্য/ছবি যোগ করা

1. নতুন পণ্যের ছবি `assets/` ফোল্ডারে রাখুন। `jpg`, `png` বা `webp` ছবি ব্যবহার করতে পারেন। ফাইলের নাম ছোট হাতের ইংরেজিতে দিন, যেমন `new-mcb.jpg`।
2. `index.html` খুলে JavaScript-এর `products` তালিকায় নতুন item যোগ করুন। উদাহরণ:

   ```js
   {name:'নতুন MCB', description:'পণ্যের সংক্ষিপ্ত বিবরণ', image:'new-mcb.jpg', badge:'নতুন', category:'mcb'}
   ```

3. `index.html`-এর `assets/${p.image}` অংশটি ছবির URL-ஐ নিজে তৈরি করে, তাই `image`-এ `assets/` লিখবেন না।
4. আপডেট করা `index.html` এবং নতুন ছবি GitHub repository-তে আপলোড/commit করুন। Pages স্বয়ংক্রিয়ভাবে আবার প্রকাশ করবে।

## যোগাযোগের নম্বর

ফোন ও WhatsApp লিংকে `+8801707944636` সেট করা আছে। নম্বর বদলালে `index.html`-এর `8801707944636` খুঁজে নতুন নম্বর বসান।

## ছবি সম্পর্কে

`assets/`-এর বর্তমান SVG-গুলো সাইটের জন্য তৈরি পণ্যের চিত্র। বিক্রির আসল পণ্যের ছবি পেলে একই ফোল্ডারে রেখে `products` তালিকার `image` মান বদলালেই হবে। নমুনা পণ্যের দাম ইচ্ছা করে দেওয়া নেই—অর্ডারকারী WhatsApp-এ দাম জানতে পারবেন।

