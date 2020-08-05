
  
<div dir="rtl">    
    <p><h2>استایل دهی عناصر در React</h2></p>    
    <p><h4>
  
<div dir="rtl">    
    <p><h2>استایل دهی عناصر در React</h2></p>    
    <p><h4>این مقاله فقط جهت درک کار کردن با استایل ها در React است و در مقاله دیگری استایل در ری اکت بررسی می شود .</h4></p>    
    <p><h4>ما می توانیم استایل دهی را به دو روش انجام دهیم</h4></p>    
    <p><h4>این تمرین در ادامه درس react-method-transfer-between-components است .</h4></p>  
        <p><h3>روش اول</h3></p>  
    <p><h4>ابتدا در پوشه ی Person یک فایل به نام Person.css می  سازیم و کدهای زیر را در آن قرار می دهیم :  
<pre dir="ltr"> ‍‍‍<code>  
    .Person {    
    width: 60%;    
  margin: 16px auto;    
  border: 1px solid #eee;    
  -webkit-box-shadow: 0 2px 3px #ccc;    
  box-shadow: 0 2px 3px #ccc;    
  padding: 16px;    
  text-align: center;    
}</code></pre>  
</h4></p>   
    <p><h4>سپس به فایل Person.js می رویم و این کلاس را به div ریشه ای اضافه می کنیم:</h4></p>   
    <p><h4><pre dir="ltr"><code>  
   &lt;div className="Person"&gt;  
   </code></pre></h4></p>   
    <p><h4>فایل Person.css را نیز درون فایل Person.js وارد می کنیم</h4></p>   
    <p><h4><pre dir="ltr"> ‍‍‍<code>  
   import React from  'react';  
   import  './Person.css';  
    </code></pre></h4></p>   
    <p><h4>پسوند فایل، فقط برای فایل های جاوا اسکریپت قابل حذف است. برای فایل های دیگر (مانند فایل های css) حتما باید پسوند را نیز ذکر کنیم. حالا اگر به مرورگر برگردیم متوجه می شویم که استایل های ما در مرورگر قابل مشاهده است.</h4></p>   
    <p><h4>اگر از قسمت dev tools (کلید f12) به قسمت <head> نگاهی بیندازیم متوجه می شویم که استایل های ما به این قسمت از صفحه ی HTML تزریق شده اند.</h4></p>                
    <p><h4>  
    این یک روش استایل دهی عناصر بود. برای استایل دهی دکمه ی switch name می خواهیم از روش دوم استایل دهی (استایل دهی inline) استفاده کنیم.  
    </h4></p>  
    <p><h3>روش دوم</h3></p>  
    <p><h4>با فایل App.js بروید و درون تابع ()render یک شیء جاوا اسکریپتی ایجاد کنید. سپس درون این شیء از خصوصیات استایل دهی در جاوا اسکریپت استفاده کنید؛ همانطور که می دانید استایل های CSS درون جاوا اسکریپت شکل خاص خود را دارند: به طور مثال background-color در css برابر با backgroundColor در جاوا اسکریپت است. انتظار می رود که با این مسائل در جاوا اسکریپت عادی آشنا شده و به آن ها تسلط داشته باشید.</h4></p>  
    <pre dir="ltr"> ‍‍‍<code>  
        .Person {    
        width: 60%;    
      margin: 16px auto;    
      border: 1px solid #eee;    
      -webkit-box-shadow: 0 2px 3px #ccc;    
      box-shadow: 0 2px 3px #ccc;    
      padding: 16px;    
      text-align: center;    
    }</code></pre>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
</div>    
<br /><br /><br /><br />    
    
<p>This project was bootstrapped with <a href="https://github.com/facebookincubator/create-react-app">Create React App</a></p></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
    <p><h4></h4></p>  
</div>    
<br /><br /><br /><br />    
    
<p>This project was bootstrapped with <a href="https://github.com/facebookincubator/create-react-app">Create React App</a></p>