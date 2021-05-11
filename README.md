# WS2812
a simple library for STM32 - non blocking library use timer and interupts

<h3>start</h3>
<p>
for start working with this library
you can look at my CubeMX file and set a Timer, PWM, DMA, and Interpts like my setup
and of course its obvious you should just focus on my WS2812 pin (forget about other pins)
</p>

<h3>set clock:</h3>
<p>
don't forget to set the clock in WS2812.h
you obtain it by math formula and then accurate it by try and false
</p>

<h3>example</h3>
<p>
  you can find the necessary coded in WS2812Example.c
  with search <code>//<-------------</code>
</p>

<hr>
<p dir="rtl">
برای شروع کار با این کتاب خانه تنها نیازه به فایل CubeMX من مراجعه کنید
و تنظیمات را مانند فایل من قرار دهید، البته فقط نیازه روی پین مربوط به 
WS2812
فوکوس کنید، چون بقیه پین ها اهمیتی ندارند
برای ست کردن کلاک هم در فایل هدر، با توجه به کلاک تایمر خود اقدام کنید، سپس با سعی و خطا آن را دقیق تر کنید
</p>
