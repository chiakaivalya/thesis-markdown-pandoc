# The Paper

 **Chia Huei Tan**^1,2^ and Patrick Meraldi^1,2^

\small ^1^ Institute of Biochemistry, ETH Zurich, CH-8093 Zurich, Switzerland
\newline
\small ^2^ Department of Physiology and Metabolism, Medical Faculty, University of Geneva, CH-1211 Geneva 4, Switzerland 
\newline   

The project was initiated, conceived, and directed by P.M. The majority of experiments and data analysis were carried out by **C.H.T.**. Data interpretation was carried out by **C.H.T.** and P.M with contribution of the other authors. P.M wrote the manuscript with contributions from **C.H.T.**

\pagebreak
 
## Abstract
write your abstract here. LaTeX commands can be used like above to start a new page

## Introduction  
Introduction goes here

## Results
### First result
 you can insert nice tables with footnotes using the package _threeparttable_. Use LaTeX language for symbols like \% and \textgreater.
 \begin{table}\sffamily
\begin{threeparttable}[b]
\captionsetup{font={normalsize,sf}}
\caption{caption}
\begin{tabular}{l c x{2.5cm}}
\toprule
Column 1 & Column 2 & Column 3\\
\midrule
A & B & C \\
D & E & F \\ 
\bottomrule\end{tabular}
\begin{tablenotes}
	\item footnote goes here
\end{tablenotes}\end{threeparttable}
\end{table}
 
  
### Second result

I had to insert figures that took up the entire page (like in journal publications), but wanted figure legends to always be on the page facing the figure. For this I used the package _fltpage_. Sadly, development of this package has stopped and it still doesn't work really perfectly. But it worked well enough for me. One bug I ran into was that if you specify the option twoside in your documentclass, fltpage might fail. As I was already using the documentclass **book**, two side is by default, and I did not have to specify it further. Since you are using LaTeX code here, you might need to use LaTeX language for symbols like \% and \textgreater.

\begin{FPfigure}
\centering 
\includegraphics{figures/FigureX.pdf}
\caption{\textbf{This figure is about X} (A) First subfigure. (B) Second subfigure. And sometimes a super long figure legend: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.}
\end{FPfigure}

### Third result 
In case you do call an FPfigure earlier, you will not be able to use markdown's standard figure insert method further down, but need to use LaTeX.

\begin{figure}[h!]
\centering
\includegraphics{figures/FigureY.pdf}
\caption{\textbf{This figure is about Y} (A) First subfigure. (B) Second subfigure.}
\end{figure} 

## Discussion
Write your discussion here.

## Methods
### Cell culture, siRNA and drug treatments

### Immunofluorescence

### Live-cell imaging 

### Statistical Methods

## Acknowledgements

vfill command will ensure that if your text is too short and doesn't fill up the entire page, it won't get spread out till the bottom. 
 
\vfill

\pagebreak
  
In case you want to have separate references, as in my case, I copied over the text from my submitted manuscript and i did not want to rewrite all the citations!
  
## References
1. Kaltschmidt, J. A., Davidson, C. M., Brown, N. H. & Brand, A. H. Rotation and asymmetry of the mitotic spindle direct asymmetric cell division in the developing central nervous system. Nat Cell Biol 2, 7–12 (2000).
2. Schneider, S. Q. & Bowerman, B. Cell polarity and the cytoskeleton in the Caenorhabditis elegans zygote. Annu. Rev. Genet. 37, 221–249 (2003).
3. Nicklas, R. B. & Arana, P. Evolution and the meaning of metaphase. J Cell Sci 102 ( Pt 4), 681–690 (1992).
4. Goshima, G. & Scholey, J. M. Control of mitotic spindle length. Annu Rev Cell Dev Biol 26, 21–57 (2010).
5. Khodjakov, A. L. & Pines, J. Centromere tension: a divisive issue. Nat Cell Biol 12, 919 (2010).

