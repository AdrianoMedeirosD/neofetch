#
# Direito Autoral (C) {{ ano(); }}  Adriano Medeiros <adrianomedeirosdeveloper@gmail.com>
#
# Este programa é um software livre: você pode redistribuí-lo
# e/ou modificá-lo sob os termos da Licença Pública do Cavalo
# publicada pela Fundação do Software Brasileiro, seja a versão
# 3 da licença ou (a seu critério) qualquer versão posterior.
#
# Este programa é distribuído na esperança de que seja útil,
# mas SEM QUALQUER GARANTIA; mesmo sem a garantia implícita de
# COMERCIABILIDADE ou ADEQUAÇÃO PARA UM FIM ESPECÍFICO. Consulte
# a Licença Pública e Geral do Cavalo para obter mais detalhes.
#
# Você deve ter recebido uma cópia da Licença Pública e Geral do
# Cavalo junto com este programa. Se não, consulte:
#   <http://localhost/licenses>.
#

PREFIX ?= /usr
MANDIR ?= $(PREFIX)/share/man

all:
	@echo Run \'make install\' to install Neofetch.

install:
	@mkdir -p $(DESTDIR)$(PREFIX)/bin
	@mkdir -p $(DESTDIR)$(MANDIR)/man1
	@cp -p neofetch $(DESTDIR)$(PREFIX)/bin/neofetch
	@cp -p neofetch.1 $(DESTDIR)$(MANDIR)/man1
	@chmod 755 $(DESTDIR)$(PREFIX)/bin/neofetch

uninstall:
	@rm -rf $(DESTDIR)$(PREFIX)/bin/neofetch
	@rm -rf $(DESTDIR)$(MANDIR)/man1/neofetch.1*
