### Es 1a

$\displaystyle \int \dfrac{x}{\sqrt{x^2 + 5}^3} dx$

$\displaystyle \int x (x^2 + 5)^{-\dfrac{3}{2}} dx$

Definiamo $X^2 + 5$ come $t$

$dt = \dfrac{d}{dx} x^2 + 5 = 2x \quad dx$

$dx = \dfrac{dt}{2x}$

$\displaystyle \int \dfrac{x}{2x} \cdot t^{-\dfrac{3}{2}} dt$

$\displaystyle \int \dfrac{1}{2} \cdot t^{-\dfrac{3}{2}} dt$

$\displaystyle \dfrac{1}{2} \int t^{-\dfrac{3}{2}} dt$

Come lo integriamo?

$\displaystyle \int x^n = \dfrac{x^{n + 1}}{n + 1}$

$t^{-\dfrac{3}{2} + 1} \cdot \dfrac{1}{- \dfrac{3}{2} + 1}$

$-2 t^{- \dfrac{1}{2}}$

$-\dfrac{2}{\sqrt{t}}$

$\displaystyle \dfrac{1}{2} \int t^{-\dfrac{3}{2}} dt \rightarrow \dfrac{1}{2} \cdot -\dfrac{2}{\sqrt{t}} = -\dfrac{1}{\sqrt{t}}$

Revertiamo la sostituzione

$t = x^2 + 5$

$- \dfrac{1}{\sqrt{x^2 + 5}} + C$

---

### Es 2a

$\displaystyle \int t^5 e^{-t^6}$

$\dfrac{d}{dx} e^x = e^x \cdot \dfrac{x}{dx} x = e^x \cdot 1 = e^x$

$\dfrac{d}{dx} e^{x^2} = e^{x^2} \cdot \dfrac{d}{dx} x^2 = 2x e^{x^2}$

Applicando lo stesso principio e supponiamo che ciò di cui dobbiamo calcolare l'integrale sia la derivata di $e^{-t^6}$

$\dfrac{d}{dx} e^{-t^6} =$

$= e^{-t^6} \cdot \dfrac{d}{dx} (-t^6) =$

$= e^{-t^6} \cdot -\dfrac{d}{dx} t^6 =$

$= e^{-t^6} \cdot -6 t^5 =$

$= -6 \cdot t^5 e^{-t^6} = \dfrac{d}{dx} e^{-t^6}$

Ma questo è come l'argomento dell'integrale moltiplicato per $-6$

$ \displaystyle -\dfrac{1}{6} \int -6 \cdot t^5 e^{-t^6} = -\dfrac{1}{6} e^{-t^6}$

Applichiamolo a un caso più semplice lo stesso ragionamento:

$\displaystyle \int \dfrac{1}{3} x^3$

Mi chiedo come ottenere l'argomento dell'integrale come risultato derivando qualcosa e sfrutto il fatto che siano due operazioni inverse

Ma possiamo ottenere qualcosa dell'ordine di $x^3$ derivando qualcosa dell'ordine di $x^4$. Proviamo a derivare $x^4$

$\dfrac{d}{dx} x^4 = 4x^3$

Noi stiamo facendo qualcosa di questo tipo:

$\displaystyle \int \dfrac{a}{b} \dfrac{d}{dx} x^n = \dfrac{a}{b} x^n$

Guardiamolo con questo caso

$\displaystyle \int ? \dfrac{d}{dx} x^4 = \int ? 4x^3 = \int \dfrac{1}{12} x^3$

Il risultato tra $? \cdot 4$ deve essere uguale a $\dfrac{1}{3}$

$t \cdot 4 = \dfrac{1}{3} \rightarrow t = \dfrac{1}{12}$

---

### Es 1g

$\displaystyle \int \dfrac{x}{(4 - x^2)^2} dx$

Appliciamo la sostituzione

$t = 4 - x^2$

$dt = -2x$

$dx = -\dfrac{dt}{2x}$

$\displaystyle \int \dfrac{x / -2x}{t^2} dt$

$\displaystyle - \dfrac{1}{2} \int \dfrac{1}{t^2} dt$

$\displaystyle - \dfrac{1}{2} \int t^{-2} dt$

Calcoliamo $\displaystyle \int t^{-2} dt$

$\displaystyle \int t^{-2} dt = \dfrac{t^{-2 + 1}}{-2 + 1} = \dfrac{t^-1}{-1} = -t^{-1} = -\dfrac{1}{t}$

Applichiamo la costante moltiplicativa esterna all'integrale:

$- \dfrac{1}{2} \cdot -\dfrac{1}{t} = \dfrac{1}{2t}$

Sostituiamo $t = 4 - x^2$

$\dfrac{1}{2t} = \dfrac{1}{2 (4 - x^2)} = \dfrac{1}{8 - 2x^2} + C$
