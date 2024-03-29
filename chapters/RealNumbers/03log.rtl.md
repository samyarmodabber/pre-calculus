# لگاریتم

لگاریتم را می توان به کمک مفهوم اعداد توان دار تعریف نمود. در حالت کلی، هر گاه $a \neq 0$ عددی مثبت باشد و $a^{x = y}$ آن گاه $x$ را لگاریتم عدد $y$ در پایه ی $a$ می گوییم و آن را با نماد $\log_{a}^{y}$ نمایش می دهیم.عدد $y$ را آرگومان لگاریتم و عدد $a$ بر پایه ی (مبنای) لگاریتم می نامیم. در حقیقت

$$
\log_{a}^{y} = x \Leftrightarrow a^{x} = y.
$$

چون لگاریتم به کمک اعداد توان دار تعریف شده است، برای بدست آوردن مقدار $\log_{2}^{\sqrt{2}}$، باید از خود این سوال را پرسید که $2^{?} = \sqrt{2}$ با توجه به آن چه پیش تر در بحث توان گفته شد، $2^{\frac{1}{2}} = \sqrt{2}$ پس می توان گفت: $\log_{2}^{\sqrt{2}} = \frac{1}{2}$.

تذکر: همان طور که در تعریف لگاریتم ملاحظه می کنید. پایه ی لگاریتم $a \neq 0$ عددی مثبت در نظر گرفته شده است.

چون $y = a^{x} > 0$ ، پس در $\log_{a}^{y}$ آرگومان لگاریتم یعنی $y$ باید مثبت باشد. به عبارت دیگر لگاریتم برای اعداد حقیقی منفی و صفر تعریف نمی شود.

هرگاه در تساوی $\log_{a}^{y} = x$ به جای $y$ مقدار معادل آن یعنی $a^{x}$ را بگذاریم، خواهیم داشت $\log_{a}^{a^{x}} = x$*.* مشابها، اگر در تساوی $a^{x} = y$ به جای $x$ مقدار معادل آن یعنی $\log_{a}^{y}$ را بگذاریم، خواهیم داشت $a^{\log_{a}^{y}} = y$. دو رابطه $\log_{a}^{a^{x}} = x$ و $\log_{a}^{y} = x$ بیانگر این مطلب مهم هستند که لگاریتم و عمل به توان رسانیدن همدیگر را خنثا می کنند.

با استفاده از قوانین نماها و تعریف لگاریتم به سادگی می توان قوانین زیر را برای لگاریتم به دست آورد:

فرض کنید $b\ ،a$ و $c \neq 1$ اعداد حقیقی مثبتی باشند، در این صورت

الف.لگاریتم عدد یک در هر پایه ای برابر با صفر است. یعنی

$$
\log_{c}^{1} = 0.
$$

زیرا $.c^{0} = 0$

ب. لگاریتم هر عددی در پایه ی خودش برابر با یک است. یعنی

$$
\log_{c}^{c} = 1.
$$

زیرا $.c^{1} = 1$

ج. لگاریتم حاصل ضرب برابر با مجموع لگاریتم ها است یعنی

$$
\log_{c}^{ab} = \log_{c}^{a} + \log_{c}^{b}.
$$

د. لگاریتم خارج قسمت برابر با تفاضل لگتریتم ها است. یعنی

$$
\log_{c}^{\frac{a}{b}} = \log_{c}^{a} - \log_{c}^{b}.
$$

ه. توان آرگومان را می توان به عنوان ضریب لگاریتم نوشت. یعنی

$$
\log_{c}^{a^{m}} = m\log_{c}^{a}.
$$

و. هر گاه در لگاریتم هم پایه و هم آرگومان لگاریتم هر دو دارای توان باشند، آن گاه این توان ها را می توان به صورت یک ضریب کسری نوشت. یعنی

$$
\log_{c^{n}}^{a^{m}} = \frac{m}{n}\log_{c}^{a};\ (n \neq 0).
$$

ز. یک لگاریتم را می توان به صورت خارج قسمت دو لگاریتم با پایه ای مشترک نوشت. یعنی

$$
\log_{b}^{a} = \frac{\log_{c}^{a}}{\log_{c}^{b}};\ (a \neq b > 0).
$$

ح. در لگاریتم اگر جای پایه و آرموگان را لگاریتم را با هم عوض کنیم حاصل لگاریتم معکوس می شود. یعنی

$$
\log_{ز}^{a} = \frac{1}{\log_{a}^{c}}\overset{کردن\ وسطین$ و $ طرفین}{\Rightarrow}\log_{c}^{a} \times \log_{a}^{c} = 1.
$$

تذکر: هر گاه در لگاریتم پایه ی لگاریتم عدد 10 باشد لگاریتم را لگاریتم اعشاری می نامیم و معمولا پایه ی لگاریتم را نمی نویسیم. برای مثال، $\log_{10}^{6}$ به طور اختصار به صورت $\log^{6}$ نوشته می شود.

> تذکر: هر گاه در لگاریتم پایه ی لگاریتم عدد گنگ $e = \frac{2}{71}\ldots$ باشد معمولا لگاریتم را لگاریتم طبیعی $(natural\ logarithm)$می گویند. در این حالت لگاریتم طبیعی $a$ را با نماد $a$ $\ln$ نمایش می دهند برای مثال، $\log_{e}^{6}$ به طور اختصار به صورت $6$ $\ln$ نوشته می شود. عدد $e$ را با افتخار ریاضیدان بزرگ اسکاتلندی، جان نپر (معرف لگاریتم) عدد نپر می نامند. با توجه به تعریف لگاریتم $y = x \Leftrightarrow e^{x} = y$ $\ln$ و از آن جایی که گفته شد آرگومان لگاریتم یعنی $y$ باید مثبت باشد پس همواره $y = e^{x} > 0$. تمام قواعد ذکر شده در مورد لگاریتم، برای لگاریتم طبیعی نیز معتبر است.

مثال 29. هر گاه \$\\left{

```{=tex}
\begin{matrix} log2 + log3 = a \\ log3 + log7 = b \\ log7 + log2 = c \\ \end{matrix}
```

\right.\$، آن گاه برای محاسبه $log42$ از حاصل جمع معادلات داده شده داریم:

$$
\left( \log 2 + \log 3 \right) + \left( \log 3 + \log 7 \right) + \left( \log 7 + \log 2 \right) = a + b + c
$$

$$
\Rightarrow 2\left( \log 2 + \log 3 + \log 7 \right) = a + b + c
$$

$$
\Rightarrow 2\log(2 \times 3 \times 7) = a + b + c
$$

$$
\Rightarrow \log 42 = \frac{1}{2}(a + b + c)
$$