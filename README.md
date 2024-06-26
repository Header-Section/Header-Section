# Header ပိုင်းကိုရှင်းလင်းချက်

* body ထဲမှာ hearder tag ကိုရေးသည်။ ထို့နောက် header tag ထဲမှာ အဓိကခေါင်းစဉ်ကြီးကို h1 tag ဖြင့်ရေးရပါသည်။


ဒီ HTML ကုဒ်ကို အစိတ်အပိုင်း အလိုက် မြန်မာဘာသာဖြင့် ရှင်းပြပါမယ်။

### HTML ဖိုင်ဖွဲစည်းပုံရှင်းလင်းချက်
```html
<!DOCTYPE html>
<html lang="en"> 
```
- `<!DOCTYPE html>`: ဒီလိုရေးသားထားခြင်းက HTML5 ကို သုံးထားတာဆိုတာကို သတ်မှတ်ပေးတာပါ။
- `<html lang="en">`: ဒီအတိုင်း အစီအစဉ်ရေးထားခြင်းက HTML ဖိုင်ရဲ့ ဘာသာစကားကို English ဆိုတာကို ဖော်ပြပေးတာပါ။

### Head အပိုင်း
```html
<head>
  <meta charset="UTF-8" />
  <title>Header-Section</title>
</head>
```
- `<meta charset="UTF-8" />`: ဒီလိုရေးထားခြင်းက ဖိုင်ရဲ့ အက္ခရာ encoding ကို UTF-8 (Unicode Text Format) အဖြစ် သတ်မှတ်ပေးတာပါ။
- `<title>Header-Section</title>`: ဒီလိုရေးထားခြင်းက Web Browser ရဲ့ Tab မှာ ပြထားမယ့် ခေါင်းစဉ်ကို သတ်မှတ်ပေးတာပါ။

### Body အပိုင်း
```html
<body>
  <!-- navigation -->
  <header>
    <h1>
      <a href="/">
        RUN BUDDY
      </a>
    </h1>
    <nav>
      <!-- Unordered list element -->
      <ul>
        <!-- List item element-->
        <li>
          <!-- Anchor element -->
          <a href="#what-we-do">What We Do</a>
        </li>
        <li>
          <a href="#what-you-do">What You Do</a>
        </li>
        <li>
          <a href="#your-trainers">Your Trainers</a>
        </li>
        <li>
          <a href="#reach-out">Reach Out</a>
        </li>
      </ul>
    </nav>
  </header>
</body>
```
- `<body>`: ဒီလိုရေးသားထားခြင်းက Web Page ရဲ့ အဓိကအကြောင်းအရာတွေကို ထည့်သွင်းထားတဲ့ နေရာပါ။

#### Header
```html
<header>
  <h1>
    <a href="/">
      RUN BUDDY
    </a>
  </h1>
```
- `<header>`: ဒီလိုရေးထားခြင်းက Web Page ရဲ့ ခေါင်းစဉ်နဲ့ Navigation Bar အပိုင်းကို သိမ်းဆည်းထားတာပါ။
- `<h1>`: ဒီလိုရေးထားခြင်းက အကြီးဆုံး ခေါင်းစဉ်ကို ပြထားတာပါ။
- `<a href="/">RUN BUDDY</a>`: ဒီလိုရေးသားထားခြင်းက "RUN BUDDY" ဆိုတဲ့ စာသားကို မူလစာမျက်နှာကို ပြန်သွားဖို့ လင့်ခ် ထားတာပါ။

#### Navigation Bar
```html
<nav>
  <!-- Unordered list element -->
  <ul>
    <!-- List item element-->
    <li>
      <!-- Anchor element -->
      <a href="#what-we-do">What We Do</a>
    </li>
    <li>
      <a href="#what-you-do">What You Do</a>
    </li>
    <li>
      <a href="#your-trainers">Your Trainers</a>
    </li>
    <li>
      <a href="#reach-out">Reach Out</a>
    </li>
  </ul>
</nav>
```
- `<nav>`: ဒီလိုရေးသားထားခြင်းက Navigation Bar အတွက် သတ်မှတ်ပေးထားတာပါ။
- `<ul>`: ဒီလိုရေးသားထားခြင်းက Unordered List (၁၊ ၂၊ ၃ စသည်စီစဉ်မထားတဲ့ စာရင်း) ဖြစ်တာပါ။
- `<li>`: ဒီလိုရေးသားထားခြင်းက စာရင်းအပိုင်းအစ (List Item) တစ်ခုချင်းစီကို သိမ်းထားတာပါ။
- `<a href="#what-we-do">What We Do</a>`: ဒီလိုရေးသားထားခြင်းက "What We Do" ဆိုတဲ့ စာသားကို `#what-we-do` ဆိုတဲ့ ID ရှိတဲ့နေရာကို ချိတ်သွားစေတဲ့ လင့်ခ် ဖြစ်ပါတယ်။

ဒီလို HTML ဖိုင်အတွင်းမှာ Header နဲ့ Navigation Bar ကို သီးသန့်ဖော်ပြထားပြီး မူလစာမျက်နှာနှင့် ချိတ်ဆက်ထားတဲ့ လင့်ခ်များကို ထည့်သွင်းထားတာ ဖြစ်ပါတယ်။