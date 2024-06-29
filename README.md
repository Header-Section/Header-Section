#   HTML မှာ Header ခေါင်းစဥ်တစ်ခု ဖြစ်ပေါ်လာအောင် ရေးသားခြင်း
### HTML ဖိုင်ဖွဲ့စည်းပုံ ရှင်းလင်းချက်
```html
<!DOCTYPE html>
<html lang="en">
```
![alt text](<Screenshot from 2024-06-26 20-13-07.png>)
- `<!DOCTYPE html>`: ဆိုတာကတော့ HTML5 အမျိုးအစားကို ကြေငြာထားခြင်းဖြစ်ပါတယ်။
- `<html lang="en">`: ကတော့ HTML ကို အင်္ဂလိပ်ဘာသာဖြင့် သုံးမယ်လို့ သတ်မှတ်ထားဖြစ်ပါတယ်။
### Head အပိုင်း
```html
<head>
  <meta charset="UTF-8" />
  <title>Header-Section</title>
</head>
```
![alt text](<Screenshot from 2024-06-26 21-39-43.png>)
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
![alt text](<Screenshot from 2024-06-26 21-40-49.png>)
- ဒီနေမှာတော့ Header ပိုင်းနဲ့ ပတ်သက်ဆက်နွယ်တဲ့ ဆင့်ကဲ ပြောင်းလှဲလာမှုများကို ရေးသားပြပါ့မယ်၊ header ထဲမှာ Devloper တစ်ယောက်အနေနဲ့ ဘယ်လို ပုံစံမျိုး ထည့်ပြီး ရေးချင်သလဲ၊ စိတ်ကူးစိတ်သန်း ကောင်းရင် ကောင်းသလို Header ပိုင်းကလည်း လှပမှု ကွဲပြားမှာ ဖြစ်ပါတယ်၊ ပထမဦးဆုံး အရိုးရှင်းဆုံးကပဲ စတင်လေ့လာကြည့်ရအောင်။
- `<header>`: ကတော့ Web Page ရဲ့ ခေါင်းစဉ်နဲ့ Navigation Bar အပိုင်းကို ဖော်ပြတဲ့နေရာဖြစ်ပါတယ်။
- `<h1>`: ကတော့ အကြီးဆုံး ခေါင်းစဉ်ကို ပြထားခြင်းဖြစ်ပါတယ်။
- `<a href="/">RUN BUDDY</a>`: ဒီပုံစံကတော့ "RUN BUDDY" ဆိုတဲ့ စာသားကို လင့်ခ်လုပ်ထားခြင်းဖြစ်ပါတယ်။ ထို့အပြင် a tag ကို anchor element လို့ခေါ်ပါတယ်၊ ။ HTML မှာ hyperlinks ဖန်တီးဖို့ အသုံးပြုပါတယ်။ Hyperlinks ဆိုတာ အသုံးပြုတဲ့သူတွေကို စာသား သို့မဟုတ် ပုံများကိုနှိပ်လျှင် တစ်နေရာမှ နောက်တစ်နေရာကို ရွှေ့ပြောင်းစေနိုင်တဲ့ မြှားပုံစံကနေ လက်ပုံစံလေး ပြောင်းသွားခြင်းပဲ ဖြစ်ပါတယ်။
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
![alt text](<Screenshot from 2024-06-29 14-50-36.png>)
- `<nav>`: ဒီသင်္ကေတကတော့ Navigation Bar အတွက် သတ်မှတ်ပေးထားတာပါ။
- `<ul>`: ဒီသင်္ကေတကတော့ Unordered List (၁၊ ၂၊ ၃ စသည်စီစဉ်မထားတဲ့ စာရင်း) ဖြစ်တာပါ။
- `<li>`: ဒီသင်္ကေတကတော့ စာရင်းအပိုင်းအစ (List Item) တစ်ခုချင်းစီကို သိမ်းထားတာပါ။
- `<a href="#what-we-do">What We Do</a>`: ဒီလိုရေးသားထားခြင်းက "What We Do" ဆိုတဲ့ စာသားကို `#what-we-do` ဆိုတဲ့ ID ရှိတဲ့နေရာကို လင့်ခ်ချိတ်ပေးတာ ဖြစ်ပါတယ်။

### Html နဲ့ css ဆိုတာ ဘာလဲ။

