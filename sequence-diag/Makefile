FILES = $(wildcard *.plantuml)
FILES_PNG = $(FILES:.plantuml=.png)

all: $(FILES_PNG)

a.png: a.plantuml
	java -jar ${PUMLJAR} a.plantuml

b.png: b.plantuml
	java -jar ${PUMLJAR} b.plantuml

c.png: c.plantuml
	java -jar ${PUMLJAR} c.plantuml