6. Li, X. & Nicklas, R. B. Mitotic forces control a cell-cycle checkpoint. Nature 373, 630–632 (1995).

7.  Kiyomitsu, T. & Cheeseman, I. M. Chromosome- and spindle-pole-derived signals generate an intrinsic code for spindle position and orientation. Nat Cell Biol 14, 311–317 (2012).

8. Kiyomitsu, T. & Cheeseman, I. M. Cortical Dynein and asymmetric membrane elongation coordinately position the spindle in anaphase. Cell 154, 391–402 (2013).

9.	Collins, E. S., Balchand, S. K., Faraci, J. L., Wadsworth, P. & Lee, W.-L. Cell cycle-regulated cortical dynein/dynactin promotes symmetric cell division by differential pole motion in anaphase. Mol Biol Cell 23, 3380–3390 (2012).
10.	Sluder, G., Thompson, E. A., Miller, F. J., Hayes, J. & Rieder, C. L. The checkpoint control for anaphase onset does not monitor excess numbers of spindle poles or bipolar spindle symmetry. J Cell Sci 110 ( Pt 4), 421–429 (1997).
11.	Yang, Z., Loncarek, J., Khodjakov, A. L. & Rieder, C. L. Extra centrosomes and/or chromosomes prolong mitosis in human cells. Nat Cell Biol 10, 748–751 (2008).
12.	Jaqaman, K. et al. Kinetochore alignment within the metaphase plate is regulated by centromere stiffness and microtubule depolymerases. J Cell Biol 188, 665–679 (2010).
13.	Greenan, G. et al. Centrosome size sets mitotic spindle length in Caenorhabditis elegans embryos. Curr Biol 20, 353–358 (2010).
14.	Keller, L. C., Wemmer, K. A. & Marshall, W. F. Influence of centriole number on mitotic spindle length and symmetry. Cytoskeleton (Hoboken) 67, 504–518 (2010).
15.	Leidel, S., Delattre, M., Cerutti, L., Baumer, K. & Gönczy, P. SAS-6 defines a protein family required for centrosome duplication in C. elegans and in human cells. Nat Cell Biol 7, 115–125 (2005).
16.	Vladimirou, E. et al. Nonautonomous movement of chromosomes in mitosis. Dev Cell 27, 60–71 (2013).
17.	Nigg, E. A. & Raff, J. W. Centrioles, centrosomes, and cilia in health and disease. Cell 139, 663–678 (2009).
18.	Kuo, T.-C. et al. Midbody accumulation through evasion of autophagy contributes to cellular reprogramming and tumorigenicity. Nat Cell Biol 13, 1214–1223 (2011).
19.	Maresca, T. J. & Salmon, E. D. Intrakinetochore stretch is associated with changes in kinetochore phosphorylation and spindle assembly checkpoint activity. J Cell Biol 184, 373–381 (2009).
20.	Uchida, K. S. K. et al. Kinetochore stretching inactivates the spindle assembly checkpoint. J Cell Biol 184, 383–390 (2009).
21.	Wan, X. et al. Protein architecture of the human kinetochore microtubule attachment site. Cell 137, 672–684 (2009).
22.	Kwiatkowski, N. et al. Small-molecule kinase inhibitors provide insight into Mps1 cell cycle function. Nat Chem Biol 6, 359–368 (2010).
23.	Rieder, C. L., Davison, E. A., Jensen, L. C., Cassimeris, L. & Salmon, E. D. Oscillatory movements of monooriented chromosomes and their position relative to the spindle pole result from the ejection properties of the aster and half-spindle. J Cell Biol 103, 581–591 (1986).
24.	Wandke, C. et al. Human chromokinesins promote chromosome congression and spindle microtubule dynamics during mitosis. J Cell Biol 198, 847–863 (2012).
25.	Mayer, T. U. et al. Small molecule inhibitor of mitotic spindle bipolarity identified in a phenotype-based screen. Science 286, 971–974 (1999).
26.	Mogensen, M. M., Malik, A., Piel, M., Bouckson-Castaing, V. & Bornens, M. Microtubule minus-end anchorage at centrosomal and non-centrosomal sites: the role of ninein. J Cell Sci 113 ( Pt 17), 3013–3023 (2000).
27.	Jeffery, J. M., Urquhart, A. J., Subramaniam, V. N., Parton, R. G. & Khanna, K. K. Centrobin regulates the assembly of functional mitotic spindles. Oncogene 29, 2649–2658 (2010).
28.	Zou, C. et al. Centrobin: a novel daughter centriole-associated protein that is required for centriole duplication. J Cell Biol 171, 437–445 (2005).
29.	Salmon, E. D. & Begg, D. A. Functional implications of cold-stable microtubules in kinetochore fibers of insect spermatocytes during anaphase. J Cell Biol 85, 853–865 (1980).
30.	Rieder, C. L. The formation, structure, and composition of the mammalian kinetochore and kinetochore fiber. Int Rev Cytol 79, 1–58 (1982).
31.	Schmidt, J. C. et al. Aurora B kinase controls the targeting of the Astrin-SKAP complex to bioriented kinetochores. J Cell Biol 191, 269–280 (2010).
32.	Ganem, N. J. & Compton, D. A. The KinI kinesin Kif2a is required for bipolar spindle assembly through a functional relationship with MCAK. J Cell Biol 166, 473–478 (2004).
33.	Ganem, N. J., Upton, K. & Compton, D. A. Efficient mitosis in human cells lacking poleward microtubule flux. Curr Biol 15, 1827–1832 (2005).
34.	Kapoor, T. M., Mayer, T. U., Coughlin, M. L. & Mitchison, T. J. Probing spindle assembly mechanisms with monastrol, a small molecule inhibitor of the mitotic kinesin, Eg5. J Cell Biol 150, 975–988 (2000).
35.	Wang, W.-J., Soni, R. K., Uryu, K. & Tsou, M.-F. B. The conversion of centrioles to centrosomes: essential coupling of duplication with segregation. J Cell Biol 193, 727–739 (2011).
36.	Rieder, C. L. & Borisy, G. G. The Centrosome Cycle in PtK2 Cells: Asymmetric distribution and structural changes in the pericentriolar material. Biol Cell 44, 117–132 (1982).
37.	Pereira, A. J. & Maiato, H. Maturation of the kinetochore-microtubule interface and the meaning of metaphase. Chromosome Res 20, 563–577 (2012).
38.	Meraldi, P., Draviam, V. M. & Sorger, P. K. Timing and checkpoints in the regulation of mitotic progression. Dev Cell 7, 45–60 (2004).
39.	Dick, A. E. & Gerlich, D. W. Kinetic framework of spindle assembly checkpoint signalling. Nat Cell Biol 15, 1370–1377 (2013).
40.	Collin, P., Nashchekina, O., Walker, R. & Pines, J. The spindle assembly checkpoint works like a rheostat rather than a toggle switch. Nat Cell Biol 15, 1378–1385 (2013).
41.	Rappaport, R. Experiments concerning the cleavage stimulus in sand dollar eggs. J. Exp. Zool. 148, 81–89 (1961).
42.	Bringmann, H. & Hyman, A. A. A cytokinesis furrow is positioned by two consecutive signals. Nature 436, 731–734 (2005).
43.	Dechant, R. & Glotzer, M. Centrosome separation and central spindle assembly act in redundant pathways that regulate microtubule density and trigger cleavage furrow formation. Dev Cell 4, 333–344 (2003).
44.	Mchedlishvili, N. et al. Kinetochores accelerate centrosome separation to ensure faithful chromosome segregation. J Cell Sci 125, 906–918 (2012).
45.	McClelland, S. E. et al. The CENP-A NAC/CAD kinetochore complex controls chromosome congression and spindle bipolarity. EMBO J 26, 5033–5047 (2007). 