### Html ကို css နဲ့ ချိတ်ဆက်၍ အလှဆင်ခြင်း
 * Html ဆိုတာ ဦးခေါင်း၊ ခန္ဓာကိုယ်၊ ခြေလက် စတဲ့ အင်္ဂါ အစုံနဲ့ တည်ဆောက်ထားတဲ့ လူတစ်ယောက်ရဲ့ ရုပ်တုတစ်ခုလို head body header footer စတဲ့ အခြေခံကုဒ်တွေနဲ့ ဖွဲ့စည်းထားတဲ့ အကြမ်းထည် ပုံသဏ္ဍာန် တစ်ခုပဲဖြစ်ပါတယ်၊
 * css ဆိုတဲ့သဘောက  html ထဲမှာ ရေးခဲ့တဲ့ header body footer စတဲ့ကုဒ်တွေကို လူရုပ်တုကို ဆေးခြယ်သလို css ထဲမှာ color fontzise margin padding စတဲ့ အလှကုန် ပစ္စည်းများနဲ့ ဆေးခြယ်သခြင်းပဲ ဖြစ်ပါတယ်။
 * ဥပမာ။ ။ အင်္ကျီ အဝတ်အစား ဘာတစ်ခုမှ ဝတ်မထားတဲ့ လူတစ်ယောက်ရဲ့ ခန္ဓာကိုယ် ပုံစံဟာ html နဲ့ တူပြီး၊ အင်္ကျီ အဝတ်အစား ဝတ်ထားပြီး ခန္ဓာကိုယ်ကို ချောမောလှပအောင် ဖီးလိမ်း ပြင်ဆင်ချယ်သထားခြင်းဟာ css နဲ့တူပါတယ်။ နောက်ထပ် ဥပမာအနေနဲ့ ပြောရရင်
 တည်ဆောက်ပြီး ဆေးမသုပ်ရသေးတဲ့ အကြမ်းထည် အိမ်နဲ့ ဆေးသုပ် အလှဆင်ထားတဲ့ အိမ်ပုံစံလိုပဲ ဖြစ်ပါတယ်။
 ဒီကုဒ်အပိုင်းကို မြန်မာဘာသာဖြင့် အသေးစိတ်ရှင်းပြပါမည်။

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
```
## (*)  star ကို ယူနီဗာဆယ် စလက်တာ အကြောင်း 
- ယူနီဗာဆယ်စလက်တာဟာ ပရိုဂရမ်းမင်းရေးတဲ့ သူတွေအတွက် အဓိက နေရာကနေ ပါဝင်ပါတယ်။ 
ယူနီဗာဆယ်စလက်တာကို cssရဲ့ အပေါ်ဆုံးအပိုင်းကနေ ရေးသားရပါတယ်။ 
file တစ်ခုလုံးအပေါ် အကျိုးသက်ရောက်မှု ရှိပါတယ်။ 

ဤကုဒ်က html၌ ပါဝင်သော  element များအားလုံးကို  margin (ပြင်ပအကွာအဝေး) နှင့် padding (အတွင်းအကွာအဝေး) ကို '၀' အဖြစ်သတ်မှတ်ပေးထားပါတယ်။ ထို့ပြင် box-sizing ကို border-box အဖြစ် သတ်မှတ်ပြီး element ရဲ့ အရွယ်အစားကို border အပါအဝင် ထည့်တွက်သွားပါတယ်။

```css
body {
    color: #39A6B2;
    font-family: Helvetica, Arial, sans-serif;
  }
```
ဤကုဒ်က website ရဲ့ body တစ်ခုလုံးအတွက် အဓိကစာလုံးအရောင်ကို #39A6B2 (အစိမ်ရောင်နုနုလေး) အဖြစ် သတ်မှတ်ပေးပြီး အဓိကအက္ခရာ(font)ကို Helvetica, Arial, sans-serif အဖြစ် သတ်မှတ်ထားပါတယ်။

```css
header {
    padding: 50px 75px;
    background-color: #39A6B2;
  }
```

header အတွက် padding (အတွင်းအကွာအဝေး) ကို အပေါ်ဘက်နှင့်အောက်ဘက်ကို  50px နှင့် ဘယ်,ညာကို 75px အဖြစ်သတ်မှတ်ထားပြီး နောက်ခံအရောင်ကို #39A6B2 (အစိမ်းရောင်နုနုလေး )ကို သုံးပေးထားပါတယ်။

```css
header h1 {
    font-weight: bold;
    font-size: 36px;
    color: #FCE138;
    margin: 0;
    display: inline;
  }
```
header အတွင်းရှိ h1 အမည်ပါ စာသားများကို bold အဖြစ်သတ်မှတ်ပီး  အရွယ်အစားကို 36px အဖြစ်သတ်မှတ်ထားပါတယ်။ အရောင်ကတော့  #FCE138 (အဝါရောင်လေး) ကို သုံးထားပီး  margin ကို '၀' အဖြစ်ထည့်ထားပါတယ်။ display ကို inline အဖြစ်သတ်မှတ်ထားပါတယ်။ 

```css
header a {
    text-decoration: none;
    color: #FCE138;
  }
```
header အတွင်းရှိ link (ချိတ်ဆက်ချက်) များအတွက် text-decoration ကို none အဖြစ်ပြုလုပ်ပြီး အရောင်ကို #FCE138 (အဝါရောင်) အဖြစ်သတ်မှတ်ထားပါတယ်။
```css
header nav {
    float: right;
    margin: 7px 0;
  }
```
header အတွင်းရှိ navigation bar (ချိတ်ဆက်မှူ့များ) ကို float right ကို အသုံးပြုထားပါတယ်။ (ညာဘက်မှာ  စနစ်တကျ ဖြစ်အောင် လုပ်ဆောင်ပေးပါတယ်)။margin ကို အပေါ်ဘက်နှင့်အောက်ဘက် 7px အဖြစ်ထားပါတယ်။

```css
header nav ul li {
    display: inline;
  }
```
header အတွင်းရှိ navigation bar တွင် ul (unordered list) ထဲရှိ li (list item) များကို  display: inline ကို (တစ်ကြောင်းထဲဖြစ်အောင်) သတ်မှတ်ပေးထားပါတယ်။ 

```css
header nav ul li a {
    margin: 0 30px;
    font-weight: lighter;
    font-size: 22px;
  }
```
header အတွင်းရှိ nav ul li a tag ထဲမှာ margin ကို အပေါ်,အောက် '၀' ဘယ်ညာကို 30px အကွာအဝေးထားပြီး font-weight ကို lighter (ဖျော့ဖျော့) အဖြစ်သတ်မှတ်ထားပါတယ်။ font-size ကို 22px အဖြစ် သုံးထားပါတယ်။ 

