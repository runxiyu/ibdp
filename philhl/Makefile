.PHONY: all
all: notes.pdf

%.pdf: %.tex
	mkdir -p ../build
	lualatex -interaction=nonstopmode $<
	lualatex -interaction=nonstopmode $<
	install $@ ../build
