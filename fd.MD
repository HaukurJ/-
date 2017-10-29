# Efnisyfirlit

| **        1** |
| --- |
| **        1** |
| **        1** |
| **        2** |
| **        2** |
| **        2** |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |
| |

# Inngangur

Þessi hönnunarskýrsla er unnnin fyrir Hugbúnaðarfræði kúrs af nemendum Háskóla Reykjavíkur. Skýrslan er skrifuð áður en forritun hófst til að hafa til hliðsjónar og leiðaraljós þegar þróun verkefnisins átti sér stað. Í henni má finna frumgerða hönnun skjámynda, klasarit, forritunarreglur o.fl. Verið er að hanna lítið skemmtilegt forrit _DREAM CRUSHER 4000_ sem leyfir vinum og vandamönnum að spila Tic-Tac-Toe við hvort annað og er hugsað fyrir fólk á öllum aldri til afþreyingar. Forritið er skrifað í Java forritunartungumálinu og þróað í Sublime.

# Skjámyndir Console

Einfalt Tic-Tac-Toe leikborð. &quot;X&quot; og &quot;O&quot; verða rituð inn eftir þörf.

 ![](data:image/*;base64,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)

# Skjámyndir Web

# Klasarit

Ákveðið var að halda kóðun leiksins sem einfaldastri til að flækja ekki of mikið fyrir í verkefninu og vorum því bara með 2 klasa, UI-layer og business-layer. Ákveðið var að halda ekki utanum gögn milli keyrslna.

# Forritunarreglur

**Nafnagiftir**

- Öll nafnagift skal vera á ensku og vera lýsandi. Reynt skal eftir fremsta megni að nöfn sem eru notuð séu ekki lykilorð. Lesanleiki skiptir meira máli en að hafa breytunöfn stutt.
- Klasar skulu vera í eintölu.

Eftirfarandi skal notast við **Camel Casing** :

- _Föll_

- _Breytur_

_Klasar_ skrifaðir með **Pascal Casing.       **

**Útlit**

- Inndráttur á kóða skal vera 4 stafabil
- Aðeins skal vera ein staðhæfing í hverri línu
- Það skal vera ein tóm lína á milli yfirlýsingu á property og falli
- Aðeins skal vera ein yfirlýsing í hverri línu
- Allir slaufusvigar skulu opnast í næstu línu
- Staðhæfingar skulu vera í svigum svo þær séu auðlesanlegar

**Athugasemdir**

- Staðsettar í sér línu, en ekki beint á eftir kóðanum í sömu línu
- Byrja athugasemdir með stórum staf
- Enda athugsasemda texta með punkti
- Á eftir // skal vera eitt bil áður en athugasemd byrjar
