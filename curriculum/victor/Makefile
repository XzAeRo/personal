CC = lualatex
OUTPUT_DIR = share


english: VictorGonzalez.en.tex
	$(CC) VictorGonzalez.en.tex

spanish: VictorGonzalez.es.tex
	$(CC) VictorGonzalez.es.tex
	
relayr: cover\ letters/VictorGonzalez.relayr.tex
	$(CC) cover\ letters/VictorGonzalez.relayr.tex
	
clean:
	rm *.aux *.bcf *.log *.out *.xml

all: english clean spanish clean relayr clean