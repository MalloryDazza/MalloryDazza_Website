---
title: "Chapitre 1 : La mole"
subtitle: "Comment déterminer la composition d'un système chimique ?"
excerpt: "Afin de suivre lévolution d'un système chimique il faut trouver comment quantifier l'état d'un système chimique. Quelles sont les grandeurs physiques pertinentes ? "
date: '2021-12-10'
draft: false
weigth: 1
math: true
editor_options: 
  markdown: 
    wrap: 72
---

# *Le cours*

## *Masse molaire d'une expèce chimique*

Les atomes sont des entités quasi indestrictibles. Le mot atome provient
du grec ancien, `\(\alpha \tau \omicron \mu \omicron \sigma\)` [átomos],
signifiant insécable. En effet, pour un chimiste l'atome est la plus
petite partie d'un corps pouvant se combiner les uns avec les autres.
Seuls les physiciens atomique utilisant des énergies considérable
arrivent à briser un atome et étudier leur composition quantique.

$$
`\begin{equation}
  f\left(k\right) = \binom{n}{k} p^k\left(1-p\right)^{n-k}
  \tag{1}
\end{equation}`
$$
Thus (1) is a figure

Ainsi, pour caractériser un système chimique il nou faudra simplement
compter les atomes. Malheureusement ceux-ci sont en nombre gigantesque.
Dans une goutte d'eau il y a `\(16 \times 10^{20}\)` molécules `\(\text{H}_2\)`O. Il
nous faut donc trouver un moyen de compter les molécule et atomes par
paquet et non un par un. Ces paquets sont appelés moles.

Une mole d'entités contient exactement `\(6,022 140 76 \times 10^{23}\)`
entités (atomes ou molécules). Nous utiliserons la valeur arrondie à
`\(6 \times 10^{23}\)` entités.

{{< panelset class="greetings" >}}
{{< panel name="Definition" >}}
<div class="definition"><span class="definition" id="def:avogadro"><strong><span id="def:avogadro"></span>Definition 1  </strong></span>Le nombre d’entités, atomes, molécules, particules, ions etc… dans une mole de matière est la constante d’Avogadro. Elle est notée <span class="math display">\[N_A = 6,02 \times 10^{23} \text{ entités / mol}\]</span></div>
{{< /panel >}}
{{< panel name="Utilisation" >}}
Nous utiliserons souvent la *mole* pour compter le nombre d'atomes ou molécules dans une solution chimique. Par exemple, nous pouvons déterminer le nombre total d'ion cuivre (II) `\(\text{Cu}^{2+}\)` dans une solution contenant 0,1 mol : 
`$$\begin{align}
N_{Cu^{2+}} &= N_A \times 0,1 \\
            &= 6,02 \times 10^{23} \times 0,1 \\
            &= 6,02 \times 10^{22} \text{ ions}
\end{align}$$`
Il y a donc `\(6,02 \times 10^{22}\)` ions `\(\text{Cu}^{2+}\)` dans la solution. Il sera utile de calculer la masse que cela représente.
{{< /panel >}}
{{< /panelset >}}

---

Effectivement, dans la vie de tous les jours, nous sommes
plus familier avec les notions de masse. Il est plus simple de peser un
solide que de compter ses atomes ! Ainsi, nous utilierons souvent la
masse d'une mole de matière.

{{< panelset class="greetings" >}}
{{< panel name="Definition" >}}
<div class="definition"><span class="definition" id="def:massemolaire"><strong><span id="def:massemolaire"></span>Definition 2  </strong></span>La masse molaire de l’espèce chimique A, notée <span class="math inline">\(M_A\)</span> est la masse d’une mole de matière. Elle s’exprime en <span class="math inline">\(\text{g.mol}^{-1}\)</span></div>
{{< /panel >}}
{{< panel name="Utilisation" >}}
Cette grandeur est très facile à utiliser. Elle représente la masse
d'un nombre fixe d'entités : `\(N_A\)` atomes ou molécules. Ainsi si 1 mol de cuivre pèse `\(M_{Cu} = 63,546\)` g, alors 0,1 mol d'atome de cuivre pèse :

