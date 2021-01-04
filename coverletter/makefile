COMMAND="export"
INPUT="cover-letter.mm"
OUTPUT="cover-letter.pdf"

letter:
	./export > ${INPUT}
	./compile ${INPUT} ${OUTPUT}

watch: 
	$(READER) ${OUTPUT} &

