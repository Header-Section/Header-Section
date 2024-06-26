#   HTML မှာ Header ခေါင်းစဥ်တစ်ခု ဖြစ်ပေါ်လာအောင် ရေးသားခြင်း


### HTML ဖိုင်ဖွဲစည်းပုံရှင်းလင်းချက်

```html
<!DOCTYPE html>
<html lang="en"> 
```
![alt text](<Screenshot from 2024-06-26 20-13-07.png>)

- `<!DOCTYPE html>`: ဆိုတာကတော့ HTML5 အမျိုးအစားကို ကြေငြာထားခြင်းဖြစ်ပါတယ်။
- `<html lang="en">`: ကတော့ HTML ကို အင်္ဂလိပ်ဘာသာဖြင့် သုံးမည်လို့ သတ်မှတ်ထားဖြစ်ပါတယ်။ 

### Head အပိုင်း
```html
<head>
  <meta charset="UTF-8" />
  <title>Header-Section</title>
</head>
```
- `<meta charset="UTF-8" />`: ဟူသည်မှာ meta tag ကတော့ မိမိတင်ထားသော ဝက်ဆိုက်ကို browser မှာ ဦးစားပေးဖော်ပြအောင် ရေးသားထားခြင်းဖြစ်၍၊ UTF-8 က (Unicode Transformation Format - 8-bit) ကိုဆိုလိုပြီး, တစ်ကမ္ဘာလုံးမှ အက္ခရာများကို သိမ်းဆည်းဖော်ပြရာမှာ အသုံးပြုတဲ့ စနစ်တစ်ခုဖြစ်တယ်။ 
- `<title>Header-Section</title>`: ဆိုသည်မှာ Web Browser ရဲ့ Tabar မှာ ပေါ်နေမယ့် ခေါင်းစဉ်ဖြစ်ပါတယ်။

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
![alt text](<Screenshot from 2024-06-26 21-31-39.png>)

- `<body>`: ဆိုတာ Web Page ရဲ့ အဓိကအကြောင်းအရာတွေကို ထည့်သွင်းရေးသားရမည့် နေရာဖြစ်ပါတယ်။

#### Header

```html
<header>
  <h1>
    <a href="/">
      RUN BUDDY
    </a>
  </h1>
```
![alt text](<Screenshot from 2024-06-26 21-32-34.png>)

- ဒီနေမှာတော့ Header ပိုင်းနဲ့ ပတ်သက်ဆက်နွယ်သော ဆင့်ကဲ ပြောင်းလှဲလာမှုများကို ရေးသားပြပါ့မယ်၊ header ထဲမှာ Devloper တစ်ယောက်အနေနဲ့ ဘယ်လို ပုံစံမျိုး ထည့်ပြီး ရေးချင်သလဲ၊ စိတ်ကူးစိတ်သန်း ကောင်းရင် ကောင်းသလို Header ပိုင်းကလည်း လှပမှု ကွဲပြားမှာ ဖြစ်ပါတယ်၊ လှပမှုတွေ အသာထား ပထမဦးဆုံး အရိုးရှင်းဆုံးကပဲ စတင်လေ့လာကြရေအာင်။

- `<header>`: ကတော့ Web Page ရဲ့ ခေါင်းစဉ်နဲ့ Navigation Bar အပိုင်းကို ဖော်ပြတဲ့နေရာဖြစ်ပါတယ်။
- `<h1>`: ဆိုသည်မှာ အကြီးဆုံး ခေါင်းစဉ်ကို ပြထားတာပါ။
- `<a href="/">RUN BUDDY</a>`: ဒီလိုရေးသားထားခြင်းက "RUN BUDDY" ဆိုတဲ့ စာသားကို မူလစာမျက်နှာကို ပြန်သွားဖို့ လင့်ခ်လုပ်ထားတာပါ။ ထို့အပြင် <a> tag ကို anchor element လို့ခေါ်ပါတယ်၊ ။ HTML မှာ hyperlinks ဖန်တီးဖို့ အသုံးပြုပါတယ်။ Hyperlinks ဆိုတာ အသုံးပြုတဲ့သူတွေကို စာသား သို့မဟုတ် ပုံများကိုနှိပ်လျှင် တစ်နေရာမှ နောက်တစ်နေရာကို ရွှေ့ပြောင်းစေနိုင်တဲ့ မြှားပုံစံ တစ်ဖြစ်လဲ လက်ပုံစံလေးပဲ ဖြစ်ပါတယ်။

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
![alt text](<Screenshot from 2024-06-26 21-33-36.png>)

- `<nav>`: ဒီလိုရေးသားထားခြင်းက Navigation Bar အတွက် သတ်မှတ်ပေးထားတာပါ။
- `<ul>`: ဒီလိုရေးသားထားခြင်းက Unordered List (၁၊ ၂၊ ၃ စသည်စီစဉ်မထားတဲ့ စာရင်း) ဖြစ်တာပါ။
- `<li>`: ဒီလိုရေးသားထားခြင်းက စာရင်းအပိုင်းအစ (List Item) တစ်ခုချင်းစီကို သိမ်းထားတာပါ။
- `<a href="#what-we-do">What We Do</a>`: ဒီလိုရေးသားထားခြင်းက "What We Do" ဆိုတဲ့ စာသားကို `#what-we-do` ဆိုတဲ့ ID ရှိတဲ့နေရာကို ချိတ်သွားစေတဲ့ လင့်ခ် ဖြစ်ပါတယ်။

ဒီလို HTML ဖိုင်အတွင်းမှာ Header နဲ့ Navigation Bar ကို သီးသန့်ဖော်ပြထားပြီး မူလစာမျက်နှာနှင့် ချိတ်ဆက်ထားတဲ့ လင့်ခ်များကို ထည့်သွင်းထားတာ ဖြစ်ပါတယ်။