all:
	cd ./tex &&\
	pdflatex -shell-escape -linktocpage ./designdocument_6_final.tex &&\
	  pdflatex -shell-escape -linktocpage ./designdocument_6_final.tex &&\
	  makeindex designdocument_6_final &&\
	  bibtex designdocument_6_final.tex &&\
	  pdflatex -shell-escape -linktocpage ./designdocument_6_final.tex &&\
	  pdflatex -shell-escape -linktocpage ./designdocument_6_final.tex &&\
	  cp designdocument_6_final.pdf ../

clean:
	rm -f *.log ./tex/*.aux ./tex/*.log
