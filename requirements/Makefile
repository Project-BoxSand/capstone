all:
	cd ./tex/ &&\
	  pdflatex -linktocpage ./problemrequirements_6_final.tex &&\
	  cp problemrequirements_6_final.pdf ../

clean:
	rm -f *.log *.pdf ./tex/*.aux ./tex/*.log

#This needs a lot of love... saving for later when, you know...
#all:
#	cd ./tex &&\
#	  latex -shell-escape ./problemrequirements_6_final.tex &&\
#	  dvips ./problemrequirements_6_final.dvi &&\
#	  ps2pdf ./problemrequirements_6_final.ps &&\
#	  cp ./problemrequirements_6_final.pdf ../
