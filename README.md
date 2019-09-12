# Programavimas su R

R kalbos istorija prasideda 1976 m. garsiojoje Bell laboratorijoje.
Iki tol statistiniams skaičiavimams atlikti daugiausia buvo
naudojama Fortran kalbos biblioteka SCS (Statistical Computing
Subroutines). Jos galimybių užteko standartiniams skaičiavimams,
tačiau net ir paprasčiausių skaičiavimų nebuvo galima atlikti
interaktyviai. Komercinės statistinių skaičiavimų programos dažnai 
pateikdavo visus įmanomus skaičiavimų rezultatus, kokie tik gali 
būti susiję su sprendžiamu uždaviniu. Toks nelankstumas kėlė 
nepatogumų sudarant naujus, nestandartinius statistinius modelius ar 
tikrinant įvairias statistines idėjas. John Chambers,
Richard Becker ir Allan Wilks sukūrė specialiai interaktyviems
skaičiavimams statistikoje ir duomenų analizėje skirtą programavimo
kalbą S, kurios pagrindas yra funkcijos, o bazinė duomenų struktūra
— vektorius.

1993 m. Naujosios Zelandijos Oklando universitete Ross Ihaka ir
Robert Gentleman sukurė statistiniams skaičiavimams ir grafiniam
duomenų atvaizdavimui skirtą programavimo kalbą R. Jos pagrindas
buvo funkcinio programavimo kalba Scheme (Lisp dialektas), tačiau 
ji turėjo S kalbos sintaksę. Ilgainiui R perėmė daug kitų S kalbos
bruožų. Dabar galima sakyti, kad R yra S kalbos dialektas arba jos
realizacija. Kalbant formaliai, **R yra interpretuojama, dinaminės
tipizacijos funkcinio programavimo kalba su objektinio programavimo
galimybėmis**.

Pagal savo paskirtį R orientuota į statistinę duomenų analizę ir
duomenų vizualizavimą, tačiau vien tuo neapsiriboja. Jos galimybes
labai išplečia didžiulis kiekis paketų, kurie leidžia spręsti
įvairius skaičiavimo uždavinius. Šiuo metu 
<a href="https://cran.r-project.org/" target = "_blank">CRAN</a> 
(The Comprehensive R Archive Network) turi beveik 15 tūkst.
paketų. Nemažai naujų R paketų patalpinama į Github ir kitur.

Skirtingai nuo S, kuri yra komercinė kalba, R kalba yra 
<a href="https://en.wikipedia.org/wiki/GNU_Project">GNU projekto</a> 
dalis, yra nemokama ir laisvai platinama. Jos vystymu rūpinasi R 
fondas (<a href="https://www.r-project.org/foundation/">The R Foundation</a>). 
Daugiau informacijos <a href="https://www.r-project.org/" target = "_blank">www.r-project.org</a>.
            
            
<h1>Rekomenduojama literatūra</h1>
            
<ul>
  <li>Dennis B. <i>The R Student Companion</i></li>
  <li>Davies T.M. <i>The Book of R</i></li>
  <li>Chambers J.M. <i>Software for Data Analysis. Programming with R</i></li>
  <li>Matloff N. <i>The Art of R Programming. A Tour of Statistical Software Design</i></li>
  <li>Wickham H. <i><a href = "http://adv-r.had.co.nz/" target = "_blank">Advanced R</a></i></li>
</ul>

<h3>Konspektai</h3>

<ul>
<li>Rekašius T. <i><a href = "https://github.com/trekasius/Rkonspektas" target = "_blank">Programavimo su R konspektas</a></i></li>
</ul>

<h3>Oficiali R kalbos dokumentacija</h3>

<ul>
<li><a href = "https://cran.r-project.org/manuals.html" target = "_blank">The R Manuals</a></li>
<li><a href = "https://cran.r-project.org/doc/manuals/r-release/R-lang.html" target = "_blank">R Language Definition</a></li>
<li><a href = "https://cran.r-project.org/other-docs.html" target = "_blank">Contributed Documentation</a></li>
</ul>

<h3>Knygos apie R grafines sistemas</h3>

<ul>
<li>Murrell P. <i>R Graphics (2nd edition)</i></li>
<li>Wilkinson L. <i>The Grammar of Graphics (2nd edition)</i></li>
<li>Sarkar D. <i>Lattice. Multivariate Data Visualization with R</i></li>
<li>Wickham H. <i>ggplot2. Elegant Graphics for Data Analysis (2nd edition)</i></li>
</ul>
            
