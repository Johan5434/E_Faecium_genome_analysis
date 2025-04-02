.PHONY: all clean

all: run

run: TSV_to_CSV.py metadata_splitter_to_CSV.py
	python TSV_to_CSV.py
	python metadata_splitter_to_CSV.py

clean:
	rm -f metadata_Tnseq_BHI.csv metadata_Tnseq_Serum.csv metadata_RNAseq_tRNA.csv metadata_RNAseq_other.csv metadata_unclassified.csv

