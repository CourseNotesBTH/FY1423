# Sammanfattning

## Harmonisk svängning

Rörelse som kan beskrivas $x(t) = A\sin(\omega t + \rho)​$.

Erhålls då $F=-kx​$. 

$A​$ innebär *amplitud*, $\omega​$ *vinkelfrekvens* ($rad/s​$), $t​$ *tid* och $\rho​$ *fas* / tidsförskjutning. Det handlar alltså om något som rör sig fram och tillbaka med mjukhet.

Den konserverande kraften $F​$ har som mål att återfå rörelsen till jämviktsläge. Kraften ökar linjärt med avståndet från jämviktsläget.

Energin hos en harmonsik svängning beskrivs med sambandet  $E=\frac{kA^2}{2}​$. När massan är i jämviktsläget är energin potentiell i fjädern. I andra lägen är den kinetisk.

Frekvensen beror på vinkelfrekvens, $f=\frac{\omega}{2\pi}\text{Hz}$. Frekvensen beskriver antalet varv per sekund.

Vinkelfrekvensen kan i sin tur därför skrivas $\omega=2\pi f​$. Vinkelfrekvensen beskriver antalet delar av en hel svängning (radianer) per sekund ($r/s​$).

Vinkelfrekvensen har även ett samband med fjäderkonstanten $k$ och massan $m$ i $\omega=\sqrt{\frac{k}{m}}$. Detta samband fick vi från beviset ovan.

Svängningens periodtid beskrivs med $T=\frac{1}{f}$.

Fjäderkonstanten $k$ anges i $N/m​$.

## Dämpad svängning

Rörelse som beskrivs av $x(t)=A_0e^{-\frac{\gamma}{2}t}\sin(\omega t + \rho)$.

Erhålls då $F=-kx-bv​$.

Här innebär $\gamma​$ dämpningen, ett värde som saknar en bestämd enhet. $A_0​$ är den ursprungliga amplituden. Med dämpning menas att amplituden avtar med tiden. Värdet $b​$ beskriver den *bromsande kraften* eller *motståndskoefficienten*.

Den ursprungliga vinkelfrekvensen får samma samband som vinkelfrekvensen för harmonisk svängning - $\omega_0=\sqrt{\frac{k}{m}}​$.

Vinkelfrekvensen får istället sambandet $\omega=\sqrt{\omega_0^2-\frac{\gamma}{4}^2}​$.

För dämpningen gäller $\gamma=\frac{b}{m}$.

## Tvungen svängning

Erhålls då ett dämpat system utsätts för en extern harmonisk *kraftpåverkan* (fysikers termer) eller *störning* (civilingenjörers termer). 

Uttrycks $F=-kx-bv+F_0\sin(\mu t)​$.

Här är $F_0​$ kraftamplituden och $\mu​$ vinkelfrekvens likt $\omega​$. Man använder $\omega​$ alternativt $\omega_0​$ för att uttrycka systemets frekvens och $\mu​$ för att beskriva den *tvingande frekvensen*.

Inom mekaniska system är man nästan alltid intresserad av jämviktsläget, men sällan vad som händer första millisekunderna. Vi kan alltså försumma en homogen lösning. Vi säger därför att $x(t)=x_p(t)​$. I tidigare svängningar har vi enbart tagit hänsyn till den homogena lösningen.

Svängningen beskrivs med funktionen $x(t)=A(\mu)\sin(\mu t + \rho)​$. Här innebär $A(\mu)​$ respons och $\rho​$ fasskillnaden mellan störning och svängning.

När $\mu​$ går mot noll blir responsen låg, men den går inte mot noll. När $\mu​$ växer och går mot oändligheten går dock responsen mot noll. Detta kallas *osynlighetsområdet*. 

För amplituden gäller $A=\frac{C}{\sqrt{(\omega_0^2-\mu^2)^2+\gamma^2\mu^2}}$. För fjädrar gäller $C=\frac{F_0}{m}$.

Energin $E=E_0e^{-\gamma t}​$.

## Resonans

