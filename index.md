---
---

# Algèbre Commutative et Effective

## Informations pratiques

**Cours** les lundis de 9h30 à 12h30, avec [Nicolas Perrin](http://lmv.math.cnrs.fr/annuaire/nicolas-perrin/).

**TDs** les lundis de 14h à 17h, avec [Luca De Feo](https://defeo.lu/).

**Serveurs SageMath**

- Serveur de l'UFR <https://jupyter.ens.uvsq.fr/>;
- En cas de panne: <https://sage.prism.uvsq.fr/> (**attention :**
  données non sauvegardées).

## Matériel de cours

- Le [polycopié de cours](poly) et le [polycopié de TD](polytd);
- Les [exercices de TD](exercises)*, et les
  [corrections](https://defeo.lu/MA2-ace-notebooks/)*{:.corr style="display:none"};
- [*Calcul mathématique avec Sage*](http://sagebook.gforge.inria.fr/).


## Calendrier

TD 1 (28/09/2018)
: [Introduction à l'environnement de travail et à SageMath](polytd#introduction-à-lenvironnemnt-de-travail-et-à-sagemath),
: [Structures algébriques de base en SageMath](polytd#anneaux-corps-polynômes-expressions),
: **Exercices :** [Manipuler les polynômes en SageMath](exercises#polynômes-à-une-variable),
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/0/TD1){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 2 (01/10/2018)
: [Anneaux de polynômes en SageMath](polytd#polynômes),
: **Exercices :** [Polynômes](exercises#polynômes-à-une-variable).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/6/TD2){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 3 (12/10/2018)
: **Exercices :** [Bases de Gröbner](exercises#idéaux-monomiaux).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/5/TD3){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 4 (15/10/2018)
: [Structures de contrôle en Python](polytd#syntaxe-pythonsage),
: **Exercices :** [Programmation Python/Sage](exercises#programmation-pythonsage).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/2/TD4){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 5 (19/10/2018)
: **Exercices :** [Bases de Gröbner](exercises#calcul-de-bases-de-gröbner).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/3/TD5){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 6 (09/11/2018)
: **Exercices :** [Élimination](exercises#résultants-et-élimination).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/4/TD6){:target="_blank"} de la séance.*{:.corr style="display:none"}

TD 7 (12/11/2018)
: **Exercices :** [Élimination et fonction de Hilbert](exercises#rappel-sur-les-idaux).
: *Le [Jupyter notebook](https://defeo.lu/MA2-ace-notebooks/#/nb/notebook/1/TD7){:target="_blank"} de la séance.*{:.corr style="display:none"}

## Annales

Devoir maison 2018
: [Coloration de graphes](misc/dm2018)

Devoir maison 2017
: [Cryptanalyse algébrique](misc/dm2014)

Devoir maison 2015
: [Résultants successifs](misc/dm2015)

Devoir maison 2013
: [FGLM](misc/dm2013)

## Ressources

[*Calcul mathématique avec Sage*](http://sagebook.gforge.inria.fr/)
: A. Casamayou, N. Cohen, G. Connan, T. Dumont, L. Fousse, F. Maltey,
M. Meulien, M. Mezzarobba, C. Pernet, N. M. Thiéry,
P. Zimmermann. <http://sagebook.gforge.inria.fr/>

[*Doc officielle de SageMath*](http://sagemath.org/doc/index.html)
: <http://sagemath.org/doc/index.html>

[*Doc officielle de Python*](https://docs.python.org/2/)
: <https://docs.python.org/2/>

[*Poly*](http://webusers.imj-prg.fr/~ariane.mezard/Grobner.pdf), par Arianne Mézard
: <http://webusers.imj-prg.fr/~ariane.mezard/Grobner.pdf>

[*Algorithmes Efficaces en Calcul Formel AECF*](https://hal.archives-ouvertes.fr/AECF/)
: A. Bostan, F. Chyzak, M. Giusti, R. Lebreton, G. Lecerf, B. Salvy et
É. Schost. <https://hal.archives-ouvertes.fr/AECF/>

Les définitions des [ordres monomiaux dans Sage](http://doc.sagemath.org/html/en/reference/polynomial_rings/sage/rings/polynomial/term_order.html)
: <http://doc.sagemath.org/html/en/reference/polynomial_rings/sage/rings/polynomial/term_order.html>


<script>
if ((new Date()).getMonth() < 8 || window.location.hash.startsWith('#corr'))
	$$('.corr').forEach((s) => s.css({ display: 'inline', 'font-style': 'normal' }));
</script>
