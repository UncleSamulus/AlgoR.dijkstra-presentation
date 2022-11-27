all: main.pdf

%.pdf: %.tex
	lualatex $<
	lualatex $<

clean:
	rm -f *.aux *.log *.out *.toc *.pdf

publish:
	cp main.pdf ../docs/AlgoR.dijkstra_slides.pdf