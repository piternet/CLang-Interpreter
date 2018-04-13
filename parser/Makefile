all:
	happy -gca Pargramatyka.y
	alex -g Lexgramatyka.x
	latex Docgramatyka.tex; dvips Docgramatyka.dvi -o Docgramatyka.ps
	ghc --make Testgramatyka.hs -o Testgramatyka
clean:
	-rm -f *.log *.aux *.hi *.o *.dvi
	-rm -f Docgramatyka.ps
distclean: clean
	-rm -f Docgramatyka.* Lexgramatyka.* Pargramatyka.* Layoutgramatyka.* Skelgramatyka.* Printgramatyka.* Testgramatyka.* Absgramatyka.* Testgramatyka ErrM.* SharedString.* gramatyka.dtd XMLgramatyka.* Makefile*