$$
`\begin{align}
m_{Cu} &= M_{Cu} \times 0,1 \\
            &= 63,546 \times 0,1 \\
            &= 6,3546 \text{ g}
\end{align}`
$$

Donc 0,1 mol de cuivre représente `\(6,02 \times 10^{22}\)` atomes et pèse 6,3 g.

{{< /panel >}}
{{< /panelset >}}

---

Comment connaitre la masse molaire d'un élément chimique comme le cuivre ? Nous ne pouvons pas la deviner, mais elle est renseignée sur tous les tableaux périodiques des éléments. La figure <a href="#fig:CNO">1</a> montre où retrouvez la masse molaire dans un tableau periodique. L'unité sera toujours le `\(\text{g.mol}^{-1}\)`.

<div class="figure" style="text-align: center">
<img src="images/CNO.png" alt="Extrait du tableau périodique des éléments représentant le Carbone, Azote et Oxygène." width="60%" />
<p class="caption">Figure 1: Extrait du tableau périodique des éléments représentant le Carbone, Azote et Oxygène.</p>
</div>

---

***QUESTION***

La masse molaire de l'oxygène étant de 16 `\(\text{g.mol}^{-1}\)`. Quelle est la
masse molaire de la molécule de dioxygène `\(\text{O}_2\)` ?

{{< panelset class="greetings" >}}
{{< panel name="Cacher la réponse !" >}}

{{< /panel >}}
{{< panel name="Afficher la réponse !" >}}
  Il le même nombre d'atome d'oxygène dans une mole d'oxygène que de
molécule de dioxygène dans une mole de dioxygène. Ainsi, la masse
molaire du dioxygène est le double de la masse molaire d'oxygène : 
$$ 
  M_{O_2} = 2 \times M_{O}
  = 2 \times 16
  = 32 \text{ g.mol}^{-1}
$$
{{< /panel >}}
{{< /panelset >}}

---

*Rappel: Un élément chimique est définit par le nombre de proton au sein
de son noyaux. Ainsi, tous les atomes d'oxygène ont 8 protons, tous les
atomes de carbone ont 6 protons etc...*

Nous savons que la masse d'un atome provient principalement de la masse
du noyaux. en effet, le électrons sont extrémement légers en comparaison
aux nucléons. Ainsi, la masse molaire est directement lié à la masse du
noyau des atomes. Or la stabilité du noyau d'un même élément chimique
n'est pas toujours la même. En effet, il existe pour un même éléments
chimique plusieurs isotopes. Par exemple, un isotope du carbone 12
contenant 6 protons et 6 neutrons est le carbone 14 contenant 6 proton
et 8 neutrons. La masse d'une mole de carbone 12 est plus petite qu'une
masse d'atome de carbone 14.

Comment savoir si dans une molécule de sucre `\(\text{C}_{12}\text{H}_{22}\text{O}_{11}\)` nous avons plus de carbone 14 ou de carbone 12 ?

La masse molaire que nous utilisons, et que nous trouverons dans le
tableau périodique des éléments prend en comptes l'abondance naturel des
isotope de chaque élément. Ainsi, la masse molaire est une moyenne sur
l'ensemble des isotopes les plus* stables.

**Formule A Retenir**: La masse molaire moléculaire est la
somme des masses molaires des atomes qui la constitue :

$$ M_{\text{molecule}} = \sum M_{atome}$$ 

## *La quantité de matière*

La quantité de matière est la grandeur physique exprimée en mol, représentant le nombre d'entités chimiques (molécules, atomes, ions etc... ) d'une substance. Par exemple, le nombre de molècule dans une masse `\(m=10\)` g de sucre peut s'exprimée comme : 

- une quantité de matière `\(n=0,05\)` mol 
- un nombre de molécules `\(N = 0,05 \times N_A = 0,3 \times 10^{23}\)`

On peut remarqué que le nombre de molécule, `\(N\)`, n'a pas d'unité : c'est un nombre de molécules de sucre. La quantité de matière, `\(n\)` est une grandeur physique équivalente : elle représente aussi le nombre de molécules. Seulement, elle est exprimée en mole, c'est-à-dire en nombre de paquet de molécules.
