

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Italian)

This relation is universal.

8443 nodes (3%) are attached to their parents as `advmod`.

6304 instances of `advmod` (75%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.30640767499704.

The following 28 pairs of parts of speech are connected with `advmod`: [it-pos/VERB]()-[it-pos/ADV]() (4694; 56% instances), [it-pos/NOUN]()-[it-pos/ADV]() (1434; 17% instances), [it-pos/ADJ]()-[it-pos/ADV]() (1420; 17% instances), [it-pos/ADV]()-[it-pos/ADV]() (273; 3% instances), [it-pos/PRON]()-[it-pos/ADV]() (198; 2% instances), [it-pos/PROPN]()-[it-pos/ADV]() (144; 2% instances), [it-pos/NUM]()-[it-pos/ADV]() (136; 2% instances), [it-pos/SCONJ]()-[it-pos/ADV]() (74; 1% instances), [it-pos/VERB]()-[it-pos/PRON]() (12; 0% instances), [it-pos/NOUN]()-[it-pos/SCONJ]() (8; 0% instances), [it-pos/SYM]()-[it-pos/ADV]() (8; 0% instances), [it-pos/AUX]()-[it-pos/ADV]() (7; 0% instances), [it-pos/CONJ]()-[it-pos/ADV]() (6; 0% instances), [it-pos/DET]()-[it-pos/ADV]() (6; 0% instances), [it-pos/VERB]()-[it-pos/ADP]() (4; 0% instances), [it-pos/ADJ]()-[it-pos/ADP]() (3; 0% instances), [it-pos/ADP]()-[it-pos/ADV]() (2; 0% instances), [it-pos/ADV]()-[it-pos/PRON]() (2; 0% instances), [it-pos/NOUN]()-[it-pos/X]() (2; 0% instances), [it-pos/VERB]()-[it-pos/X]() (2; 0% instances), [it-pos/ADJ]()-[it-pos/PRON]() (1; 0% instances), [it-pos/INTJ]()-[it-pos/ADV]() (1; 0% instances), [it-pos/NOUN]()-[it-pos/ADP]() (1; 0% instances), [it-pos/NOUN]()-[it-pos/VERB]() (1; 0% instances), [it-pos/PROPN]()-[it-pos/ADP]() (1; 0% instances), [it-pos/VERB]()-[it-pos/CONJ]() (1; 0% instances), [it-pos/VERB]()-[it-pos/SCONJ]() (1; 0% instances), [it-pos/X]()-[it-pos/ADV]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 5 advmod	color:blue
1	Stia	stare	VERB	V	Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
2	a	a	ADP	E	_	3	case	_	_
3	casa	casa	NOUN	S	Gender=Fem|Number=Sing	1	nmod	_	_
4	lo	il	DET	RD	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	5	det	_	_
5	stesso	stesso	ADV	B	_	1	advmod	_	SpaceAfter=No
6	.	.	PUNCT	FS	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 1 advmod	color:blue
1	Ecco	ecco	ADV	B	_	3	advmod	_	_
2	l'	il	DET	RD	Definite=Def|Number=Sing|PronType=Art	3	det	_	SpaceAfter=No
3	arringa	arringa	NOUN	S	Gender=Fem|Number=Sing	0	root	_	_
4	di	di	ADP	E	_	5	case	_	_
5	Tiziana	Tiziana	PROPN	SP	_	3	nmod	_	_
6	Maiolo	Maiolo	PROPN	SP	_	5	name	_	SpaceAfter=No
7	.	.	PUNCT	FS	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 9 advmod	color:blue
1	Le	il	DET	RD	Definite=Def|Gender=Fem|Number=Plur|PronType=Art	2	det	_	_
2	chiavi	chiave	NOUN	S	Gender=Fem|Number=Plur	10	nsubj	_	_
3	di	di	ADP	E	_	6	case	_	_
4	i	il	DET	RD	Definite=Def|Gender=Masc|Number=Plur|PronType=Art	6	det	_	_
5	suoi	suo	DET	AP	Gender=Masc|Number=Plur|Poss=Yes|PronType=Prs	6	det:poss	_	_
6	film	film	NOUN	S	Gender=Masc	2	nmod	_	_
7	sono	essere	VERB	V	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	10	cop	_	_
8	fin	fino	ADV	B	_	9	advmod	_	_
9	troppo	troppo	ADV	B	_	10	advmod	_	_
10	leggibili	leggibile	ADJ	A	Number=Plur	0	root	_	_
11	e	e	CONJ	CC	_	10	cc	_	_
12	giuste	giusto	ADJ	A	Gender=Fem|Number=Plur	10	conj	_	SpaceAfter=No
13	"	"	PUNCT	FB	_	12	punct	_	SpaceAfter=No
14	.	.	PUNCT	FS	_	10	punct	_	_

~~~


