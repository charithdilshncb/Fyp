Usage:
	From the cloned source:
	python -m ln2sql.main -d <path> -l <path> -i <input-sentence> [-j <path>] [-t <path>] [-s <path>]
Parameters:
	-h					print this help message
	-d <path>				path to sql dump file
	-l <path>				path to language configuration file
	-i <input-sentence>			input sentence to parse
	-j <path>				path to JSON output file
	-t <path>				path to thesaurus file
	-s <path>				path to stopwords file

example of usage:

python -m ln2sql.main -d database_store/city.sql -l lang_store/english.csv -j output.json -i "Count how many city there are with the name blob?"