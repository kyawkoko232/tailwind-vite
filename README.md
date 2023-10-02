### Vite + Tailwind Starter Pack

အသုံးပြုပုံ
* `npm install` ဖြင့်လိုသည့် module များကို install လုပ်ပါ။
* `npm run dev` ဖြင့် server ဖွင့်ပါ။
* စတင်ရေးမည့်ဖိုင်များကို src directory ထဲတွင်ရေးပါ။
* ပုံတွေ ၊ပြင်ပ Assets တွေအတွက် static folder ထဲတွင်နေရာချပါ။ 
*    ` /` လို့ရေးပါက static folder ကိုထောက်ပြီးသားဖြစ်မည်။ လိုသည့် Folder များတည်ဆောက်ပြီးယူသုံးပါ။
```
<img  class="w-64 mx-auto"  src="/img/render.jpg"  alt="">
```
ဥပမာ `src="/img/render.jpg"` staic folder ထဲမှ img folder ထဲမှာ render.jpg ပုံကိုယူသုံးထားသည်။

### Tailwind Customize
Tailwind Customize လုပ်လိုပါက tailwind.config.js ဖိုင်ထဲတွင်လိုအပ်သည်များကိုပြင်ဆင်ပါ။
အသုံးပြုပုံမှာ CSSဖိုင်ကို JavaScript file ထဲတွင် import လုပ်၊ Module တွေကို JavaScript ဖိုင်ထဲက တစ်ဆင့်ယူသုံးသည်ဖြစ်လို့ သုံးမည့် html ဖိုင်တိုင်းတွင်

``` 
<script  type="module"  src="./main.js"></script>
```
script ဖိုင်ကို module type နှင့်မဖြစ်မနေချိတ်ပေးမှ Tailwind အလုပ်လုပ်မည်။


### DO NOT TOUCH
 vite.config.js ကိုမလိုအပ်ဘဲမထိပါနှင့်