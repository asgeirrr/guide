Příručka pro pořadatele kurzů pro začátečníky
#############################################

- vycházíme z toho, jak se dělají PyLadies, ale příručka by měla být obecná na jakýkoliv kurz pro začátečníky
- místo
- jak sehnat kouče
- kolik koučů?
- čas; 30 min na review úkolů; 90 min zbytek
- 1. sraz - představení
- červené/zelené papírky
- "desatero" pro kouče (co z desatera má smysl?)
- "čtvrteční srazy"

Tato příručka by měla pomoci organizátorům programovacích kurzů pro začátečníky. Měla by nabídnout nápady, které se osvědčily, a varovat před chybami, kterých jsme se již jednou dopustili, a které by bylo zbytečné opakovat. Ačkoliv vychází primárně ze zkušeností z organizace brněnských a pražských PyLadies, většina poznatků a tipů by měla být aplikovatelná na jakýkoliv kurz pro začátečníky.

1. Organizace a komunikace
==========================

1.1 Zdůraznit práci na úkolech
------------------------------
Je dobré od začátku říkat, že kurz vyžaduje důslednou práci na úkolech, které zaberou čas.
Účastník by měl dopředu počítat s tím, že časová náročnost je více než 2 hodiny týdně na kurzu.
Zároveň by ale měli organizátoři aktivně a často nabízet pomoc při jejich plnění (individuální či hromadné konzultace, popř. pomoc online).
Pokud účastníci nestíhají úkoly plnit, neovládnou probrané téma dobře a při dalších lekcích se to často negativně projeví a začne se nabírat skluz.

1.2 Dát najevo, že jsme všichni začínali stejně
-----------------------------------------------
Začátečníci si často mohou připadat ztraceně nebo hloupě. Ty pocity zažívají i zkušení programátoři každý den, ale to začátečník neví a připadá si,
že se nikdy nemůže naučit programovat. Pomohlo by, kdyby koučové zdůrazňovali, že začátky jsou těžké a u náročnější partie explicitně říct něco jako:
"Já tohle pochopil až napočtvrté/po měsíci." nebo "Tohle téma se na VŠ bere půl semestru."

1.3 Seznámit vedlejší kouče s pravidly koučování
------------------------------------------------
Ač si všichni přejeme v kurzu přátelskou atmosféru, nemůže být na srazech chaos. Často se jako organizátoři soustředíme na účastníky a zapomínáme, že nový kouč nemusí vědět, jak se chovat a ne každý oplývá přirozeně takovou dávkou taktu, aby nenarušoval průběh kurzu. Zvláště je to problém, když během kurzu vedlejší koučové fluktuují. Na pražských PyLadies bylo zavedeno následující desatero kouče:

# Jsem tu proto, abych rozvíjel každou PyLady (PL).
# Hlavní kouč vede hodinu a otvírá nová témata. Vždy vysvětluji pouze to, co je aktuálně řešené (a nepředbíhám).
# Pokud opravdu musím vysvětlovat něco, i když hlavní kouč mluví, šeptám, abych nerušil ostatní PL, které poslouchají.
# Neustále se aktivně rozhlížím po červených papírcích, každá PL může být v nesnázích. A třeba to můžu být já, kdo jí zachrání. Nekempuji u jedné PL celý večer.
# Na červené papírky (volání o pomoc) kolem sebe reaguji okamžitě.
# Klávesnice každé PL je svatá a sahat na ní může pouze ona.
# Řešení problému by mělo vzejít od PL, napovídáním jí pomohu pouze krátkodobě.
# Pokud si neví PL rady, snažím se jí dovést k řešení otázkami, na které si sama odpovídá.
# Nepoužívám terminologii, kterou PL zatím nezná, ani nezlehčuji problémy, které řeší. Chápu, že je začátečník a pravděpodobně nemá ani technické zázemí.
# Chválím PL pokaždé, když se jí povede vyřešit i sebemenší problém (dává jí to více chuti k dalšímu objevování).

