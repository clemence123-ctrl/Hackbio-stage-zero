# simple_code.py
Full_names = 'Clemence Usanase, Poornavaishnavi Chekuri, Aaronie Jersha Jenyfred, Abane Louis Ashu, Hasiba asma,  Zakia Salod'.split(",")

Slack_names = ' Clemence, Vaishnavi, Jersha Fernando, Louis ,Hasiba asma, Zakia Salod'.split(",")

countries = 'Rwanda, USA, USA,Cameroun, Pakistani, South Africa '.split(",")
 Hobbies = ' TV shows, Knowledge hunter, Book reading, investind and trading, Exploring AI with bioinformatics, Art'.split(",")
Affiliations= 'NA, University of Houston-Clear lake, Northeastern University, Universite Libre de Brussels(ULB)-Belgium, Sepal AI, University of KwaZulu-Natal'.split(",")
favorite_gene_Seq = 'EGFR, KRAS, GATA6, Hox gene'.split(",")
or name, country, hobby, affil, genes in zip(Full_names, countries, Hobbies, Affiliations, favorite_gene_Seq):
    print(f"{name.strip():30} | {country.strip():15} | {hobby.strip():40} | {affil.strip():55} | {genes.strip()}")
