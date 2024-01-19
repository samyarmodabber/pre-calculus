::: {dir="rtl"}

# قدر مطلق

> قدر مطلق یا اندازه ی یک عدد حقیقی $a$ که با نماد $|a|$ نمایش داده می شود، برابر با خود $a$ تعریف می شود هر گاه $a$ عددی نامنفی (مثبت یا صفر) باشد در غیر این صورت مساوی با قرینه ی $a$ تعریف می شود. به زبان نمادین

$$
|a| = \left\{ \begin{matrix}
a\ ;\ \ \& a \geq 0\ اگر \\
 - a\ ;\ \ \& a < 0\ اگر \\
\end{matrix} \right.\
$$

به عنوان مثال

> $|0| = 0$(ب
>
> $| - 0.21| = 21$(الف
>
> \$\|3x - 1\| = \\left{
>
> ```{=tex}
> \begin{matrix} 3x - 1\ \ \ \ \ \ \ \ \ ;\ 3x - 1 \geq 0\ اگر \\  - (3x - 1)\ \ ;\ 3x - 1 < 0\ اگر \\ \end{matrix}
> ```
>
> \right.\$(ب
>
> $\left| - \frac{3}{5} \right| = \frac{3}{5}$(الف

اما $3x - 1 \geq 0$ یعنی $3x \geq + 1$ و با تقسیم طرفین نامساوی بر $3$ داریم $x \geq \frac{1}{3}$، همچنین $3x - 1 < 0$ یعنی $3x - 1 < 0$ یعنی $3x < + 1$ و با تقسیم طرفین نامساوی بر $3$ داریم $x < \frac{1}{3}$، پس می توان نوشت:

$$
|3x - 1| = \left\{ \begin{matrix}
3x - 1\ \ \ \ \ \ \ \ \ ;\ \ x \geq \frac{1}{3}\ اگر \\
 - 3x + 1\ \ \ \ \ ;\ \ \ x < \frac{1}{3}\ اگر \\
\end{matrix} \right.\
$$

از تعریف قدر مطلق می توان فهمید، قدر مطلق هر عدد نا منفی با خود آن عدد مساوی است. برای مثال، از آن جا که توان دوم (مربع) هر عدد حقیقی مانند $x$ نامنفی است یعنی $x^{2} \geq 0$، با افزودن $+ 1$ به طرفین این نامساوی داریم: $x^{2} + 1 \geq 1$ لذا $x^{2} + 1 > 0$، بنابراین می توان نوشت:

$$
\left| x^{2} + 1 \right| = x^{2} + 1
$$

تذکر: قبلا گفته شد به ازای هر عدد حقیقی نامنفی مانند $a$ دو عدد حقیقی مانند \$–x\$ و \$ x\$ وجود دارند به طوری که ${( - x)}^{2} = a$ و \$ x\^{2} = a\$ این اعداد را ریشه ی دوم های $a$ می نامیم و از نماد \$\sqrt{a}\$ فقط برای نمایش ریشه ی نامنفی استفاده می کنیم پس

$$
\sqrt{x^{2}} = \sqrt{a} = \left\{ \begin{matrix}
x\ \ \ \ \ ;\ \ x \geq 0\ اگر \\
 - x\ ;\ \ \& x < 0\ اگر \\
\end{matrix} \right.\
$$

از مقایسه ی این رابطه با تعریف قدر مطلق، می توان نتیجه گرفت $\sqrt{x^{2}} = |x|$ .

قضیه. هر گاه $b$ و \$  a\$ دو عدد حقیقی باشند و $n$ یک عدد طبیعی باشد آن گاه خواص زیر همواره برقرارند:

$|a| = 0 \Leftrightarrow a = 0$(الف

$|a| = | - a|$ (ب

$|ab| = |a||b|$ (ج

$\left| \frac{a}{b} \right| = \frac{|a|}{|b|}\ ;(b \neq 0)$(د

هر گاه در قانون سوم $a = b$ باشد، آن گاه $\left| a^{2} \right| = |a.a| = |a|.|a| = |a|^{2}$، که از تعمیم آن خواهیم داشت:

$\left| a^{n} \right| = |a|^{n}$.

**برهان.**

الف. اگر $a = 0$، آن گاه بنابر تعریف قدر مطلق $|a| = |0| = 0$. اگر $a \neq 0$، آن گاه $- a \neq 0$ خواهد بود چون بنا بر تعریف قدر مطلق $|a| = \pm a$، لذا در هر صورت $|a| \neq 0$.

ب. اگر $a = 0$، آن گاه بنا بر تعریف قدر مطلق $|0| = 0$ پس $|0| = | - 0|$. اگر $a > 0$، آن گاه $|a| = a$، در این حالت $- a < 0$ خواهد بود، پس بنا بر تعریف $|a| = | - a|،| - a| = - ( - a) = a$*.*

ج. برای دو عدد حقیقی $b$ و \$ a\$، اگر این دو عدد نامنفی باشند، آن گاه حاصل ضرب آن ها نیز نامنفی است. پس بنا بر تعریف قدر مطلق، برای این مقادیر نامنفی داریم

$$
\left\{ \begin{matrix}
|a| = a\ \ \ \ \  \\
|b| = b\ \ \ \ \  \\
|ab| = ab \\
\end{matrix} \right.\
$$

پس در این حالت، $|ab| = ab = |a||b|$. اگر $b$ و \$ a\$ دو عدد منفی باشند، آن گاه حاصل ضرب آن ها نیز مثبت است. پس بنا بر تعریف قدر مطلق، برای این مقادیر داریم

$$
\left\{ \begin{matrix}
|a| = - a\ \ \ \ \  \\
|b| = - b\ \ \ \ \  \\
|ab| = - ab \\
\end{matrix} \right.\
$$

در این حالت نیز $|ab| = ab = ( - a)( - b) = |a||b|$.دو حالت مختلف دیگر را دانشجو می تواند

به طور مشابه برسی نمایید.

راه دوم

\|ab\|=(ab)²=a²b²=√a²√b²=\|a\|\|b\|

ابتدا نشان می دهیم به ازای هر عدد حقیقی$\frac{1}{|b|}$,≠ 0 =\| $\frac{1}{b}$\|. توجه داریم که اگر bمثبت باشد آنگاه $\frac{1}{b}$ نیز مثبت است و داریم

\|b\| =b

$\frac{1}{b}$\|= $\ \frac{1}{b}$.\|

پس در این حالت $\frac{1}{|b|}$, =\| $\frac{1}{b}$\| ولی اگر منفی باشد آنگاه نیز منفی است داریم

\|b\| =-b

$\frac{1}{b}$\|= - $\ \frac{1}{b}$.\|

بنابراین در هر حالت به ازای هر عدد حقیقی حال برای اثبات مورد چهارم می توان از خاصیت سوم بهره گرفت و نوشت

$\frac{a}{1}$× $\frac{1}{b}$ \| =\| $\frac{a}{b}$\|

قدر مطلق و چند مساوی مهم

قضیه . هرگاه و دو عدد حقیقی یک عدد حقیقی منفی باشد خواص زیر همواره برقرارند

الف ) \|a\|≤ k -k ≤ a ≤ k

ب) b - \|a\| ≤ a ≤ \|a\|

ج) \|a\| ≥ k a ≥ k یا a ≤ - k

د) │\|a\|- \|b\|│≤ \|a±b\| ≤ \|a\|+\|b\|

برهان

الف) چون قضیه به صورت دو شرطی (اگر و تنها اگر ) بیان شده است ابتدا فرض می کنیم ، در این صورت با توجه به اینکه یا برابر با است بنابراین از نتیجه می گیریم که هم و هم که با ضرب طرفین در یک 1- می توان نتیجه گرفت پس

بر عکس فرض کنیم با ضرب طرفین در می توان نتیجه گرفت پس هم لذا بنابر تعریف باید

ب) برای اثبات کافی است در قسمت اول قضیه به جای عدد را جایگزین نمایید

ج) چون پس هر گاه آنگاه

الف ) a ≥ 0 \|a\| = a ≥ k

ب) a \< 0 \|a\| = -a ≥ k a ≤ -k

بر عکس هر گاه یا آنگاه معادله داریم

A ≥ k یا --a ≥ k

پس در هر حالت خواهد داشت

د) ابتدا نشان میدهیم با استفاده مکرر از قسمت دوم قضیه می توان نوشت که از جمع ای نا مساوی ها داریم

-\|a\| ≤ a ≤ \|a\|

-\|b\| ≤ b ≤ \|a\|

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\- (\|a\| + \|b\|) ≤ a+b ≤ \|a\| +\|b\|

حالا با استفاده از قسمت اول قضیه می توان نوشت :

\|a+b\| ≤ \|a\| +\|b\|

(1)

با توجه به اینکه ثابت کردیم نا مساوی (1) برای هر دو عدد طبیعی دلخواه درست است پس برای دو عدد نامساوی (1) می توان ه صورت زیر نوشت

\|a-b\| ≤ \|a\| + \|-b\|

اما قبلا ثابت کردیم پس نامساوی بالا را می توان به صورت زیر نوشت

(2)

\|a-b\| ≤ \|a\| + \|b\|

با استفاده از نا مساوی (1) می توان نوشت

\|a\| = \|a-b+b\| ≤ \|a-b\|

(3)

اگر در این نا مساوی (3) جای را با هم تعویض کنیم داریم

\|b\|-\|a\| ≤ \|b - a\| = \|a-b\|

با ضرب طرفین در 1- خواهیم داشت :

-\|a\| - \|b\| ≥ -\|a-b\|

(4)

حال با ادغام نامساوی (3) و (4) داریم

-\|a-b\| ≤ \|a\| - \|b\| ≤ \|a-b\|

که در نهایت در با استفاده از قسمت اول قضیه این نا مساوی معادل است با

(5)

│\|a\| - \|b\|│≤ \|a-b\|

اگر در این نا مساوی (5) جای و را با هم تعویض نماییم

│\|a\| - \|-b\|│≤ \|a- (-b)\|

│\|a\| - \|b\|│≤ \|a+b)\|

(6)

از ادغام همه ی نا مساوی های (1) ، (2) ، (5) و (6) می توان نوشت:

│\|a\| - \|b\|│≤ \|a ± b\| ≤ \|a\| +\|b\|

نا مساوی های مطرح شده در قسمت چهارم به نامساو های مثلثی مشهور است کاربرد های فراوانی دارد هر جا که با نا مساوی سر و کار داشته باشیم از این نا مساوی یاد می کنیم اما اینکه چرا آن را نا مساوی مثلثی می گویند به این دلیل است که در هر مثلث اندازه هر ضلع از مجموعه اندازه های هر دو ضلع دیگر آن کوچک تر است و اندازه همین ضلع تفاضل دو ضلع دیگر بزرگتر است

از مفهوم قدر مطلق برای تعریف فاصله ی بین دو نقطه روی محور اعداد استفاده می کنند

فرض کنید طول این دو نقطه روی محور اعداد به ترتیب و باشد فاصله بین و را با نماد نشان داده و آن را به صورت زیر تعریف میکنیم.

D(a,b) = \|a - b\|

چون طبق خواص بالا است پس

D(a,b) = \|a - b\| = \|-(a-b)\| = \|b-a\| = d (b,a)

عدد طول پاره خط نامیده می شوند

مثال 31. مجموعه همه ی اعداد حقیقی که فاصله ی آنها از کوچک تر از 0.1 اشد را مشخص نمایید.

هرگاه مجموعه ی مورد نظر باشد، داریم

A = {x € R : \|x-2\| \< 0.1}

با توجه به خواص قدر مطلق می توان نوشت

A = {x € R : 0.1 - \< x-2 \< 0.1} = { x € R : 1.9 \< X \<2.1 } = (1.9, 2.1 )

ماکزیمم: بین دو یا چند عدد حقیقی عددی که بزرگتر یا مساوی این اعداد باشد ماکزیمم نامیده میشود

اعداد حقیقی معمولا با نماد نمایش داده می شود و به عبارت دیگر اگر حقیقی باشد آنگاه

Max {a } = m m ≥ a

مینیمم بین دو یا چند عدد حقیقی عددی که کوچیکتر یا مساوی بقیه اعداد باشد مینیمم اعداد نامیده می شود. مینیمم عدد حقیقی با نماد نمایش داده می شود به عبارت دیگر اگر یک عدد حقیقی باشد آنگاه

Max

مثال 32. نشان دهید اگر و دو عدد حقیقی باشد آنگاه

الف) max {a ,b } = )a+b) + \|a-b\|

2

ب) min {a ,b } = )a+b) - \|a-b\|

2

اثبات : برای اثبات قسمت اول کافی است نشان دهیم سمت راست تصاویر دقیقا برابر با ماکزیمم است.

A ≥ b → a-b ≥ 0 →\|a-b\| = a-b

(a+b) +\|a --b\| = a+b+a-b = 2a = a = MaX {a,b}

\_\_\_\_\_\_\_\_\_\_ \_\_\_\_\_\_ \_\_\_

2 2 2

A ≤ b → a-b ≤ 0 →\|a-b\| = -( a-b)

(a+b) +\|a --b\| = a+b+a+b = 2b = b = MaX {a,b}

\_\_\_\_\_\_\_\_\_\_ \_\_\_\_\_\_ \_\_\_

2 2 2

قسمت دوم مشابه با قسمت اول اثبات می شود.

:::