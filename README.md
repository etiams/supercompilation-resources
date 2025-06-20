# `supercompilation-resources`

_Supercompilation_ is an principiled program transformation technique that symbolically evaluates a given input program into its more efficient version, eliminating as much of computational overhead as possible. From a given program it builds a _process graph_ of dynamically encountered _configurations_ (expressions with unknown variables), converts loops into special edges between the configurations, & finally _residualizes_ the process graph into a structurally simpler output program in the same or different language. Furthermore, with suitable extensions it can achieve _asymptotic speedups_ for some functional algorithms.

This is a collection of resources for studying supercompilation & its applications, ranging from introductory materials to advanced papers. Any questions regarding supercompilation will be welcomed in the issues.

## Projects

 - [SPSC](https://github.com/sergei-romanenko/spsc) -- A Small Positive Supercompiler in Scala, Haskell, Python, Ruby, JavaScript & Idris.
 - [HOSC](https://github.com/ilya-klyuchnikov/hosc) -- A higher-order call-by-name supercompiler for a subset of Haskell.
 - [JSCP](http://supercompilers.org/) -- A supercompiler for the Java programming language.
 - [MRSC](https://github.com/ilya-klyuchnikov/mrsc) -- A toolkit for rapid design and prototyping of (multi-result) supercompilers.
 - [TT-Lite](https://github.com/ilya-klyuchnikov/ttlite) -- A supercompiler for a version of Martin-Löf’s Type Theory (MLTT).
 - [sc-mini](https://github.com/ilya-klyuchnikov/sc-mini) -- A minimal positive supercompiler written in Haskell.
 - [erlscp](https://github.com/fenollp/erlscp) -- A supercompiler pass for the Erlang programming language.
 - [agda-simple-scp](https://github.com/sergei-romanenko/agda-simple-scp) -- A simple supercompiler formally verified in Agda.
 - [Mazeppa](https://github.com/mazeppa-dev/mazeppa) -- A modern supercompiler for call-by-value functional languages.
 - [Distiller](https://github.com/poitin/Distiller) -- The implementation of the distillation algorithm.

## Videos

 - [Nate Nystrom -- A Scala Framework for Supercompilation | Scala Symposium 2017](https://www.youtube.com/watch?v=GPmSs8msu7U)

## Papers

### 1986

 - Turchin, Valentin F. "The concept of a supercompiler." ACM Transactions on Programming Languages and Systems (TOPLAS) 8.3 (1986): 292-325. $${\textbf{\color{orange}must read}}$$ $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](https://stanleymiracle.github.io/blogs/org/docs/supercompiler.pdf), [webarchive](http://web.archive.org/web/20250620135501/https://stanleymiracle.github.io/blogs/org/docs/supercompiler.pdf)

### 1993

 - Glück, Robert, and Andrei V. Klimov. "Occam's razor in metacomputation: the notion of a perfect process tree." International Workshop on Static Analysis. Berlin, Heidelberg: Springer Berlin Heidelberg, 1993. $${\textbf{\color{orange}must read}}$$
   <br>[URL](https://pat.keldysh.ru/~anklimov/papers/1993.Occam's.Razor.in.Metacompuation.pdf), [webarchive](http://web.archive.org/web/20240712101420/https://pat.keldysh.ru/~anklimov/papers/1993.Occam's.Razor.in.Metacompuation.pdf)
 - Turchin, Valentin F. "Program transformation with metasystem transitions." Journal of Functional Programming 3.3 (1993): 283-313. $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/F0D67B654FB2C053A961551C357B92E9/S0956796800000757a.pdf/program-transformation-with-metasystem-transitions.pdf), [webarchive](http://web.archive.org/web/20221208214353/https://www.cambridge.org/core/services/aop-cambridge-core/content/view/F0D67B654FB2C053A961551C357B92E9/S0956796800000757a.pdf/program-transformation-with-metasystem-transitions.pdf)

### 1995

 - Turchin, V., and A. Nemytykh. Metavariables: Their implementation and use in Program Transformation. CCNY Technical Report CSc TR-95-012, 1995. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](http://refal.botik.ru/library/Turchin-Nemytykh-Metavariables_their_Implementation_and_Use_in_Program_Transformation_(City%20College%20of%20the%20City%20University%20of%20New%20York__N_TR%2095-012__1995).pdf), [webarchive](http://web.archive.org/web/20250513184017/http://refal.botik.ru/library/Turchin-Nemytykh-Metavariables_their_Implementation_and_Use_in_Program_Transformation_(City%20College%20of%20the%20City%20University%20of%20New%20York__N_TR%2095-012__1995).pdf)
 - Sørensen, Morten Heine, and Robert Glück. "An Algorithm of Generalization in Positive Supercompilation." ILPS. Vol. 95. 1995. $${\textbf{\color{gold}popular}}$$
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=8d2fe193679b1e3c014c457b294ebd33a2735936), [webarchive](http://web.archive.org/web/20250620141326/https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=8d2fe193679b1e3c014c457b294ebd33a2735936)

### 1996

 - Soerensen, Morten Heine, Robert Glück, and Neil D. Jones. "A positive supercompiler." Journal of functional programming 6.6 (1996): 811-838. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{gold}popular}}$$
   <br>[URL](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/4EEE2EBC972AA2FDC861EF7A713EE898/S0956796800002008a.pdf/a-positive-supercompiler.pdf), [webarchive](http://web.archive.org/web/20240415050443/https://www.cambridge.org/core/services/aop-cambridge-core/content/view/4EEE2EBC972AA2FDC861EF7A713EE898/S0956796800002008a.pdf/a-positive-supercompiler.pdf)
 - Glück, Robert, and Morten Heine Sørensen. "A roadmap to metacomputation by supercompilation." Partial Evaluation: International Seminar Dagstuhl Castle, Germany, February 12–16, 1996 Selected Papers. Springer Berlin Heidelberg, 1996. $${\textbf{\color{lightgreen}introductory}}$$ $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=ea7ff9b5825e8fabdac356b2ed20e904bca77ab6), [webarchive](http://web.archive.org/web/20240418034034/https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=ea7ff9b5825e8fabdac356b2ed20e904bca77ab6)
 - Turchin, Valentin F. "Metacomputation: MST plus SCP." Proc. of the Dagstuhl Seminar on Partial Evaluation, Springer-Verlag. 1996. $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](http://refal.botik.ru/library/Turchin-Metacomputation_Metasystem_transitions_plus_supercompilation_(LNCS_vol_1110,_1996,_pp_481-509).pdf), [webarchive]()
 - Nemytykh, Andrei P., Victoria A. Pinchuk, and Valentin F. Turchin. "A self-applicable supercompiler." Partial Evaluation: International Seminar Dagstuhl Castle, Germany, February 12–16, 1996 Selected Papers. Springer Berlin Heidelberg, 1996. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=3265a0bdb78e62a2966c3332f1dba457aca6e0bd), [webarchive](http://web.archive.org/web/20241111081647/https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=3265a0bdb78e62a2966c3332f1dba457aca6e0bd)
 - Turchin, Valentin F. "Supercompilation: Techniques and results." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 1996. $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/3-540-62064-8_20), [webarchive](http://web.archive.org/web/20250620141641/https://link.springer.com/chapter/10.1007/3-540-62064-8_20)
 - Turchin, Valentin F. "On generalization of lists and strings in supercompilation." Technical Report CSc. TR 96-002 (1996). $${\textbf{\color{cyan}Refal}}$$
   <br>[URL](https://pat.keldysh.ru/~roman/refal/1996-Turchin--On_generalization_of_lists_and_strings_in_supercompilation.pdf), [webarchive](http://web.archive.org/web/20250620141644/https://pat.keldysh.ru/~roman/refal/1996-Turchin--On_generalization_of_lists_and_strings_in_supercompilation.pdf)

### 1998

 - Sørensen, Morten Heine B. "Convergence of program transformers in the metric space of trees." International Conference on Mathematics of Program Construction. Berlin, Heidelberg: Springer Berlin Heidelberg, 1998. $${\textbf{\color{orange}must read}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/BFb0054297), [webarchive](http://web.archive.org/web/20250620144324/https://link.springer.com/chapter/10.1007/BFb0054297)
 - Sørensen, Morten Heine B., and Robert Glück. "Introduction to supercompilation." DIKU International Summer School. Berlin, Heidelberg: Springer Berlin Heidelberg, 1998. 246-270. $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/3-540-47018-2_10), [webarchive](http://web.archive.org/web/20250620144254/https://link.springer.com/chapter/10.1007/3-540-47018-2_10)

### 1999

 - Secher, Jens Peter, and Morten Heine Sørensen. "On perfect supercompilation." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 1999.
   <br>[URL](https://www.academia.edu/125902576/On_Perfect_Supercompilation), [webarchive](http://web.archive.org/web/20250620143014/https://www.academia.edu/125902576/On_Perfect_Supercompilation)

### 2001

 - Secher, Jens Peter. "Driving in the jungle." Symposium on Program as Data Objects. Berlin, Heidelberg: Springer Berlin Heidelberg, 2001. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/3-540-44978-7_12), [webarchive](http://web.archive.org/web/20250620142515/https://link.springer.com/chapter/10.1007/3-540-44978-7_12)
 - Abramov, Sergei, and Robert Glück. "From standard to non-standard semantics by semantics modifiers." International Journal of Foundations of Computer Science 12.02 (2001): 171-211. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://www.researchgate.net/publication/220181098_FROM_STANDARD_TO_NON-STANDARD_SEMANTICS_BY_SEMANTICS_MODIFIERS), [webarchive](http://web.archive.org/web/20250620142522/https://www.researchgate.net/publication/220181098_FROM_STANDARD_TO_NON-STANDARD_SEMANTICS_BY_SEMANTICS_MODIFIERS)

### 2002

 - Korlyukov, A. V., and Andrei P. Nemytykh. "Supercompilation of Double Interpretation. (How One Hour of the Machine’s Time Can Be Turned to One Second)." 2002 $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](http://refal.net/~korlukov/scp2int/Karliukou_Nemytykh.pdf), [webarchive](http://web.archive.org/web/20250513183950/http://www.refal.net/~korlukov/scp2int/Karliukou_Nemytykh.pdf)

### 2008

 - Klimov, Andrei Valentinovich. "A program specialization relation based on supercompilation and its properties." Препринты Института прикладной математики им. МВ Келдыша РАН 0 (2008): 26-28.
   <br>[URL](http://meta2008.pereslavl.ru/accepted-papers/meta2008-KlimovA1.pdf), [webarchive](http://web.archive.org/web/20250620144501/http://meta2008.pereslavl.ru/accepted-papers/meta2008-KlimovA1.pdf)
 - Klimov, Andrei V. "An approach to supercompilation for object-oriented languages: the Java Supercompiler case study." Nemytykh [28] (2008): 43-53. $${\textbf{\color{lightblue}practical}}$$
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=26bd6bf43696b2070b79a07ba5bf7327b6d27d9e#page=43), [webarchive](http://web.archive.org/web/20250620143301/https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=26bd6bf43696b2070b79a07ba5bf7327b6d27d9e#page=43)
 - Lisitsa, Alexei, and Andrei P. Nemytykh. "Reachability analysis in verification via supercompilation." International Journal of Foundations of Computer Science 19.04 (2008): 953-969. $${\textbf{\color{lightblue}practical}}$$
   <br>[URL](http://skif.pereslavl.ru/psi-info/psi/psi-publications/2007-eng/rp07_lisitsa_nemytykh.pdf), [webarchive](http://web.archive.org/web/20250620143356/http://skif.pereslavl.ru/psi-info/psi/psi-publications/2007-eng/rp07_lisitsa_nemytykh.pdf)
 - Lisitsa, Alexei, and Matt Webster. "Supercompilation for equivalence testing in metamorphic computer viruses detection." Proceedings of the First International Workshop on Metacomputation in Russia. Vol. 226. 2008. $${\textbf{\color{lightblue}practical}}$$
   <br>[URL](https://matt-webster.com/pubs/meta2008.pdf), [webarchive](http://web.archive.org/web/20241008113133/https://matt-webster.com/pubs/meta2008.pdf)
 - Lisitsa, Alexei, and Andrei P. Nemytykh. "Extracting bugs from the failed proofs in verification via supercompilation." Tests and Proofs: Papers Presented at the Second International Conference TAP. No. 5. 2008. $${\textbf{\color{lightblue}practical}}$$
   <br>[URL](https://www.academia.edu/download/30942931/2008_05_Arbeitsberichte.pdf#page=57)

### 2009

 - Jonsson, Peter A., and Johan Nordlander. "Positive supercompilation for a higher order call-by-value language." ACM SIGPLAN Notices 44.1 (2009): 277-288. $${\textbf{\color{gold}popular}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/1594834.1480916)
 - Klyuchnikov, Ilya, and Sergei Romanenko. "Proving the equivalence of higher-order terms by means of supercompilation." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2009.
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=67d5073533eeb41380d278c61957288baaac0a90), [webarchive](http://web.archive.org/web/20250620143718/https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=67d5073533eeb41380d278c61957288baaac0a90)
 - Klyuchnikov, Ilya, and Sergei Romanenko. "SPSC: a simple supercompiler in Scala." PU 9 (2009): 5.
   <br>[URL](https://google-code-archive-downloads.storage.googleapis.com/v2/code.google.com/spsc/Klyuchnikov__Romanenko__SPSC_a_Simple_Supercompiler_in_Scala.pdf), [webarchive](http://web.archive.org/web/20250620143652/https://google-code-archive-downloads.storage.googleapis.com/v2/code.google.com/spsc/Klyuchnikov__Romanenko__SPSC_a_Simple_Supercompiler_in_Scala.pdf)
 - Reich, Jason S. Optimus Prime: A new tool for interactive transformation and supercompilation of functional programs. Diss. Masters dissertation, University of York, UK, 2009.
   <br>[URL](https://www.academia.edu/download/101185901/ReichMD2009.pdf)
 - Klimov, Andrei V. "A Java supercompiler and its application to verification of cache-coherence protocols." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2009. $${\textbf{\color{lightblue}practical}}$$
   <br>[URL](https://pat.keldysh.ru/~anklimov/papers/2009-Klimov--A_Java_Supercompiler_and_its_Application_to_Verification_of_Cache-Coherence_Protocols--slides.pdf)

### 2010

 - Bolingbroke, Maximilian, and Simon Peyton Jones. "Supercompilation by evaluation." Proceedings of the third ACM Haskell symposium on Haskell. 2010. $${\textbf{\color{gold}popular}}$$ $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/1863523.1863540)
 - Jonsson, Peter, and Johan Nordlander. "Strengthening supercompilation for call-by-value languages." International Valentin Turchin Memorial Workshop on Metacomputation in Russia: 01/07/2010-05/07/2010. Ailamazyan University of Pereslavl, 2010.
   <br>[URL](https://www.diva-portal.org/smash/get/diva2:1005200/FULLTEXT01.pdf), [webarchive](http://web.archive.org/web/20250620144753/https://www.diva-portal.org/smash/get/diva2:1005200/FULLTEXT01.pdf)
 - Klyuchnikov, Ilya, and Sergei Romanenko. "Towards higher-level supercompilation." Second International Workshop on Metacomputation in Russia. Vol. 2. No. 4.2. 2010.
   <br>[URL](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=dffa6ae2bc5ca62453930895d94c25a158136b84)
 - Klyuchnikov, Ilya Grigorievich. "Supercompiler HOSC 1.5: homeomorphic embedding and generalization in a higher-order setting." Keldysh Institute Preprints 62 (2010): 1-23.
   <br>[URL](https://pat.keldysh.ru/~ilya/preprints/HOSC15_en.pdf), [webarchive](http://web.archive.org/web/20250620144833/https://pat.keldysh.ru/~ilya/preprints/HOSC15_en.pdf)
 - Mitchell, Neil. "Rethinking supercompilation." ACM Sigplan Notices 45.9 (2010): 309-320. $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/1932681.1863588)
 - Klyuchnikov, Ilya Grigorievich. "Towards effective two-level supercompilation." Препринты Института прикладной математики им. МВ Келдыша РАН 0 (2010): 81-28.
   <br>[URL](https://www.keldysh.ru/papers/2010/source/prep2010_81_eng.pdf), [webarchive](http://web.archive.org/web/20240719160513/https://keldysh.ru/papers/2010/source/prep2010_81_eng.pdf)

### 2011

 - Hamilton, Geoff W., and Neil D. Jones. "Proving the correctness of unfold/fold program transformations using bisimulation." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2011.
   <br>[URL](https://researchrepository.ul.ie/articles/journal_contribution/Proving_the_correctness_of_unfold_fold_program_transformations_using_bisimulation/19855399/1/files/35271520.pdf)
 - Jonsson, Peter A., and Johan Nordlander. "Taming code explosion in supercompilation." Proceedings of the 20th ACM SIGPLAN workshop on Partial evaluation and program manipulation. 2011. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/1929501.1929507)
 - Jonsson, Peter A. Time-and size-efficient supercompilation. Diss. Luleå tekniska universitet, 2011.
   <br>[URL](https://www.diva-portal.org/smash/get/diva2:999818/FULLTEXT01.pdf), [webarchive](http://web.archive.org/web/20240626032316/https://www.diva-portal.org/smash/get/diva2:999818/FULLTEXT01.pdf)
 - Klyuchnikov, Ilya, and Sergei A. Romanenko. "Multi-result supercompilation as branching growth of the penultimate level in metasystem transitions." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2011.
   <br>[URL](https://pat.keldysh.ru/~roman/publications/2011-Klyuchnikov_Romanenko--Multi-Result_Supercompilation_as_Branching_Growth--preproceedings.pdf), [webarchive](http://web.archive.org/web/20250620145328/https://pat.keldysh.ru/~roman/publications/2011-Klyuchnikov_Romanenko--Multi-Result_Supercompilation_as_Branching_Growth--preproceedings.pdf)
 - Bolingbroke, Maximilian, and Simon Peyton Jones. "Improving supercompilation: tag-bags, rollback, speculation, normalisation, and generalisation." ICFP. (2011). $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://simon.peytonjones.org/assets/pdfs/design-space.pdf), [webarchive](http://web.archive.org/web/20221212192536/https://simon.peytonjones.org/assets/pdfs/design-space.pdf)

### 2012

 - Grechanik, Sergei A. "Overgraph representation for multi-result supercompilation." Proceedings of the Third International Valentin Turchin Workshop on Metacomputation. Pereslavl-Zalessky: Ailamazyan University of Pereslavl, 2012. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://pat.keldysh.ru/~grechanik/doc/overgraph.pdf), [webarchive](http://web.archive.org/web/20250208232848/https://pat.keldysh.ru/~grechanik/doc/overgraph.pdf)
 - Klyuchnikov, Ilya G., and Sergei A. Romanenko. "Formalizing and implementing multi-result supercompilation." Klimov and Romanenko [18] (2012): 142-164.
   <br>[URL](https://www.academia.edu/download/89551167/2012_Klyuchnikov_Romanenko__Formalizing_and_Implementing_Multi-Result_Supercompilation.pdf)
 - Klimov, Andrei V., Ilya G. Klyuchnikov, and Sergei A. Romanenko. "Automatic verification of counter systems via domain-specific multi-result supercompilation." Preprint 19 (2012): 2012-19.
   <br>[URL](https://pat.keldysh.ru/~roman/publications/2012-Klimov_Klyuchnikov_Romanenko--Automatic_Verification_of_Counter_Systems--meta2012.pdf), [webarchive](http://web.archive.org/web/20250620145737/https://pat.keldysh.ru/~roman/publications/2012-Klimov_Klyuchnikov_Romanenko--Automatic_Verification_of_Counter_Systems--meta2012.pdf)

### 2013

 - Hamilton, G. W. "On the Termination of Higher-Order Positive Supercompilation." Proc. of the First International Workshop on Verification and Program Transformation. 2013. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://easychair.org/publications/download/FJ), [webarchive](http://web.archive.org/web/20240816162329/https://easychair.org/publications/download/FJ)
 - Grechanik, Sergei Aleksandrovich. "Supercompilation by hypergraph transformation." Препринты Института прикладной математики им. МВ Келдыша РАН 0 (2013): 26-24. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://www.keldysh.ru/papers/2013/prep2013_26.pdf), [webarchive](http://web.archive.org/web/20250620145957/https://www.keldysh.ru/papers/2013/prep2013_26.pdf)
 - Bolingbroke, Maximilian C. Call-by-need supercompilation. No. UCAM-CL-TR-835. University of Cambridge, Computer Laboratory, 2013.
   <br>[URL](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/bolingbroke-thesis.pdf), [webarchive](http://web.archive.org/web/20240713223911/https://www.microsoft.com/en-us/research/wp-content/uploads/2016/11/bolingbroke-thesis.pdf)

### 2014

 - Klyuchnikov, Ilya, and Dimitur Krustev. "Supercompilation: Ideas and methods." The Monad. Reader Issue 23 (2014): 17. $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://themonadreader.wordpress.com/wp-content/uploads/2014/04/issue23.pdf#page=17), [webarchive](http://web.archive.org/web/20250608174431/https://themonadreader.wordpress.com/wp-content/uploads/2014/04/issue23.pdf#page=17)
 - Mogensen, Torben Ægidius. "Supercompilation for Datatypes." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2014. $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](https://link.springer.com/chapter/10.1007/978-3-662-46823-4_19), [webarchive](http://web.archive.org/web/20250620150249/https://link.springer.com/chapter/10.1007/978-3-662-46823-4_19)
 - Klyuchnikov, Ilya, and Sergei Romanenko. "Certifying supercompilation for Martin-Löf’s type theory." International Andrei Ershov Memorial Conference on Perspectives of System Informatics. Berlin, Heidelberg: Springer Berlin Heidelberg, 2014. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://pat.keldysh.ru/~ilya/ttlite-psi2014.pdf), [webarchive](http://web.archive.org/web/20250620150155/https://pat.keldysh.ru/~ilya/ttlite-psi2014.pdf)
 - Grechanik, Sergei, Ilya Klyuchnikov, and Sergei Romanenko. "Staged multi-result supercompilation: Filtering by transformation." Proceedings of the Fourth International Valentin Turchin Workshop on Metacomputation/ed. by A. Klimov, S. Romanenko.—Pereslavl-Zalessky, Russia: Pereslavl Zalessky: Publishing House” University of Pereslavl. 2014. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](http://skif.pereslavl.ru/psi-info/rcms/rcms-publications/2014-rus/multi-result.pdf), [webarchive](http://web.archive.org/web/20250620150205/http://skif.pereslavl.ru/psi-info/rcms/rcms-publications/2014-rus/multi-result.pdf)

### 2015

 - Klyuchnikov, Ilya G., and Sergei A. Romanenko. "Supercompilation for Martin-Lof’s type theory." Programming and Computer Software 41 (2015): 170-182.
   <br>[URL](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1134/S0361768815030068.pdf), [webarchive](http://web.archive.org/web/20250620150450/https://link.springer.com/article/10.1134/S0361768815030068)

### 2016

 - Glück, Robert, Andrei Klimov, and Antonina Nepeivoda. "Nonlinear Configurations for Superlinear Speedup by Supercompilation." Fifth International Valentin Turchin Workshop on Metacomputation. 2016. $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](http://meta2016.pereslavl.ru/papers/2016_Proceedings_of_the_Fifth_International_Valentin_Turchin_Workshop_on_Metacomputation.pdf#page=32), [webarchive](http://web.archive.org/web/20250511224105/http://meta2016.pereslavl.ru/papers/2016_Proceedings_of_the_Fifth_International_Valentin_Turchin_Workshop_on_Metacomputation.pdf#page=32)
 - Grechanik, Sergei. "Towards Unification of Supercompilation and Equality Saturation." Proceedings of the Fifth International Valentin Turchin Workshop on Metacomputation/ed. by A. Klimov, S. Romanenko.—Pereslavl-Zalessky, Russia: Pereslavl Zalessky: Publishing House” University of Pereslavl. 2016. $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](http://meta2016.pereslavl.ru/papers/2016_Proceedings_of_the_Fifth_International_Valentin_Turchin_Workshop_on_Metacomputation.pdf#page=52), [webarchive](http://web.archive.org/web/20250511224105/http://meta2016.pereslavl.ru/papers/2016_Proceedings_of_the_Fifth_International_Valentin_Turchin_Workshop_on_Metacomputation.pdf#page=52)

### 2017

 - Nystrom, Nathaniel. "A scala framework for supercompilation." Proceedings of the 8th ACM SIGPLAN International Symposium on Scala. 2017.
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/3136000.3136011)

### 2018

 - Климов, Андрей Валентинович, and Сергей Анатольевич Романенко. "Суперкомпиляция: основные принципы и базовые понятия." Препринты Института прикладной математики им. МВ Келдыша РАН 0 (2018): 111-36. $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://keldysh.ru/papers/2018/prep2018_111.pdf), [webarchive](http://web.archive.org/web/20250517201601/https://keldysh.ru/papers/2018/prep2018_111.pdf)
 - Романенко, Сергей Анатольевич. "Суперкомпиляция: гомеоморфное вложение, вызов по имени, частичные вычисления." Препринты ИПМ им. МВ Келдыша 209 (2018): 1-32. $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://www.keldysh.ru/papers/2018/prep2018_209.pdf), [webarchive](http://web.archive.org/web/20250517201601/https://keldysh.ru/papers/2018/prep2018_209.pdf)

### 2020

 - Krustev, Dimitur Nikolaev. "Optimizing Program Size Using Multi-result Supercompilation." arXiv preprint arXiv:2008.04669 (2020).
   <br>[URL](https://arxiv.org/pdf/2008.04669), [webarchive](http://web.archive.org/web/20250620150824/https://arxiv.org/pdf/2008.04669)

### 2022

 - Klimov, A. V. "Supercompilation and partial evaluation are still not widely used in practice. Why and what to do?." Scientific Services & Internet. Vol. 24. 2022.
   <br>[URL](https://keldysh.ru/abrau/2022/theses/38.pdf), [webarchive](http://web.archive.org/web/20250620150824/https://keldysh.ru/abrau/2022/theses/38.pdf)

### Homeomorphic embedding

 - Leuschel, Michael. "Homeomorphic embedding for online termination of symbolic methods." The essence of computation: complexity, analysis, transformation. Berlin, Heidelberg: Springer Berlin Heidelberg, 2002. 379-403. $${\textbf{\color{lightgreen}introductory}}$$
   <br>[URL](https://eprints.soton.ac.uk/257252/1/state-of-the-art.final.pdf), [webarchive](http://web.archive.org/web/20250620151040/https://eprints.soton.ac.uk/257252/1/state-of-the-art.final.pdf)
 - Nash-Williams, C. St JA. "On well-quasi-ordering finite trees." Mathematical Proceedings of the Cambridge Philosophical Society. Vol. 59. No. 4. Cambridge University Press, 1963.
   <br>[URL](https://www.cs.umd.edu/~gasarch/COURSES/752/S25/slides/nashwilliams.pdf), [webarchive](http://web.archive.org/web/20250620151113/https://www.cs.umd.edu/~gasarch/COURSES/752/S25/slides/nashwilliams.pdf)
 - Bolingbroke, Maximilian, Simon Peyton Jones, and Dimitrios Vytiniotis. "Termination combinators forever." Proceedings of the 4th ACM symposium on Haskell. 2011. $${\textbf{\color{violet}inspirational}}$$
   <br>[URL](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/termination-combinators.pdf), [webarchive](http://web.archive.org/web/20250620151017/https://www.microsoft.com/en-us/research/wp-content/uploads/2016/07/termination-combinators.pdf)

### Distillation

 - Hamilton, Geoffrey William, and Neil D. Jones. "Distillation with labelled transition systems." Proceedings of the ACM SIGPLAN 2012 workshop on Partial Evaluation and Program Manipulation. 2012. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://dl.acm.org/doi/pdf/10.1145/2103746.2103753)
 - Hamilton, Geoff. "The Next 700 Program Transformers." International Symposium on Logic-Based Program Synthesis and Transformation. Cham: Springer International Publishing, 2021. $${\textbf{\color{violet}inspirational}}$$ $${\textbf{\color{crimson}advanced}}$$
   <br>[URL](https://arxiv.org/pdf/2108.11347), [webarchive](http://web.archive.org/web/20241106133329/http://arxiv.org/pdf/2108.11347)
 - Hamilton, Geoff W. "Poítin: Distilling theorems from conjectures." Electronic Notes in Theoretical Computer Science 151.1 (2006): 143-160.
   <br>[URL](https://www.sciencedirect.com/science/article/pii/S1571066106001149/pdf?md5=bb8ac1e2a6b17d914adba1d719120941&pid=1-s2.0-S1571066106001149-main.pdf)
 - Hamilton, Geoff W., and M. H. Kabir. "Constructing programs from metasystem transition proofs." (2008).
   <br>[URL](http://www.botik.ru/~znamensk/sbornik/meta-2008/meta2008_submission_3.pdf), [webarchive](http://web.archive.org/web/20250620151638/http://www.botik.ru/~znamensk/sbornik/meta-2008/meta2008_submission_3.pdf)
 - Mendel-Gleason, Gavin E., and Geoff W. Hamilton. "Supercompilation and normalisation by evaluation." (2010).
   <br>[URL](http://meta2010.pereslavl.ru/accepted-papers/meta2010-Gavin-Mendel-Gleason-Geoff-Hamilton.pdf), [webarchive](http://web.archive.org/web/20250512144830/http://meta2010.pereslavl.ru/accepted-papers/meta2010-Gavin-Mendel-Gleason-Geoff-Hamilton.pdf)

## META workshops

 - [META 2008](http://meta2008.pereslavl.ru/), [META 2010](http://meta2010.pereslavl.ru/), [META 2012](http://meta2012.pereslavl.ru/), [META 2014](http://meta2014.pereslavl.ru/), [META 2016](http://meta2016.pereslavl.ru/)

## Miscellaneous

 - [Sergei Romanenko's notes on supercompilation (in Russian)](https://sergei-romanenko.github.io/scp-notes-ru/)