Dále nepomáhá řešit přede všemi s hlavním koučem kvality vybraného textového editoru, zvoleného postupu řešení problému (protože ten je většinou pečlivě vybrán ohledem na to, co zatím studenti znají, ačkoliv to není ten nejlepší způsob) a čehokoliv, co nepřispívá k pochopení právě probírané látky. Podobné debaty se hodí např. k pivu, kdy se řeší, jak celý kurz zlepšit, čemuž by měli být organizátoři nakloněni a vyslechnout všechny názory.

### 1.4 Držet počet hlavních koučů v rozumných mezích
Přílišné střídání koučů není pro kurz dobré. Podmínka, aby hlavní kouč byl alespoň vedlejším koučem na předešlém srazu je nutná. Ale i tak by bylo lepší držet počet hlavních koučů nízký (řekněme do 4) a nestřídat je často, spíš se snažit naplánovat pro hlavního kouče blok 3 nebo 4 srazů po sobě. Střídání po jedné hodině je náročné pro hlavního kouče i pro holky.

## 2. Technické problémy

### 2.1 Vyzkoušet materiály pro všechny platformy
Nejčastěji byl problém s Windows, někdy s MacOS (viz Grafika na Verčině MacBooku). Hlavní kouč musí mít v Windows v malíčku -- instalaci Pythonu, Unicode znaky, nepoužitelný terminál a práci s Gitem (hlavně kterou instalačku použít).

### 2.2 Dělat úlohy maximálně multiplatformní
Různé instrukce pro různé systémy jsou pro holky zbytečně matoucí a hlavnímu koučovi ubírají čas na vysvětlení samotného problému. Do příštího kurzu by bylo dobré zvážit použití [Minicondy](http://conda.pydata.org/miniconda.html) a [IPython](http://ipython.org/) Notebooku, což jsou nástroje, které se chovají na všech platformách stejně (teoreticky) a na Windows řadu věcí zjednodušují (hlavně instalaci knihoven jako je NumPy či SciPy, které mohou být snadno použity pro zpestření úkolů). Instrukce by pak mohly být pro různé platformy podobnější.

## 3. Výuka

### 3.1 Nebrat harmonogram závazně
Harmonogram je potřeba, ale není to tak, že by přes něj nějel vlak. Každá skupina bude jiná a bude postupovat jiným tempem popř. jí půjdou různá témata různě rychle. Myslím, že jsme se všichni cítili zavázáni harmonogramem hlavně kvůli tomu, že Petr Viktorin připravil výborné materiály a my chtěli postupovat podle nich. A to přesto, že jsme viděli, jak jsme holky na začátku dost zavalili. Je potřeba na začátku nepodcenit představování a zjistit, jaké mají holky zkušenosti a jaké jsou jejich cíle a podle toho přizpůsobit harmonogram.

### 3.2 Nekompromisně vyžadovat úkoly
Úkolů bylo hodně a holky je vůbec nestíhaly a zdálo se, že jejich objem je dost děsí. Možná jich není potřeba tolik. Kdyby holky udělaly jen polovinu, pořád by si asi dané téma dost procvičilo. Ale je nutné je udělat, tím se osamostatní při programování od koučů.

Objevil se nápad, aby kromě výkladu byla další hodina vyloženě konzultace nad úkoly, popř. jeden týden učit, druhý týden konzultovat. 

### 3.3 Prakticky zaměřené úlohy

Téma srazu může být např. _Seznamy_, ale výstupem by mělo být něco užitečného, při čem se seznamy procvičí, a zároveň by to mělo mít nějaký pěkný výstup (např. graf nebo jinou vizualizaci), tím podpoříme radost z programování. Není dobré vyjmenovávat všechno, co se dá se seznamy dělat, spíš se soustředit na základní použití. Poskytnutí [taháku](http://pyladies.cz/v1/s007-cards/list-cheatsheet.html) všech funkcí seznamů je ale užitečné.

### 3.4 Vyvarovat se příliš komplexním úlohám
Obtížnějších úloh jako byl např. Solitaire bychom se měli vyvarovat. V základním kurzu by mělo být cílem naučit holky formalizovat drobný problém z reálného světa a implementovat ho v Pythonu. Přínosnější je dělat více menších úloh než jednu velkou, ve které se budou holky ztrácet.
