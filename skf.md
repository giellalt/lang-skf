Nouns
Nouns in the Sakirabiá language are things.




Numerals
Numerals in the Sakirabiá language are numbers.


Verbs
Verbs in the Sakirabiá language are actions.


Adjectives
Adjectives in the Sakirabiá language describe things.
they follow the head of the NP and take the oblique markers we call case (perhaps elsewere adpositions)





Pronouns
Pronouns in the Sakirabiá language are references to things.


=================================== !
The Sakirabiá morphophonological/twolc rules file !
=================================== !




Archiconsonants













tek+N+Sg+Ill+PxSg1
* *o%<te%{kg%}%^WG%>%{bmØ%}%{õo%}*
* *o%<teg0%>0õ*





# Symbol affixes





Noun inflection
The Sakirabiá language nouns inflect in cases.





Proper noun inflection
The Sakirabiá language proper nouns inflect in the same cases as regular
nouns, but with a colon (':') as separator.



Verb inflection
The Sakirabiá language verbs inflect in persons.






Prefixes
Prefixes in the Sakirabiá language are bound to beginning of other words.



Adjective inflection
The Sakirabiá language adjectives compare.




INTRODUCTION TO MORPHOLOGICAL ANALYSER OF Sakirabiá LANGUAGE.


 # Definitions for Multichar_Symbols

## Analysis symbols
The morphological analyses of wordforms for the Sakirabiá
language are presented in this system in terms of the following symbols.
(It is highly suggested to follow existing standards when adding new tags).

The parts-of-speech are:

The parts of speech are further split up into:

The Usage extents are marked using following tags:

The nominals are inflected in the following Case and Number


The possession is marked as such:

The comparative forms are:
Numerals are classified under:
Verb moods are:

Verb personal forms are:
Other verb forms are





 * +Symbol = independent symbols in the text stream, like £, €, ©
Special symbols are classified with:
The verbs are syntactically split according to transitivity:
Special multiword units are analysed with:
Non-dictionary words can be recognised with:

Question and Focus particles:


Semantics are classified with


Derivations are classified under the morphophonetic form of the suffix, the
source and target part-of-speech.


Morphophonology
To represent phonologic variations in word forms we use the following
symbols in the lexicon files:
Archiconsonants


And following triggers to control variation

### Symbols that need to be escaped on the lower side (towards twolc):

* »
* «
* > (escaped with square brackets, to avoid collision with > as morpheme boundary)
* < (escaped with square brackets, to avoid collision with < as morpheme boundary)

## Flag diacritics
We have manually optimised the structure of our lexicon using following
flag diacritics to restrict morhpological combinatorics - only allow compounds
with verbs if the verb is further derived into a noun again:
 |  @P.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @D.NeedNoun.ON@ | (Dis)allow compounds with verbs unless nominalised
 |  @C.NeedNoun@ | (Dis)allow compounds with verbs unless nominalised

For languages that allow compounding, the following flag diacritics are needed
to control position-based compounding restrictions for nominals. Their use is
handled automatically if combined with +CmpN/xxx tags. If not used, they will
do no harm.
 |  @P.CmpFrst.FALSE@ | Require that words tagged as such only appear first
 |  @D.CmpPref.TRUE@ | Block such words from entering ENDLEX
 |  @P.CmpPref.FALSE@ | Block these words from making further compounds
 |  @D.CmpLast.TRUE@ | Block such words from entering R
 |  @D.CmpNone.TRUE@ | Combines with the next tag to prohibit compounding
 |  @U.CmpNone.FALSE@ | Combines with the prev tag to prohibit compounding
 |  @P.CmpOnly.TRUE@ | Sets a flag to indicate that the word has passed R
 |  @D.CmpOnly.FALSE@ | Disallow words coming directly from root.

Use the following flag diacritics to control downcasing of derived proper
nouns (e.g. Finnish Pariisi -> pariisilainen). See e.g. North Sámi for how to use
these flags. There exists a ready-made regex that will do the actual down-casing
given the proper use of these flags.
 |  @U.Cap.Obl@ | Allowing downcasing of derived names: deatnulasj.
 |  @U.Cap.Opt@ | Allowing downcasing of derived names: deatnulasj.




The word forms in the Sakurabiat language start from the lexeme roots of basic
word classes, or optionally from prefixes:







We describe here how abbreviations are in Sakirabiá are read out, e.g.
for text-to-speech systems.

For example:

 * s.:syntynyt # ;  
 * os.:omaa% sukua # ;  
 * v.:vuosi # ;  
 * v.:vuonna # ;  
 * esim.:esimerkki # ; 
 * esim.:esimerkiksi # ; 


















































% komma% :,      Root ;
% tjuohkkis% :%. Root ;
% kolon% :%:     Root ;
% sárggis% :%-   Root ; 
% násti% :%*     Root ; 