<h3>Kai kurios specializuotos temos</h3>

<ul>
  <li>Bloomfield V.A. <i>Using R for Numerical Analysis in Science and Engineering</i></li>
  <li>Jones O. <i>Introduction to Scientific Programming and Simulation using R</i></li>
  <li>Rizzo M.L. <i>Statistical Computing with R</i></li>
  <li>Spector Ph. <i>Data Manipulation with R</i></li>
  <li>Wickham H. <i><a href="http://r4ds.had.co.nz/" target = "_blank">R for Data Science</a></i></li>
  <li>Eubank R.L. <i>Statistical Computing in C++ and R</i></li>
  <li>Eddelbuettel D. <i>Seamless R and C++ Integration with Rcpp</i></li>
</ul>

<h3>Straipsniai ir kiti skaitiniai</h3>

<ol>
<li>Richard A. Becker. <a href="http://www.lcg.unam.mx/~lcollado/R/resources/history_of_S.pdf" target = "_blank">A Brief History of S</a></li> 
<li>Ross Ihaka, Robert Gentleman. <a href="http://biostat.mc.vanderbilt.edu/wiki/pub/Main/JeffreyHorner/JCGSR.pdf" target = "_blank">R: A Language for Data Analysis and Graphics</a></li>
<li>Martyn Plummer. <a href="http://calcul.math.cnrs.fr/IMG/pdf/r-history-ecology.pdf" target = "_blank">History and Ecology of R</a></li>
<li>Patrick Burns. <a href="http://www.burns-stat.com/pages/Tutor/R_inferno.pdf" target = "_blank">The R Inferno</a> — “If you are using R and you think you're in hell, this is a map for you.”</li>
<li>John M. Chambers. <a href="https://arxiv.org/pdf/1409.3531v1.pdf" target = "_blank">Object-Oriented Programming, Functional Programming and R</a></li>
<li>Suraj Gupta. <a href="http://blog.obeautifulcode.com/R/How-R-Searches-And-Finds-Stuff/" target = "_blank">How R Searches and Finds Stuff</a></li>
<li>Robert Gentleman, Ross Ihaka. <a href="https://www.stat.auckland.ac.nz/~ihaka/downloads/lexical.pdf" target = "_blank">Lexical Scope and Statistical Computing</a></li>
</ol>

<h3>Naudingos nuorodos</h3>

<ul>
<li><a href="http://www.cookbook-r.com/">Cookbook for R</a></li>
<li><a href="http://adv-r.had.co.nz/Style.html">Style guide</a></li>
<li><a href="https://google.github.io/styleguide/Rguide.xml">Google's R Style Guide</a></li>
</ul>


<h1>Paskaitų ir pratybų temos</h1>

<h3>I dalis. R kalbos pradmenys</h3>
            
