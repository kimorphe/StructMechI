summary3.pdf:	summary3.dvi
	dvipdfmx -p a4 summary3.dvi
summary3.dvi:	summary3.tex fig1.eps strain.eps 2D_problems.eps
	platex summary3.tex


fig1.eps: fig1.svgz
	inkscape -z -f fig1.svgz -E fig1.eps
strain.eps: strain.svgz
	inkscape -z -f strain.svgz -E strain.eps
2D_problems.eps: 2D_problems.svgz
	inkscape -z -f 2D_problems.svgz -E 2D_problems.eps
