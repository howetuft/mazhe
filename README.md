# Mazhe

This is a big course of mathematics declined in two versions.

* [Le Frido](http://student.ulb.ac.be/%7Elclaesse/lefrido.pdf)  contient des mathématiques du niveau de l'agrégation. Il recouvre à peu près tout le programme.  
* [(almost) Everything I know in mathematics](http://student.ulb.ac.be/%7Elclaesse/mazhe.pdf) contains more or less everything I know in mathematics, including my research.
* [readme.pdf](http://student.ulb.ac.be/%7Elclaesse/readme.pdf) contient des instruction pour la compilation du Frido, ainsi que des politiques éditoriales à l'attention de qui voudrait contribuer.

Les sources sont sur [github](https://github.com/LaurentClaessens/mazhe).

## Le Frido (niveau agrégation)


[Le Frido](http://student.ulb.ac.be/%7Elclaesse/lefrido.pdf) contient des mathématiques du niveau de l'agrégation. Il recouvre à peu près tout le programme. Affin de donner une idée, une liste (pas spécialement à jour) des développements que vous pourriez y trouver est en annexe.


### Quelque éléments en plus que l'agrégation

* construction compète de la mesure de Lebesgue, y compris les notions de complétion de mesure (le chapitre tribu/théorie de la mesure est assez lourd)
* la topologie exacte des espaces de distribution, y compris la topologie liée à une famille de semi-normes.
* la notion de produit semi-direct de groupe, et la décomposition du groupe des isométries de `R^n` en translation plus rotation.

### Ce qu'il manque pour l'agrégation

Cette liste est certainement hautement non-exhaustive en ce qui concerne les choses qu'il faudrait savoir pour passer l'agrégation, mais que l'on ne trouve pas dans le Frido.

* le chapitre sur la géométrie projective est pauvre.
* le chapitre sur les espaces affines est pauvre.
* très peu de calcul numérique.
* il manque des exemples de tout, partout.

### Originalité

Ce cours se distingue d'autres cours de mathématique pour l'agrégation de plusieurs manières.

#### En positif

* La licence est libre : vous pouvez le copier, le distribuer, l'imprimer et le modifier sans demander d'autorisation.
* Le Frido contient de quoi dire sur presque toutes les leçons en un seul volume. Certes c'est épais, mais cela évite de devoir mémoriser une liste associative qui à une leçon fait correspondre une liste de livres. Le Frido est de plus certainement plus léger que l'ensemble des livres dont vous auriez besoin pour couvrir la même matière.
* Les références sont toutes vers le haut. Les démonstrations ne dépendent que de résultats énoncés et démontrés *plus haut* dans le texte. Vous n'avez pas à vous inquiéter de l'ordre logique de présentation de vos résultats : celui du Frido est bon.
* Il y a une uniformité des notations à travers toutes les matières.
* Tout est très explicite. Pas d'abus de notation, citation explicite de tous les résultats utilisés et énormément de détails dans les démonstrations.

#### En négatif

Le Frido se distingue également par certains aspects négatifs.

* Manque de relecture. Vous croyez que les livres commerciaux sont bien relus et sans erreurs ? Eh bien ce n'est pas le cas pour le Frido. Il n'est pas très relu (si vous trouvez des erreurs, contactez moi!!), et contient sûrement beaucoup d'erreurs. Un certain nombre sont d'ailleurs très clairement indiquées.
* Le fait que toutes les références soient faites vers le haut engendre de très lourdes contraintes dans le découpage des chapitres a priori, tout peut dépendre de tout. Il n'y a pas une partie anneaux/corps séparée de la partie algèbre linéaire, séparée de la partie analyse. Certains résultats ne se trouvent pas là où vous croyez qu'ils se trouvent.

### Est-ce je peux utiliser le Frido le jour de l'oral ?

Réponse : je ne sais pas. J'ai demandé au jury (que j'ai déjà relancé quelque fois) qui ne m'a pas répondu. Quelque éléments de réflexion :

* Plusieurs candidats l'ont déjà utilisé sans être inquiétés.
* Une version imprimée est [dans la bibliothèque de l'ENS Cachan](https://catalogue.ens-cachan.fr/cgi-bin/koha/opac-detail.pl?biblionumber=59258).
* Si vous croyez que 3 mois sans réponse équivaut à acceptation, alors le Frido est accepté.

Posez donc la question vous-même (ou mieux : faites la poser par un préparateur agreg de votre université) et transmettez moi la réponse.

## (almost) Everything I know in math

The document [(almost) Everything I know in mathematics](http://student.ulb.ac.be/%7Elclaesse/mazhe.pdf) contains almost everything I know in mathematics. It includes
* A part (in French) about general mathematics at master level (le Frido)
* A part (in French) containing the exercises and many corrections of the courses I gave at university.
* Higher level mathematics including research stuff -- my PhD thesis is here (in English) 

### General differential geometry

* Fibre bundles : vector, principal and associated bundles. 
* Connexions on fibre bundle, covariant derivative.

### Lie groups, Lie algebra
* Lie groups and Lie algebra.
* Homogeneous and symmetric spaces.
* Root spaces, Iwasawa decomposition. 
* Cyclic modules and representations.

### Quantum field theory
Very few physics. The aim is to understand why are we using groups, representations and principal bundle in quantum field theory.

* Link between fibre bundle and quantum field theory : why are particles irreducible representations of the Poincaré group ?
* Particles are modeled by sections of associated bundle : product of one representation of the Poincaré group and one representation of the gauge group. The interaction is given by a connexion on that bundle (with values in the Lie algebra of the gauge group).
* Clifford module and Dirac operator.
* Yang-Mills action.

### Non commutative geometry
* Compact quantum group.
* General non commutative geometry.
* WKB Deformation and quantization theory. Deformation of a manifold by action of a "deformable" group.

### Black hole in anti-de Sitter space
This is the argument of my PhD thesis.

* Black hole in anti-de Sitter space. The singular part is defined as the closed orbits of the Iwasawa subgroup of SO(2,l-1) acting on the l-dimensional anti-de Sitter space. 
* Dirac operator on the anti-de Sitter space.
* Deformation of the anti-de Sitter space.

### Other
* Symplectic geometry, Hamiltonian action.
* Bialgebra and Hopf algebra.
* Oscillatory integral.
* von Neumann algebra.

## Annexe : liste de choses que l'on peut trouver dans le Frido

### Algèbre et géométrie

* Endomorphismes cycliques et commutant dans le cas diagonalisable.
* Isométries du cube.
* Racine carré d'une matrice hermitienne positive.
* Action du groupe modulaire sur le demi-plan de Poincaré.
* Algorithme des facteurs invariants.
* Méthode du gradient à pas optimal.
* Extrema liés.
* Enveloppe convexe du groupe orthogonal.
* Une forme canonique pour les transvections et dilatations.
* Résolution diophantienne de $ax+by=c$ en utilisant Bézout.
* Résolution de l'équation diophantienne $x^2+2=y^3$ en parlant de l'extension $Z[i\sqrt{2}]$ et de stathme.
* Le dénombrement des solutions de l'équation diophantienne $\alpha_1 n_1+\ldots \alpha_pn_p=n$ utilise des séries entières et des décomposition de fractions en éléments simples.
* Triplets pythagoriciens.
* Polynômes semi-symétriques.
* Lemme de Morse.
* Générateurs du groupe diédral.
* Table des caractères du groupe diédral.
* Sous-groupes compacts de $GL(n,R)$.
* Théorème de Wedderburn.
* Suites de décomposition et théorème de Jordan-Hölder.
* Le groupe alterné est simple.
* Théorème de Lie-Kolchin.
* RSA, plus l'exponentielle rapide, plus la recherche de couples de Bézout.
* Théorème de Sylow.
* Coloriage de roulette et composition de colliers.
* Théorème de Burnside sur les sous groupes d'exposant fini de $GL(n,C)$.
* $(Z/pZ)^* = Z/(p-1)Z$
* Forme alternées de degré maximum.
* Décomposition de Bruhat.
* Table des caractères du groupe symétrique $S_4$
* Décomposition polaire d'un endomorphisme.
* Théorème de Von Neumann.
* Forme faible du théorème de Dirichlet.
* Irréductibilité des polynômes cyclotomiques, proposition.
* Structure des groupes d'ordre $pq$
* Divergence de la somme des inverses des nombres premiers.
* Théorème des deux carrés.
* Théorème de Chevalley-Warning.
* Loi de réciprocité quadratique.
* Polynômes irréductibles sur $F_q$
* Nombres de Bell, théorème.
* Partitions d'un entier en parts fixes, proposition.
* Théorème de Rothstein-Trager sur l'intégration de fraction rationelles.
* Théorème de la dimension.
* Théorème de Carathéodory.
* Diagonalisation de matrices symétriques.
* Stabilité du rang par extension des scalaires.
* Ellipsoïde de John-Loewner, proposition.
* Décomposition de Dunford.
* Équation de Hill $y''+qy=0$.
* Connexité des formes quadratiques de signature donnée.
* Points extrémaux de la boule unité dans $End(E)$.
* Théorème de Kronecker.
* Polynômes séparables.
* Lien entre les racines (multiples) de $P$ et $ P'$ .
* Théorème de l'élément primitif.
* À propos d'extensions de $Q$.
* Polygones réguliers constructibles, théorème de Gauss-Wantzel.

### Analyse

* Le dénombrement des solutions de l'équation $ \alpha_1 n_1+\ldots \alpha_pn_p=n$ utilise des séries entières et des décomposition de fractions en éléments simples.
* Méthode de Newton.
* Formule sommatoire de Poisson.
* Inégalité isopérimétrique.
* Équation de Hill $ y''+qy=0$.
* Théorème de stabilité de Lyapunov.
* Le système proie prédateurs, Lokta-Voltera.
* Méthode du gradient à pas optimal.
* Équation de Schrödinger.
* L'équation  $ (x-x_0)^{\alpha}u=0 $ pour $u$ dans les distributions tempérées.
* Espace de Sobolev $ H^1(I)$.
* Un résultat sur $ y''+qy=0 $ à partir d'une hypothèse de croissance.
* L'inégalité de Jensen.
* Théorème de Cauchy-Lipschitz.
* Dual de $ L^p[ 0 , 1 ] \big) $ pour $ p $ strictement entre $ 1$ et $ 2$.
* Prolongement de fonction définie sur une partie dense.
* Complétion d'un espace métrique.
* Critère de Weyl.
* Densité des polynômes dans $C^0[ 0 , 1 ]$, théorème de Bernstein.
* Suite telle que $\lim_{k\to \infty} d(u_{k+1},u_k)=0$.
* Théorème de Montel.
* Théorème de Runge.
* Théorème de Brouwer en dimension $ 2$ via l'homotopie.
* Théorème de Lie-Kolchin.
* La notion de classes dans $L^p$.
* Théorème de Fischer-Riesz.
* Processus de Galton-Watson.
* Théorème d'inversion locale.
* Théorème de Picard et l'inséparable théorème de Cauchy-Lipschitz.
* Prolongement méromorphe de la fonction $\Gamma$ d'Euler.
* Théorème de Tietze.
* Extrema liés.
* Les théorèmes sur les fonctions définies par des intégrales.
* Lemme de Borel.
* Divergence de la somme des inverses des nombres premiers.
* Théorème taubérien de Hardy-Littlewood.
* Théorème d'Abel angulaire.
* Le théorème de Weierstrass sur la limite uniforme de fonctions holomorphes.
* Problème de la ruine du joueur.
* Calcul d'intégrale par suite équirépartie.
* Fonction caractéristique.
* Théorème central limite.
* Fonction continue et périodique dont la série de Fourier ne converge pas.
* Estimation des grands écarts.
* Théorème de Banach-Steinhaus.

