

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is universal.

957 nodes (1%) are attached to their parents as `advcl`.

770 instances of `advcl` (80%) are right-to-left (child precedes parent).
Average distance between parent and child is 8.79937304075235.

The following 26 pairs of parts of speech are connected with `advcl`: [fa-pos/VERB]()-[fa-pos/VERB]() (311; 32% instances), [fa-pos/VERB]()-[fa-pos/ADJ]() (132; 14% instances), [fa-pos/VERB]()-[fa-pos/ADV]() (91; 10% instances), [fa-pos/NOUN]()-[fa-pos/VERB]() (77; 8% instances), [fa-pos/ADJ]()-[fa-pos/VERB]() (71; 7% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (63; 7% instances), [fa-pos/VERB]()-[fa-pos/NOUN]() (62; 6% instances), [fa-pos/ADJ]()-[fa-pos/ADJ]() (34; 4% instances), [fa-pos/NOUN]()-[fa-pos/ADV]() (23; 2% instances), [fa-pos/ADJ]()-[fa-pos/ADV]() (20; 2% instances), [fa-pos/ADJ]()-[fa-pos/NOUN]() (20; 2% instances), [fa-pos/NOUN]()-[fa-pos/NOUN]() (15; 2% instances), [fa-pos/VERB]()-[fa-pos/CONJ]() (8; 1% instances), [fa-pos/PRON]()-[fa-pos/VERB]() (6; 1% instances), [fa-pos/ADJ]()-[fa-pos/CONJ]() (4; 0% instances), [fa-pos/ADV]()-[fa-pos/NOUN]() (4; 0% instances), [fa-pos/ADV]()-[fa-pos/ADJ]() (3; 0% instances), [fa-pos/ADV]()-[fa-pos/VERB]() (3; 0% instances), [fa-pos/ADP]()-[fa-pos/ADJ]() (2; 0% instances), [fa-pos/PRON]()-[fa-pos/ADJ]() (2; 0% instances), [fa-pos/ADJ]()-[fa-pos/NUM]() (1; 0% instances), [fa-pos/AUX]()-[fa-pos/VERB]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/CONJ]() (1; 0% instances), [fa-pos/NUM]()-[fa-pos/ADJ]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/NUM]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/PRON]() (1; 0% instances).


~~~ conllu
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 16 advcl	color:blue
1	گفت	گفت#گو	VERB	V_PA	Number=Sing|Person=3|Tense=Past	0	root	_	_
2	:	:	PUNCT	DELM	_	1	punct	_	_
3	بر	بر	ADP	P	_	4	case	_	_
4	من	من	PRON	PRO	Number=Sing|Person=1|PronType=Prs	6	nmod	_	_
5	روزی	روز	NOUN	N_SING	Number=Sing	6	nsubj	_	_
6	نمی‌گذرد	_	VERB	V_PRS	Number=Sing|Person=3|Tense=Pres	1	ccomp	_	_
7	مگر	مگر	ADV	ADV_I	PronType=Int	16	mark	_	_
8	آن	آن	PRON	PRO	Number=Sing|PronType=Dem	7	mwe	_	_
9	که	که	CONJ	CON	_	8	mwe	_	_
10	علی	علی	NOUN	N_SING	Number=Sing	16	dobj	_	_
11	)	)	PUNCT	DELM	_	10	punct	_	_
12	ع	ع	NOUN	N_SING	Number=Sing	10	dep	_	_
13	(	(	PUNCT	DELM	_	10	punct	_	_
14	را	را	PART	CLITIC	_	10	case	_	_
15	یاد	یاد	NOUN	N_SING	Number=Sing	16	compound:lvc	_	_
16	می‌کنم	_	VERB	V_PRS	Number=Sing|Person=1|Tense=Pres	6	advcl	_	_
17	.	.	PUNCT	DELM	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 advcl	color:blue
1	مدینه	مدینه	NOUN	N_SING	Number=Sing	7	dobj	_	_
2	را	را	PART	CLITIC	_	1	case	_	_
3	در	در	ADP	P	_	4	case	_	_
4	آخر	آخر	ADJ	ADJ	Degree=Pos	7	advcl	_	_
5	کار	کار	NOUN	N_SING	Number=Sing	4	nmod:poss	_	_
6	قرار	قرار	NOUN	N_SING	Number=Sing	7	compound:lvc	_	_
7	دادم	داد#ده	VERB	V_PA	Number=Sing|Person=1|Tense=Past	0	root	_	_
8	.	.	PUNCT	DELM	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 advcl	color:blue
1	بایستی	_	AUX	V_AUX	VerbForm=Inf	5	aux	_	_
2	گامی	گام	NOUN	N_SING	Number=Sing	5	dobj	_	_
3	به	به	ADP	P	_	4	case	_	_
4	پیش	پیش	ADV	ADV_LOC	Case=Loc	5	advcl	_	_
5	نهاد	_	VERB	V_PA	Number=Sing|Person=3|Tense=Past	0	root	_	_
6	.	.	PUNCT	DELM	_	5	punct	_	_

~~~


