This dataset contains information collected from citeulike website (http://www.citeulike.org). A website for helping researchers 
keep track of relevant scientific papers. Users can build their personalized libraries by adding selected papers to their 
libraries and annotate them with personalized tags tags.
This dataset records information about a set of users, their libraries, and a set of scientific publications (papers).
# users = 28416
# papers = 172079
# min library size = 10
# max library size = 2000
# min paper popularity = 3
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Files structures:
----------------------------------------------------------------------------------------------------------------------------
- papers.csv
	This file records papers information:
	Format: 
		- Comma delimited (CSV file)
		- No header
	Fields:
		1 - paper_id
		2 - type
		3 - journal
		4 - bookـtitle
		5 - series
		6 - publisher
		7 - pages
		8 - volume
		9 - number
		10 - year
		11 - month
		12 - postedat
		13 - address
		14 - title
		15 - abstract
----------------------------------------------------------------------------------------------------------------------------
- users_libraries.txt
	This file records users ratings (libraries), it reports users and their paper libraries
	semi-colon to separate user hash with library, comma to separate the IDs in the library, 
	Format:
		- No header
		- user_hash_id; comma separated list of paper_id's 
	Fields:
		1 - user_hash_id
		2 - user library: comma separated list of paper_id's 
----------------------------------------------------------------------------------------------------------------------------
- stopwords_en.txt
	This file contains the list of stop words in English
	Format:
		- No header
	Fields:
		- Single column ocntains the stop word