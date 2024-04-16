# Genome_Seq

sequences = "CTGAGGAATGATCACACGGT TTAGACGCAGTCTTGTCAGT CCCTGACGACCACCGTAACA CCAATACGGGGTATCTTCAG CTGAACAGATGGCTTAGAAA TTCCCCGTTGCACAGTGTCC CGTAACATATACCCGGAATT GAGTTTGGCAAATCATTTTG CATCCGAATTCAGCTTAGTC GTGTTAAGGGCAGTATTATC CATTACCTGTACGCTGCTCA ATAAGCGAGTATGATTACCT"

# Split the sequences by space and add double quotes around each sequence
sequences_list = sequences.split()
formatted_sequences = ['"' + sequence + '"' for sequence in sequences_list]

# Join the formatted sequences with " " between them
result = " ".join(formatted_sequences)

print(result)
