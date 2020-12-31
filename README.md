# CLDataset (Extracted on 20-09-2020)
Russian dataset for natural language processing problems
Each file contains a single JSON array containing articles information
Object structure is as follow
cyberleninka.txt: Full information crawled from CyberLeninka (2098 papers)

	[
		{
			'keywords': [...],
			'fulltext': [...],
			'title': '...',
			'abstract': '...',
			'views': '...',
			'downloads': '...'
		},
		...
	]

cyberleninka_ds.txt: Reduced information, for most keyphrase extraction tasks (2098 papers)

	[
		{
			'keywords': [...],
			'fulltext': [...]
		},
		...
	]

cyberleninka_long.txt: Reduced information, for most keyphrase extraction tasks. Only longer papers (longer than 10000 characters). (900 papers)

	[
		{
			'keywords': [...],
			'fulltext': [...]
		},
		...
	]

cyberleninka_short.txt: Reduced information, for most keyphrase extraction tasks. Only shorter papers (shorter than 10000 characters). (900 papers)

	[
		{
			'keywords': [...],
			'fulltext': [...]
		},
		...
	]
