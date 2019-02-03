FILES = $(wildcard *.plantuml)
FILES_PNG = $(FILES:.plantuml=.png)

all: $(FILES_PNG)

a.png: a.plantuml
	java -jar ${PUMLJAR} a.plantuml

b.png: b.plantuml
	java -jar ${PUMLJAR} b.plantuml

c.png: c.plantuml
	java -jar ${PUMLJAR} c.plantuml

d.png: d.plantuml
	java -jar ${PUMLJAR} d.plantuml

e.png: e.plantuml
	java -jar ${PUMLJAR} e.plantuml

f.png: f.plantuml
	java -jar ${PUMLJAR} f.plantuml