<ol>
<li>Vektoriai ir vektoriaus elementų tipai: <b>logical</b>, <b>integer</b>, <b>numeric</b>, <b>complex</b>, <b>character</b> ir <b>raw</b>.</li>
<li>Pagrindinės duomenų struktūros ir jų sudarymo funkcijos: <b>vector</b>, <b>matrix</b>, <b>array</b>, <b>data.frame</b>, <b>list</b> ir <b>factor</b>.</li>
<li>Kategorinių ir ranginių kintamųjų sudarymas naudojant funkciją <b>factor</b>. Funkcijos <b>levels</b>, <b>nlevels</b>, <b>relevel</b>, <b>reorder</b>.</li>
<li>Vektorių ir sąrašų apjungimas naudojant funkciją <b>c</b>. Vektorių apjungimas į matricą naudojant funkcijas <b>rbind</b>, <b>cbind</b>.</li>
<li>Vektorių, matricų ir kitų duomenų struktūrų transformavimas. Funkcijos <b>as.vector</b>, <b>as.matrix</b>, <b>as.factor</b> ir t. t.</li>
<li>Aritmetinių sekų generavimas naudojant operatorių <b>:</b> ir funkciją <b>seq</b>. Funkcijos <b>seq_along</b>, <b>seq_len</b>, <b>sequence</b>.</li>
<li>Kategorinių ir ranginių kintamųjų generavimas naudojant funkciją <b>gl</b>.</li>
<li>Vektoriaus arba sąrašo elementų pakartojimo funkcija <b>rep</b>. Funkcijos <b>rep.int</b> ir <b>rep_len</b>.</li>
<li>Elementų išrinkimo iš vektorių, matricų, sąrašų ir duomenų lentelių būdai. Funkcijos <b>[</b> ir <b>[[</b>, <b>$</b>, <b>head</b>, <b>tail</b>.</li>
<li>Vektorių, matricų ir kitų duomenų struktūrų elementai ir jų skaičiaus nustatymas. Funkcijos <b>length</b>, <b>dim</b>, <b>nrow</b>, <b>ncol</b>.</li>
<li>Duomenų nuskaitymas iš tekstinių ir binarinių failų. Funkcijos <b>scan</b>, <b>read.table</b>, <b>readLines</b>, <b>load</b>.</li>
<li>Duomenų įrašymas į tekstinius ir binarinius failus. Funkcijos <b>write</b>, <b>write.table</b>, <b>writeLines</b>, <b>save</b>.</li>
<li>Duomenų nuskaitymas iš iškarpinės (<em>clipboard</em>). Virtualaus tekstinio failo sudarymas ir nuskaitymas, f-ja <b>textConnection</b>.</li>
<li>Veiksmai su loginiais kintamaisiais. Loginiai operatoriai <b>!</b>, <b>==</b>, <b>!=</b>, <b>|</b>, <b>&</b>, <b>||</b>, <b>&&</b>. Funkcijos <b>all</b> ir <b>any</b>.</li>
<li>Informacinės funkcijos: <b>is.vector</b>, <b>is.character</b> ir t. t. Objektų tapatumo nustatymo f-jos <b>identical</b>, <b>isTRUE</b> ir <b>all.equal</b>.</li> 
<li>Sąlygos konstrukcija <b>if</b> arba <b>if-else</b>. Vektorinė sąlygos funkcija <b>ifelse</b>.</li>
<li>Ciklai: <b>for</b>, <b>while</b> ir <b>repeat</b> ciklai. Iteracijos ir ciklo nutraukimo funkcijos <b>next</b> ir <b>break</b>.</li>
<li>Iteracijos per vektoriaus, matricos, duomenų lentelės ir sąrašo elementus. Funkcijos <b>apply</b>, <b>lapply</b>, <b>sapply</b>.</li>
<li>Matricos eilučių arba stulpelių sumos arba vidurkio skaičiavimo funkcijos <b>rowSums</b>, <b>rowMeans</b>, <b>colSums</b>, <b>colMeans</b>.</li>
<li>Duomenų grupavimas. Funkcijos reikšmės skaičiavimas atskirose grupėse naudojant funkcijas <b>tapply</b>, <b>by</b> ar <b>aggregate</b>.</li>
<li>Funkcijos reikšmės perskaičiavimas keičiant argumentų reikšmes. Funkcija <b>mapply</b>.</li>
<li>Funkcijos reikšmės ant dviejų argumentų dekartinės sandaugos apskaičiavimas. Funkcija <b>outer</b> ir operatorius <b>%o%</b>.</li>
<li>Vektoriaus elementų perstatymas ir atsitiktinės imties sudarymas naudojant funkciją <b>sample</b>.</li>
<li>Pakartotinis funkcijos reikšmės perskaičiavimas naudojant funkcija <b>replicate</b> ir jos panaudojimas kartu su f-ja <b>sample</b>.</li>
<li>Kai kurie tipiniai veiksmai su matricomis ir lentelėmis. Funkcijos <b>subset</b>, <b>scale</b>, <b>sweep</b>.</li>
<li>Praleistos reikšmės <b>NA</b> ir jų pašalinimas iš duomenų lentelės: funkcija <b>is.na</b>, <b>complete.cases</b>, <b>na.omit</b>.</li>
</ol>

<h3>II dalis. R kalbos objektai, sintaksė ir semantika</h3>

<ol>
<li>Trumpai apie R ir kitas funkcinio programavimo kalbas. Imperatyvinio ir deklaratyvinio programavimo paradigmos.</li>
<li>R kalbos objektų apžvalga. Objekto tipas ir objekto klasė. Funkcijos <b>class</b>, <b>typeof</b>, <b>mode</b> ir <b>storage.mode</b>.</li>
<li>Sintaksiškai taisyklingo R objekto vardo sudarymo taisyklės. Sintaksiškai netaisyklingų vardų naudojimas.</li>
<li>Vardo ir objekto susiejimas. Priskyrimo operatorius <b><-</b> arba <b>-></b> ir globalaus priskyrimo operatorius <b><<-</b>.</li>
<li>Standartiniai R objektų atributai. Funkcijos <b>names</b>, <b>row.names</b>, <b>dim</b>, <b>dimnames</b>, <b>rownames</b>, <b>colnames</b>.</li>
<li>NULL objektas. Funkcija <b>is.null</b>. NULL objekto panaudojimas objekto elementų panaikinimui.</li>
<li>R objektų atributai ir jų pakeitimas. Funkcijos <b>attr</b> ir <b>attributes</b>. Atributų panaikinimas priskiriant reikšmę NULL.</li>
<li>Skliaustai-funkcijos <b>()</b> ir <b>{}</b>, jų grąžinomos reikšmės ir reikšmės matomumas. Funkcijos <b>invisible</b> ir <b>withVisible</b>.</li>
<li>Standartinės R funkcijos struktūra ir jos sudarymas. Funkcija <b>function</b>. Funkcijos reikšmės grąžinimo funkcija <b>return</b>.</li>
<li>Anoniminės funkcijos, jų iškvietimas ir tipiniai anoniminių funkcijų naudojimo pavyzdžiai.</li>
<li>Reikšmių f-jos argumentams priskyrimo taisyklės. Argumentai su numatytaja reikšme.</li>
<li>Argumentas <b>...</b> (<em>dot-dot-dot</em>) ir jo panaudojimas įdėtosios funkcijos argumentų reikšmių perdavimui.</li>
<li>Vektorizuotos ir nevektorizuotos R funkcijos. Funkcijos vektorizavimas naudojant f-ją <b>Vectorize</b>.</li>
<li>Funkcijos argumentų reikšmių korektiškumo tikrinimas. Funkcijos vykdymo nutraukimas ir pranešimai apie klaidą.</li>
<li>Detali R funkcijos struktūra. Funkcijos <b>formals</b>, <b>body</b> ir <b>environment</b>.</li>
<li>Funkcijos argumentų sąrašo nustatymas: funkcijos <b>args</b>, <b>formalArgs</b>. Argumentų sąrašo pakeitimas su f-ja <b>formals</b>.</li>
<li>Binarinių operatorių <b>%op%</b> sudarymas, pakeitimo funkcijų <b>fx<-</b> užrašymas ir jų panaudojimas.</li>
<li>Aukštesnio lygio funkcijos (higher-order function): <b>Map</b>, <b>Reduce</b>, <b>Filter</b>, <b>Find</b>, <b>Position</b>, <b>Negate</b> ir jų taikymas.</li>
<li>Kalbos objektas išraiška ("expression"). Išraiškos sudarymas ir jos suvykdymas naudojant funkcijas <b>expression</b> ir <b>eval</b>.</li>
<li>Kalbos objektas funkcijos iškvietimas ("call"). Funkcijos <b>call</b>, <b>is.call</b>, <b>as.call</b>. Funkcijos iškvietimas naudojant <b>do.call</b>.</li>
<li>Kalbos objektas vardas ("name"). Funkcijų ir objektų vardai. Išraiškos išskaidymas į vardus.</li>
<li>Pairlist tipo objektas ir jo struktūra. Vektoriai, sąrašai ir apibendrinti sąrašai.</li>
<li>Funkcijų tipų klasifikacija: "closure", "builtin" ir "special" funkcijos. <b>.Primitive</b>, <b>.Internal</b> ir <b>.External</b> sąsajos.</li>
<li>Į baitkodą sukompiliuotos "closure" tipo funkcijos bei "generic" funkcijos ir jų metodai.</li>
<li>Aplinkos (environment): globali aplinka, paketų aplinkos, funkcijų aplinkos, funkcijų vykdymo aplinkos ir jų ryšiai.</li>
<li><em>Lexical-scoping</em> taisyklė. Taisyklės, kaip surandama funkcija ir kaip funkcija suranda kintamųjų reikšmes.</li>
</ol>
            
            
