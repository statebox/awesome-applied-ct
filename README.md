# Awesome Applied Category Theory

A curated list of Applied Category Theory resources.

## Table of contents

- [Awesome ACT](#awesome-act)
    - [Articles](#articles)
        - [Databases](#databases)
        - [Data types](#data-types)
        - [Dynamical systems](#dynamical-systems)
        - [Game theory](#game-theory)
        - [Machine learning](#machine-learning)
        - [Petri nets](#petri-nets)
    - [Books](#books)
    - [Companies](#companies)
        - [Heavily using ACT](#heavily-using-act)
        - [Interested in ACT research](#interested-in-act-research)
    - [Conferences](#conferences)
    - [Journals](#journals)
    - [Lectures](#lectures)
    - [Meetups](#meetups)
    - [Software libraries](#software-libraries)
    - [Tools](#tools)

### Articles
*Relevant articles applying category theory to various fields.*

#### Databases

* [Algebraic databases](http://www.tac.mta.ca/tac/volumes/32/16/32-16abs.html) - by [Patrick Schultz][schultz], [David I. Spivak][spivak], [Christina Vasilakopoulou][vasilakopoulou] and [Ryan Wisnesky][wisnesky]
* [Algebraic Model Management: A survey](https://www.categoricaldata.net/cql/wadt.pdf) - by [Patrick Schultz][schultz], [David I. Spivak][spivak], and [Ryan Wisnesky][wisnesky]
* [Functorial data migration](https://www.sciencedirect.com/science/article/pii/S0890540112001010) - by [David I. Spivak][spivak]

#### Data types

* [Categories of Containers](https://www.cs.nott.ac.uk/~psztxa/publ/fossacs03.pdf) - by [Michael Abbot][abbot], [Thorsten Altenkirch][altenkirch] and [Neil Ghani][ghani]

#### Dynamical systems

* [A categorical approach to open and interconnected dynamical systems](https://arxiv.org/abs/1510.05076) - by [Brendan Fong][fong], [Paolo Rapisarda][rapisarda] and [Paweł Sobociński][sobocinski]

#### Game theory

* [A semantical approach to equilibria and rationality](https://arxiv.org/abs/0905.3548) - by [Dusko Pavlovic][pavlovic]
* [Compositional game theory](https://arxiv.org/abs/1603.04641) - by [Jules Hedges][hedges], [Neil Ghani][ghani], [Viktor Winschel][winschel] and [Philipp Zahn][zahn]
* [The game semantics of game theory](https://arxiv.org/abs/1904.11287) - by [Jules Hedges][hedges]

#### Linguistics

* [Free compact 2-categories](https://hal-lirmm.ccsd.cnrs.fr/lirmm-00137681v2/document) - by Joachim Lambek and Anne Preller
* [Mathematical foundations for a compositional distributional model of meaning](https://arxiv.org/abs/1003.4394) - by [Bob Coecke][coecke], [Mehrnoosh Sadrzadeh][sadrzadeh] and [Stephen Clark][clark]
* [The Frobenius anatomy of word meanings I: subject and object relative pronouns](https://arxiv.org/abs/1404.5278) - by [Mehrnoosh Sadrzadeh][sadrzadeh], [Stephen Clark][clark] and [Bob Coecke][coecke]

#### Machine learning

* [Backprop as Functor: A compositional perspective on supervised learning](https://arxiv.org/abs/1711.10455) - by [Brendan Fong][fong], [David I. Spivak][spivak] and [Rémy Tuyéras][tuyeras]
* [Compositional Deep Learning](https://arxiv.org/abs/1907.08292) - by [Bruno Gavranović][gavranovic]

#### Manufacturing

* [String diagrams for assembly planning](https://arxiv.org/abs/1909.10475) - by [Jade Master][master], [Evan Patterson][patterson], Shahin Yousfi, Arquimedes Canedo

#### Petri nets

* [Generalized Petri Nets](https://arxiv.org/abs/1904.09091) - by [Jade Master][master]
* [The Mathematical Specification of the Statebox Language](https://arxiv.org/abs/1906.07629) - by [Fabrizio Genovese][genovese] and [Jelle Herold][herold]

#### Probability and statistics

* [A categorical approach to probability theory](https://www.chrisstucchio.com/blog_media/2016/probability_the_monad/categorical_probability_giry.pdf) - by Michèle Giry
* [Causal inference by string diagram surgery](https://arxiv.org/abs/1811.08338) - by [Bart Jacobs][jacobs], [Aleks Kissinger][kissinger] and [Fabio Zanasi][zanasi]
* [A synthetic approach to Markov kernels, conditional independence and theorems on sufficient statistics](https://arxiv.org/abs/1908.07021) - by [Tobias Fritz][fritz]

### Books
*Books on applied category theory.*

* [Category Theory for Programmers](https://github.com/hmemcpy/milewski-ctfp-pdf) - by [Bartosz Milewski][milewski]
* [Category Theory for the Sciences](https://mitpress.mit.edu/books/category-theory-sciences) - by [David I. Spivak][spivak]
* [Seven Sketches in Compositionality: An Invitation to Applied Category Theory](https://arxiv.org/abs/1803.05316) - by [Brendan Fong][fong] and [David I. Spivak][spivak] (note also the [corresponding lecture series](#lectures)).
* [What is Applied Category Theory](https://arxiv.org/abs/1809.05923) - by [Tai-Danae Bradley][bradley]

### Companies
*Companies applying category theory.*

#### Heavily using ACT

* [Conexus](https://conexus.com/) - A start-up developing [CQL](https://www.categoricaldata.net/), a generalization of SQL to data migration and integration that contains an automated theorem prover to rule out most semantic errors at compile time.
* [Statebox](https://statebox.org/) - building a formally verified process language using robust mathematical principles to prevent errors, allow compositionality and ensure termination

#### Interested in ACT research

* [IOHK](https://iohk.io/) - builds cryptocurrencies and blockchain solutions, based on peer reviewed papers; formally verified specifications in [Agda](https://github.com/input-output-hk/plutus/tree/master/metatheory), [Coq](https://github.com/input-output-hk?language=coq) and [k-framework](https://testnet.iohkdev.io/iele/about/formal-verification/)
* [RChain](https://github.com/rchain/) - blockchain ecosystem it's foundational language - Rholang is implementation of [rho-calculus](http://rho.loria.fr/index.html) wih deep roots in [higher category theory](https://arxiv.org/abs/1504.04311) and [enriched Lawvere theories](https://arxiv.org/abs/1704.03080)

### Conferences

* [ACT](http://www.appliedcategorytheory.org/) - Applied Category Theory Conference
* [Statebox Summit](https://summit.statebox.org/) - An yearly gathering of category theorists and functional programmers
* [SYCO](http://events.cs.bham.ac.uk/syco) - Symposium on Compositional Structures

### Journals
*Academic journals on applied category theory.*

* [Compositionality](http://www.compositionality-journal.org/) - open-access journal for research using compositional ideas, most notably of a category-theoretic origin, in any discipline

### Lectures
*Video recordings of lecture series on applied category theory.*

* [Applied Category Theory @ MIT 2019](https://www.youtube.com/playlist?list=PLhgq-BqyZ7i5lOqOqqRiS0U5SwTmPpHQ5), series of lectures based on the "Seven Sketches" book - by [Brendan Fong][fong] and [David I. Spivak][spivak]

### Meetups
* [Boston](https://www.meetup.com/Categorical-Databases/)
* [Munich](https://www.meetup.com/Applied-Category-Theory-Munich/)
* [New York](https://www.meetup.com/NYC-Category-Theory/)
* [San Francisco Bay Area](https://www.meetup.com/Category-Theory)

### Software libraries
*Libraries to actually encode category theory in software.*

* [copumpkin/categories](https://github.com/copumpkin/categories) - categories parametrized by morphism equality, in [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php)
* [idris-ct](https://github.com/statebox/idris-ct) - a formally verified category theory library written in [Idris](https://www.idris-lang.org/)
* [UniMath](https://github.com/UniMath/UniMath/tree/master/UniMath/CategoryTheory) - categories formalized using univalent mathematics, in [Coq](https://coq.inria.fr/)

### Tools
*Useful tools for applied category theory.*

* [Cartographer.id](http://cartographer.id/) - a tool for string diagrammatic reasoning
* [Catlab.jl](https://github.com/epatters/Catlab.jl) - an experimental framework for applied category theory
* [Homotopy.io](https://homotopy.io/) - a web-based proof assistant for finitely-presented globular n-categories
* [KdMonCat](https://edit.statebox.cloud/) - a tool for drawing morphisms in monoidal categories

[abbot]: https://www.cs.le.ac.uk/people/mabbott/
[altenkirch]: http://www.cs.nott.ac.uk/~psztxa/
[bradley]: https://www.math3ma.com/
[clark]: https://sites.google.com/site/stephenclark609/
[coecke]: https://www.cs.ox.ac.uk/people/bob.coecke/
[fong]: http://brendanfong.com/
[fritz]: https://perimeterinstitute.ca/personal/tfritz/
[gavranovic]: https://www.brunogavranovic.com/
[genovese]: https://twitter.com/fabgenovese
[ghani]: https://www.strath.ac.uk/staff/ghanineilprof/
[hedges]: https://julesh.com/
[herold]: http://shell.defekt.nl/~jelle/#/p/about/
[jacobs]: https://www.cs.ru.nl/B.Jacobs/
[kissinger]: https://www.cs.ru.nl/A.Kissinger/papers.html
[master]: https://sites.google.com/view/jadeedenstarmaster/home
[milewski]: https://bartoszmilewski.com/
[patterson]: https://www.epatters.org/
[pavlovic]: http://dusko.org/
[rapisarda]: https://www.ecs.soton.ac.uk/people/pr3
[sadrzadeh]: https://msadrzadeh.com/
[schultz]: https://www.linkedin.com/in/patrick-schultz-16645590/
[sobocinski]: https://www.ioc.ee/~pawel/
[spivak]: https://math.mit.edu/~dspivak/
[tuyeras]: http://www.normalesup.org/~tuyeras/
[vasilakopoulou]: https://mathdept.ucr.edu/faculty/cvasil.html
[winschel]: http://www.vikwin.de/
[wisnesky]: https://www.wisnesky.net/
[zahn]: https://www.philipp-zahn.com/
[zanasi]: http://www.zanasi.com/fabio/
