# Question-2
# Student 2's Answer to Question 2

**Q2**Assign variables to the individual components of your favourite gene (e.g. promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the 
entire gene by using the string concatenation on the standart output! Note: Feel free to create a fictional gene sequence by randomly filling in the components.


promoter = "TATTTAAATTAAAAATT"
5_prime_UTR = "GTAAGTTGGGGAAAA"
start_codon = "ATG"
exon1 = "ATCCCGGGTTCGAACTG"
intron = "AATTTTTAAGGGGGAAAAA"
exon2 = "GGCATTAGTCCAATGAAG"
stop_codon = "TAG"
3_prime_UTR = "AAAATTAAAAAAAAAAA"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 + intron + exon2 + stop_codon + 3_prime_UTR

print("My favourite gene sequence is as follows:")
print(my_fav_gene)