Resonans vid $\mu=\omega_0, \omega_0=\sqrt{\frac{k}{m}}$.

Kvalitetsfaktorn $Q=\frac{\omega_0}{\gamma}$ svarar på frågan "är systemet känsligt för interferens?". Lågt $Q$ ges av ett mindre känsligt system, ett högt $Q$ innebär ett mer känsligt system.

$E_{res}=\frac{D}{\gamma^2 \omega_0^2}$

TODO: responskurva

## Vågor

Vågfunktion $s(r, t)=A(r)\sin(\omega t -kr+\rho)$.

Vågtal $k=\frac{2\pi}{\lambda}$.

Vågfart $u=\frac{\omega}{k}=\lambda f$.

Våglängden $\lambda$ är avståndet mellan två vågtoppar.

Vidare gäller $\ddot{S}=u^2s''$ för alla vågor där $\ddot{S}$ är tidsderivata för $S$ och $s''$ är $x$-derivata för $s$. Vidare är $u$ vågfarten.

$I_u​$ betecknar intensiteten en meter från källan. $A_u​$ betecknar amplituden en meter från källan.

### Vågor i en dimension

$S(r, t)= A_u\sin(\omega t-kr+\rho)$.

$A(r)=A_u​$.

För dämpat fall gäller $A=A_ue^{-\alpha(r-1)}​$

För snöre gäller $u=\sqrt{\frac{T}{\rho}}​$   där $T​$ står för *tension* och $\rho​$ för densitet. För snöre gäller $\rho=\frac{m}{l}​$.

### Vågor i två dimensioner

$S(r, t)=\frac{A_u}{\sqrt{r}}\sin(\omega t-kr+\rho)​$.

$A(r)=\frac{A_u}{\sqrt{r}}​$

$I=\frac{I_u}{r}$. Intensiteten är i detta fall effekt per area, $I=\frac{P}{r^2}$.

För ljud så är $A_u​$ samma sak som *tryckamplitud*.

Generellt gäller i två dimensioner att vågen varar länge.

##### Dämpat fall

$S(r, t)=\frac{A_u}{\sqrt{r}}e^{-\alpha(r-1)}\sin(\omega t-kr+\rho)​$.

För dämpat fall gäller $A=e^{-\alpha(r-1)}​$.?????

### Vågor i tre dimensioner

$S(r, t)=\frac{A_u}{r}\sin(\omega t-kr+\rho)$.

$A(r)=\frac{A_u}{r}$ där $A_u=A​$ vid en meter från källan.

$I=\frac{I_u}{r^2}$

$I=\frac{P}{4\pi r^2}$ (effekt per volym).

Generellt gäller i tre dimensioner att vågen är kortvarig.

#### Dämpat fall

$S(r,t)=\frac{A_u}{r}e^{-\alpha(r-1)}\sin(\omega t-kr+\rho)$.

För dämpat fall gäller $A=e^{-\alpha(r-1)}​$.????

### Interferens

Vi begränsar oss till vågor som svänger i fas.

![Untitled Diagram](/Users/alexgustafsson/Dropbox/Skola/Fysik 2/Untitled Diagram.png)

$\Delta r=|r_2-r_1|$

Amplituden för varje punkt ges av $A(\Delta r)=\sqrt{A_1^2+A_2^2+2A_1A_2\cos(k\Delta r)}$ där $k$ är vågtalet.

Vid positiv interferens gäller $A=A_1+A_2\iff\Delta r=n\lambda​$

Vid negativ interferens gäller $A=|A_2-A_1|\iff\Delta r=n\lambda+\frac{\lambda}{2}​$

### Stående våg

Interferens längs en linje mellan källorna. Vid reflektion möts två likadana vågor, varvid en stående våg uppstår. Vi begränsar oss inte längre till vågor som svänger i fas.

$S_1=A_1\sin(\omega t-kr)$ och $S_2=A_2\sin(\omega t + k(r-L)+\rho)$ där vi använder $r-L$ för att nollställa $S_2$s origo till punkten $L$. Konstanten $\rho$ betecknar här fasskillnaden. 

