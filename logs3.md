# Proprietà dei logaritmi:

1) Definizione di logaritmo: \
$a^{\log_a b} = b$
---
2) Logaritmo del prodotto: \
${\log_a b \cdot c} = \log_a b + \log_a c$
---
3) Regola dell'esponente: \
${\log_a b^c} = c \cdot \log_a b$
---
4) Logaritmo del rapporto: \
$\log_a \dfrac{b}{c} = \log_a b - \log_a c$
---
5) Formula del cambiamento di base per logaritmi: \
$\log_a b = \dfrac{\log_c b}{\log_c a}$
---
6) Formula di inversione per i logaritmi: \
$\log_a b = \dfrac{1}{\log_b a}$
---

# Esercizi 

$\log_a (a^b) \cdot \log_a (a^b \cdot a) \cdot \log_{\sqrt{a}} (\sqrt[3]{a^b})$

$b \log_a a \cdot \log_a a^(2b) \cdot \log_{\sqrt{a}} (\sqrt[3]{a^b})$

$b \log_a a \cdot 2b \log_a a \cdot \log_{\sqrt{a}} (\sqrt[3]{a^b})$

$b \cdot 2b \cdot \log_{\sqrt{a}} (\sqrt[3]{a^b})$

$\log_{\sqrt{a}} (\sqrt[3]{a^b})$ 

Cambiamo base in $a$:

$\log_{\sqrt{a}} (\sqrt[3]{a^b}) = \dfrac{\log_a (\sqrt[3]{a^b})}{\log_a \sqrt{a}}$

Ma $\log_a \sqrt{a} = \dfrac{1}{2}$

Invece $\log_a (\sqrt[3]{a^b}) = \dfrac{b}{3}$

Dunque:

$\dfrac{b}{3} \cdot 2 = \dfrac{2b}{3}$

$b \cdot 2b \cdot \log_a a^{\dfrac{2b}{3}}$

$b \cdot 2b \cdot \dfrac{2b}{3}$

$a = 4, b = 1$

$\log_{\sqrt{a}} (\sqrt[3]{a^b}) \rightarrow log_2 \sqrt[3]{4} \rightarrow log_2 2^{\frac{2}{3}} \rightarrow \dfrac{2}{3}$

Infatti per $b = 1 \rightarrow \dfrac{2b}{3} = \dfrac{2}{3}$

$a = 4, b = 2$

$\log_{\sqrt{a}} (\sqrt[3]{a^b}) \rightarrow log_2 \sqrt[3]{16} \rightarrow log_2 2^{\frac{4}{3}} \rightarrow \dfrac{4}{3}$

Infatti per $b = 2 \rightarrow \dfrac{2b}{3} = \dfrac{4}{3}$

https://www.wolframalpha.com/input?i2d=true&i=Log%5Ba%2CPower%5Ba%2Cb%5D%5D+*+Log%5Ba%2CPower%5Ba%2Cb%5D+*+a%5D+*+Log%5BSqrt%5Ba%5D%2CCbrt%5BPower%5Ba%2Cb%5D%5D%5D

$(a^{\frac{1}{2}})^x = a^{\dfrac{b}{3}}$