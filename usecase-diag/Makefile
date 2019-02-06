FILES = $(wildcard *.plantuml)
FILES_PNG = $(FILES:.plantuml=.png)

all: $(FILES_PNG)

a.png: a.plantuml
	java -jar ${PUMLJAR} a.plantuml
