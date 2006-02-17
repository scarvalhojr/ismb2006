BIN_DIR = ../bin
FILENAME = ismb2006

dvi:
	latex -output-directory=${BIN_DIR} -output-format=dvi ${FILENAME}.tex

pdf: dvi
	dvipdf ${BIN_DIR}/${FILENAME}.dvi ${BIN_DIR}/${FILENAME}.pdf

clean:
	rm -r ../bin/*
