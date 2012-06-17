#
# Makefile para instalacao do pacote
#
# UFRGS TeX Users Group
# $Id: Makefile,v 5.1 2003/03/02 16:07:05 avila Exp $
#
INSTALLDIR = /usr/local/share/texmf

all:
	@echo "Digite \`\`make install'' para instalar o pacote."
	@echo "Por padrão, os arquivos serão instalados a partir de $(INSTALLDIR)"
	@echo "Você pode mudar essa configuração alterando a variável INSTALLDIR, no Makefile"
	@echo

install:
	install -d $(INSTALLDIR)/{doc/bibtex,bibtex/bst}/bibabnt
	install abnt.bst $(INSTALLDIR)/bibtex/bst/bibabnt
	install README CHANGELOG TO-DO-LIST manual.tex exemplo.bib $(INSTALLDIR)/doc/bibtex/bibabnt

clean:
	rm -f *[~#] *.{bak,aux,bbl,dvi,log,blg}