Vågen i en punkt längs linjen ges av $S_f=S_1+S_2=A\sin(\omega t + \delta)​$.

$A(r)=\sqrt{A_1^2+A_2^2+2A_1A_2\cos(2kr)}$

$\delta=\arctan\big(\frac{(A_1+A_2)\cos(kr+\frac{\theta}{2})}{(A_2-A_1)\sin(kr+\frac{\theta}{2})}\big)​$

$\theta=\rho-kL​$

Med **bukar** menas punkter där vågen svänger som mest ($S_f=0​$, i $A​$ gäller $\cos=\pm 1​$). Med **noder** menas punkter som inte svänger alls (i $A​$ gäller $\cos=0​$). Avståndet mellan bukar är $\frac{\lambda}{2}​$. Mellan bukar finns en nod.

För två vågkällor som svänger i fas finns alltd en buk mitt mellan vågkällorna.

### Toner

Återkommande reflektion.

Vid lika sidor gäller $L=\frac{n\lambda}{2}$ där $L$ är den inneslutande längden. $f=\frac{u}{2Ln}$.

Vid olika sidor gäller $L=\frac{n\lambda}{2}+\frac{\lambda}{4}​$

TODO: buk, hårda?

### Dopplereffekten

$f_m=\frac{u-v_m}{u-v_s}f_s$ där $_m$ är mottagare och $_s$ sändare

Positiv med signalens riktning gentemot mottagaren (minus kvar i formeln).

## Toppvinkel

TODO: bild här

$\Theta=2\arcsin(\frac{u}{v})$

## Kärnfysik

### Termer

**Atomnummer** ($z$) - antal protoner - ämnet ("alla atomer med kärnor som har 26 protoner är järn").

**Protoner** - laddade med $+1e$ (lika många elektroner som protoner).

**Masstal** ($m$) - antal protoner + neutroner (nukleoner). Förklarar vilken isotop det rör sig om. Det finns ungefär 90 stabila ämnen - många fler isotoper.

**Beteckna isotop** - $^7\text{Li}$ är en isotop av litium (atomnummer 3) som har 4 neutroner). $^{58}\text{Fe}​$ är en isotop av järn (atomnummer 26) som har 32 neutroner.

## Strålning

$E_{tot}=\Delta m*c^2​$

$1\;\text{eV}=1.602*10^{-19}\;\text{J}$

$1\;\text{u}=1.6605402*10^{-27}\;\text{kg}$

TODO: infoga bild över instabil och stabil kärna

### Alfastrålning

En alfapartikel består av 2 protoner och 2 neutroner - $^4\text{He}$. Alfastrålning är den minst farliga strålningen utanför kroppen, men den mest farliga inuti.

$E_\alpha = \underbrace{E_{k\alpha}}_\text{kinetisk energi}+\underbrace{E_{0\alpha}}_{viloenergi}$.

$E_{0\alpha}=3.72738\;\text{GeV}$

$E_0=m_0c^2$

$_z^m\text{A}\rightarrow\ ^{m-4}_{z-2}\text{B}+\ ^4_2\text{He}$

TODO: infoga spektrum här.

### Betastrålning

$_z^m\text{A}\rightarrow\ ^{m}_{z\pm1}\text{B}+e^\pm+\stackrel{\text{(-)}}{\cup}$

$^m_{z\pm1}\text{B}$ och $e^\pm$ har motsatt laddning. Neutrinon $\stackrel{\text{(-)}}{\cup}$ har samma laddning som elektronen.

TODO: infoga spektrum här

### Relativitetsteorin

Den relativistiska kinetisk energin $E_k=(\gamma-1)E_0$ där $E_0=mc^2$, gammafaktorn $\gamma=\frac{1}{\sqrt{1-r^2}}$ och rapiditeten $r=\frac{v}{c}​$.

## Fission

TODO: infoga bild över fission här

