# Parser_wpp
Project to extract information from a WPP chat and return it as structured data for analysis using NLP, pandas, regex and watchdog.

1. The watchdog detects a new file created in the assigned directory, and this triggers the script that parses the information regardless of whether the chat was exported from an Android or iPhone.
2. Using pandas, regex and spacy, a data frame is created with all the relevant information.
3. Finally, the case where information already exists (recurring use) is addressed. In this case, the information is stored, but not overwritten.
