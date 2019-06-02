<!-- .slide: data-background-image="img/portier2.png" -->
<!-- .slide: class="hover"-->

## Visualizing brouhaha: <br> an (attempt of) analysis of French contemporary literature<br>(and how to learn from failure)

Servanne Monjour

_Congress 2019_

<!-- .element: style="font-size:1.4rem" -->

![CC-BY-SA](http://i.creativecommons.org/l/by-sa/4.0/88x31.png) <!-- .element: class="logo" -->

====

Even if "Visualizing brouhaha" is the title of my presentation, I will not show many visualizations today. I'm rather going to present how I struggled to produce visualizations of a quite challenging corpus, that come under what we may call a "brouhaha literature". "Brouhaha literature" is a recent concept, proposed by the french theoritecian Lionel Ruffel in 2016, and that is currently very successful in French literary studies.

I will explain and illustrate in details the concept later, but quickly, let say that brouhaha-literature refers to somes new kinds of heterogeneous corpora, composed of very disseminated sources on and outside the web. Thoses sources can be textual, visual, sound, performance, etc.

Although relevant, and refering to a very large part of contemporary writing and artistic practices, this concept of "brouhaha literature" can be very challenging for computational literary analysis, since the tidy notion of a work to be analyzed is replaced by a never-ending sequence of questions about what belongs and how to apprehend it.

In fact, "visualizing Brouhaha" may appear like an nonsense: the principle of this literature is to be chaotic, etc. My question, to fill the metaphor, was: can we see some patterns in this brouhaha? Is it just noisy, is it just a cacophony, or can we identify some echos, or even maybe a choral organization?

It was a nice challenge, and I want to thank Stefan Sinclair for his help on this crazy project, that partially failed, but partially only, because as we know, one of the main interest of vizualisation is the hermeneutic process involved in our research and methodology, that can reveal the complexity of our objects or study case.


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/generalinstinVitrail.jpg" -->


## The "Général [H]instin" project

===

My study case is the *Général [H]instin* collective, an interdisciplinary and artistic group created in the 1990's, involving more than 200 contributors from many areas: the collective is composed by novelists, poets, performers, visual artists, etc.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/instinss.jpg" -->

### Once upon a time, there was a general: from Hinstin to Instin

source image: _Quand on écrira l’histoire secrète du vingt et unième siècle…_ sur remue.net  

<!-- .element: class="source" -->

===

Adophe Hinstin was a French general who lived during the nineteenth century, died in 1905, and was buried in Paris, at the Cimetière du Montparnasse.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

source image: _introduction au feuilleton collectif Général Instin_ sur remue.net

<!-- .element: class="source" -->

===

In the vault of the Hinstin family, we can find this portrait of Adolphe, printed on a stained-glass window. Due to the printing technique, the portrait is slowly dissolving, giving to the figure of the general this spectral appearance.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

source image: _introduction au feuilleton collectif Général Instin_ sur remue.net

<!-- .element: class="source" -->

===

In 1997, while he was taking a walk into the Cimetière du Montparnasse in Paris, the french writer Patrick Chatelier discovered the vault of the Hinstin family.

On his demand, the photographer Juliette Soubrier took some pictures of the vault and its decomposed portrait.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

source image: _introduction au feuilleton collectif Général Instin_ sur remue.net

<!-- .element: class="source" -->

===

The same year, Patrick Chatelier uses the picture for co-creation experiment by a group of artists at the "Squat de la Grange-aux-Belles" -a major place of French counter-culture during the 90's:

>J’ai montré les photos, j’ai un peu personnifié le général et je me suis aperçu que les artistes présents s’en emparaient pour en faire leur propre chose. C’est là que c’est devenu collectif. (Chatelier, 2015, Libération)

>(I showed the pictures, I personified the general, and I realized that the artists were absorbing it, transforming it into their own thing. Then it became a collective project.)


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/revueGeste.png" data-background-size="contain"-->

source image: revue-geste.fr  <!-- .element: class="source" -->

===
Cette photo du Général va inspirer les artistes présents, et marquer le début d'un collectif relativement informel (bien que très pro-actif), qui donnera lieu à quelques publications papier - et à différents atelier littéraires (+/- formels là aussi).

Entre temps, Hinstin a perdu son "H" qui le faisait personnage historique, pour devenir un matériau narratif, platisque, sémiotique. Il devient ainsi Général Instin svt abrégé GI.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/item-026.png" data-background-size="contain" -->

source image: remue.net

<!-- .element: class="source" -->
===
Rapidement, GI insvestit la plateforme Remue.net, qui va jouer un rôle d'agrégateur / centralisateur des productions consacrées à Instin : poèmes, récits, beaucoup d'images, des vidéos et enregistrements (car bcp de lectures et d'ateliers commencent à être archivés).

Désormais, GI a pris racine dans l'hypertexte, et commence à hanter le web.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/item-036.png" data-background-size="contain" -->

source image: generalinstin.net  <!-- .element: class="source" -->

===
Ainsi, il se permet des incursions sur d'autres plateformes, à travers certaines expériences qui gagnent leur autonomie - nous avons nommés "Spin-off" ces expériences.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

<!-- .slide: data-background-image="img/toutesLesImages.png" -->

===
Les productions reliées au GI contiennent un aspect intermédial très fort, avec une production iconographique importante et foisonnante.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/Hinstin-famille.jpg" -->

source image: BNF  <!-- .element: class="source" -->

===
Au cours des années 2000, Retour de bâton : le collectif redécouvre que la famille Hinstin (avec son H), a en fait partie liée depuis longtemps avec la littérature et les arts - présent chez Jarry, Kessel.

La BNF dispose même d'un fonds d'archive photo de la famille (qui d'ailleurs est bien connue des spécialistes de Lautréamont). Comme quoi l'Histoire et l'histoire ne sont finalement pas si cloisonnées.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/instinPapier.png" -->

===
Enfin, depuis l'an dernier, Instin est devenu une figure auctoriale à part entière. Pour fêter cela, il a réinvesti le modèle éditorial imprimé, aux Éditions du Nouvel Attila, qui lui a même dédié une collection à lui seul : la collection Othello. Trois ouvrages ont été déjà publiés.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/corpusFantome.png" -->

source image: _lexique généraliste_ sur remue.net

<!-- .element: class="source" -->

===
Instin est donc un corpus fantôme.
La métaphore peut sembler facile pour parler d'une figure elle-même spectrale, mais elle revendiquée par le collectif.
[CITER]
Nous tenons tout particulièrement à cette expression qui évoque l'un de nos principaux défis : par sa nature processuelle, une partie de notre corpus semble toujours un peu sur le point de se dérober, voire sur le point de disparaître. En même temps, ce corpus est vivant et continue de se construire en même temps que nous l'étudions.

Instin est un fantôme, performé par le récit sans cesse réitéré de sa disparition, qui lui donne finalement un supplément d'existence.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

## "Brouhaha literature": a concept for a literature "out of the book"


===


In 2015, the French theoretician Lionel Ruffel proposed the concept of "littérature brouhaha" (a brouhaha-literature) to qualify this new condition of literature, characterized by its dissemination in multiple public spaces, and by a strong heterogeneity: the "brouhaha" first refers to multiple forms of literature emerging out of the printed text -performances, video, photography, social media, websites, etc.

Not ELO either: some very "old" forms, return  of orality, of performance.

The digital is used to archive and disseminate the corpus.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§
<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

### Publication as "make public"

===

More and more writers and artists occupy the web and all its publishing platforms, contemporary French literature is experiencing an important epistemological shift with the passage from a conception of literature based on the book (an object and a support for literary contents) to a conception of literature based on an action: publication that, in this way, goes back to its first meaning, "to make public".

The fact that the project began at the Squat de la Grange-aux-Belles, an alternative place based on group decision-making, is very significant, and illustrates one of the fondamental aspect of the brouhaha-literature, which places itself into the margins of traditional literary institutions and their hierarchy. As defined by Lionel Ruffel, brouhaha-literature aims to occupy public space, and deploy itself "out of the book", resisting to the printed model.

The web as a new squat?


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

### co-authorship

Also, brouhaha refers to a principle of co-authorship, in a context where the digital culture seems to (partially) decrease the modern status of the author -as described by Foucault- and reassert the worth of co-creation experiences and collaborative writing (just as early electronic literature and early web literature used to do).

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

## Building the corpus Instin (where the problems begin)

===

Just a "small" part of the corpus, on the web.

Web scraping

very different kind of text, problem of granularity.

Co-authorship, very different kind of contributors.

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

<!-- .slide: data-background-image="img/vitrailOriginal.jpg" data-background-size="contain"-->

### Dissemination and heterogeneity: a "gohst corpus"

===

Disappearing at the moment you have the impression to grasp it.

* Intermédiality
* Loss
* transformations
* Ongoing

§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### "jambon laissé": GI, un "canon"?

===


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

<!-- .slide: data-background-image="img/iLoveInstin.jpg" data-background-size="contain" -->

## Vizualising (eventually)

===
visualiser l'intermédialité ?

Métadiscours : histin qui réapparait = constitution et réitération du métadiscours


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§

### Postproduction: voices from teh past and from the present

===


§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§§<!-- .slide: data-background-image="img/iLoveInstin.jpg" data-background-size="contain" -->

### Archive 3.0



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/iLoveInstin.jpg" data-background-size="contain" -->

## Conclusion:
* "ceci tuera cela"?
* "brouhaha" and voices

===

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
<!-- .slide: data-background-image="img/iLoveInstin.jpg" data-background-size="contain" -->



### Thanks!



![CC-BY-SA](http://i.creativecommons.org/l/by-sa/4.0/88x31.png) <!-- .element: class="logo" -->