En kärna delas i två eller fler dotterkärnor. Spontan fission sker från ett grundtillstånd. Stimulerad fission sker från ett eciterat tillstånd - exempelvis neutroninducerat.

Antal reaktioner i en viss isotop med massan $M(^mA)​$ för en viss massa $m​$ är $\frac{m}{M(^mA)}​$. Exempelvis är antalet reaktioner för $1\;\text{kg}​$ $^2H​$ med massan $M(^2H)=2.014102​$ $ n=\frac{1}{2.1014102\;\text{u}}=2.866*10^{26}\;\text{st}​$.

**Uran**:

$^{235}\text{u}+n\rightarrow\ ^{236}\text{u}*\rightarrow\text{massa kärnor}+\text{neutroner}+\text{energi}​$

I snitt $215 MeV​$ och $2.4​$ neutroner.

**Plutonium**:

$^{239}\text{Pu}+n\rightarrow\ ^{240}\text{Pu}*\rightarrow\text{massa kärnor}+\text{neutroner}+\text{energi}$

## Fusion

Två kärnor "smälter" samman till en.

**PP-kedjan**
$$
\begin{align}{}
p+p\rightarrow\ ^2\text{He}\stackrel{\beta}{\rightarrow}\ ^2\text{H}&\\
&\rightarrow\ ^4\text{He}\\
p+p\rightarrow\ ^2\text{He}\stackrel{\beta}{\rightarrow}\ ^2\text{H}&
\end{align}
$$
**CNO-cykeln**
$$
\underbrace{^{12}\text{C}}_\text{stabil}+4p\rightarrow\ \underbrace{^{13}\text{N}}_\text{instabil}+3p\stackrel{\beta}{\rightarrow}\ \underbrace{^{13}\text{C}}_\text{instabil}+3p\rightarrow\ \underbrace{^{14}\text{N}}_\text{stabil}+2p\rightarrow\ \underbrace{^{15}\text{O}}_\text{instabil}+p\stackrel{\beta}{\rightarrow}\ ^{15}\text{N}+p\rightarrow\ ^{16}\text{O}*\stackrel{\alpha}{\rightarrow}\ ^{12}\text{C}+\ ^4_2\text{He}
$$


## Gaslagen

$PV=nRT​$ där $n​$ är antal mol

$PV=Nk_BT​$ där $N​$ är antal partiklar och $k_B​$ är Boltzmanns konstant

Med *adiabatisk* menas att inget är konstant.

*Isoterm* innebär att temperaturen är konstant, vilket innebär att $PV​$ är konstant. TODO: infoga bild här. $\Delta E=P_iV_i*ln(\frac{V_B}{V_A})​$

*Isobar* innebär att trycket är konstant, vilket innebär att $\frac{V}{T}$ är konstant. TODO: infoga bild här. $\Delta E=P\Delta V$

*Isokor* innebär att volymen är konstant vilket innebär att $\frac{P}{T}$ är konstant. TODO: infoga bild här. $\Delta E=0$

Energin per partikel varierar. För en atom gäller $E=\frac{3}{2}k_BT​$. För två atomer gäller $E=\frac{5}{2}k_BT​$. För tre atomer gäller $E=3k_BT​$. Allitd gäller $\frac{mv^2}{2}=\frac{3}{2}k_BT​$.

## Reflektion

Effekten vid reflektion genom flera **av samma** medium $P=T^nP$  där $T=1-R$

### Ljud

Reflektansen $R=\big(\frac{Z_2-Z_1}{Z_2+Z_1}\big)^2$ där $Z=\rho*u$ där $\rho$ är densiteten och $u$ ljudets hastighet för ett vist medium.

Hastigheten $u=\frac{Z}{\rho}$ där $Z​$ är den akustiska impedansen för ett visst medium.

### Ljus

Reflektansen $R=\big(\frac{n_2-n_1}{n_2+n_1}\big)^2$ där brytningsindexet $n=\frac{c}{u}$

Brewstervinkeln: Vid $\Theta_B​$ (Brewstervinkeln) blir allt reflekterat ljus polariserat.
