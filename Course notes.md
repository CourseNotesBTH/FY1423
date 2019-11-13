# Fysik 2

## Vecka 1

### Harmonisk svängning

#### Definition

Rörelse som kan beskrivas $x(t) = A\sin(\omega t + \rho)$.

Erhålls då $F=-kx$.

$A$ innebär *amplitud*, $\omega$ *vinkelfrekvens* ($rad/s$), $t$ *tid* och $\rho$ *fas* / tidsförskjutning. Det handlar alltså om något som rör sig fram och tillbaka med mjukhet.

Den konserverande kraften $F​$ har som mål att återfå rörelsen till jämviktsläge. Kraften ökar linjärt med avståndet från jämviktsläget.

Energin hos en harmonsik svängning beskrivs med sambandet  $E=\frac{kA^2}{2}$. När massan är i jämviktsläget är energin potentiell i fjädern. I andra lägen är den kinetisk.

#### Bevis för den konserverande kraften

$$
\begin{array}{l}
F=-kx\\
ma=-kx\\
\end{array}
\tag{1}
\phantom{0000000000}
$$

$$
\begin{array}{l}
a=\frac{dv}{dt}\equiv\dot{v}\\
v=\frac{dx}{dt}\equiv\dot{x}\\
\dot{v}\equiv\ddot{x}\\
\end{array}
\tag{2}
\phantom{0000000000}
$$

$$
\begin{array}{l}
m\ddot{x}=-kx\\
m\ddot{x}+kx=0\\
\ddot{x}+\frac{k}{m}x=0\\
r^2+\frac{k}{m}=0\\
r=\pm\sqrt{-\frac{k}{m}}=\pm\sqrt{\frac{k}{m}}i
\end{array}
\tag{3}
$$

$$
\begin{array}{}
x(t)=A\sin(\sqrt{\frac{k}{m}}t+\rho)\\
\omega=\sqrt{\frac{k}{m}}\\
x(t)=A\sin(\omega t + \rho)
\end{array}
\tag{4}
$$



Vid steg 1 använder vi Newtons andra lag för att sätta $F=ma$.

I det andra steget använder vi sambandet mellan sträcka, hastighet och acceleration. Notera att med $\dot{x}$ menas derivatan av $x$ med hänseende på tid - tidsderivatan. $\ddot{x}$ innebär alltså andraderivatan med hänseende på tid.

I det tredje steget löser vi differentialekvationen genom att sätta upp en karakteristisk ekvation. Vi vet att om den karakteristiska ekvationen ger $r=\alpha\pm i \Beta$ är lösningen $y=Ae^{ax}\sin(\Beta x+\rho)$.

I det fjärde steget använder vi lösningen och utför bytet till $\omega$. Slut på bevis.

#### Bevis för energin

Vi utnyttjar att derivatan av kraften $F$ är derivatan av energin $E$ med hänseende på sträckan $x$.
$$
dE=F*dx=kxdx\\
E=\int_0^Akxdx=\Big[\frac{kx^2}{2}\Big]_0^A=\frac{kA^2}{2}
$$

#### Samband

Frekvensen beror på vinkelfrekvens, $f=\frac{\omega}{2\pi}\text{Hz}$. Frekvensen beskriver antalet varv per sekund.

Vinkelfrekvensen kan i sin tur därför skrivas $\omega=2\pi f$. Vinkelfrekvensen beskriver antalet delar av ett helt varv (radianer) per sekund ($r/s$).

Vinkelfrekvensen har även ett samband med fjäderkonstanten $k$ och massan $m$ i $\omega=\sqrt{\frac{k}{m}}$. Detta samband fick vi från beviset ovan.

Svängningens periodtid beskrivs med $T=\frac{1}{f}$.

Fjäderkonstanten $k$ anges i $N/m$.

#### Exempel

##### 1

Ett flöte guppar upp och ned harmoniskt. Det svänger $10\text{cm}$ mellan vändlägena. Vid $t=0$ är flötet $2\text{cm}$ över jämviktsläget och på väg upp. För flötet gäller $f=5\text{Hz}$.

Vart är flötet efter $0.11\text{s}$?

**Lösning:**
$$
A=5\text{cm}\\
x(t)=5\sin(\omega t + \rho)
\\\ \\
\omega=2\pi f =10\pi≈31.4\;r/s\\
x(t)=5\sin(31.4t+\rho)
\\\ \\
x(0)=2\Rightarrow 2=5\sin(\rho)\\
\rho_1=\arcsin(\frac{2}{5})=0.412\\
\rho_2=\pi-\rho_1=2.714
$$
Vi har från uppgiften att flötet är påväg upp. Vi noterar att $0\leq\rho_1\leq\frac{\pi}{2}$ vilket innebär att den är mellan jämviktsläget och på väg uppåt mot det maximala värdet för sinus ($\frac{\pi}{2}$). Samma test för $\rho_2$ ger oss $\frac{\pi}{2}\leq\rho_2\leq\pi$ vilket innebär en rörelse från maximalt värde ned mot jämviktsläget igen. Vårt enda värde för $\rho$ är alltså $\rho=\rho_1=0.412$.

Vi får funktionen $x(t)=5\sin(31.4t+0.412)$ och sätter in $t=0.11$ vilket ger oss $x(0.11)=-3.3\text{cm}$.

Svar: $-3.3\text{cm}$.

##### 2

En massa påverkas av en fjäder med en kraft på $F=-80x$. Massan svänger med $3.18\text{Hz}$.

Hur stor är massan?

**Lösning:**

Vi utnyttjar sambandet $\omega=2\pi f$ och och får då $\omega=2\pi*3.18=19.98\;r/s$. För att hitta massan använder vi sambandet $\omega=\sqrt{\frac{k}{m}}$ och bryter ut $m$ genom $m=\frac{k}{\omega^2}=\frac{80}{19.98^2}=0.200\text{kg}=200\text{g}$.

Svar: $200\text{g}$.

##### 3

En massa hänger i en fjäder med fjäderkonstanten $k=122\;N/m$. Fjädern absorberar $50\;J$.

Vad blir avståndet mellan vändningarna?

**Lösning:**

Vi utnyttjar sambandet $E=\frac{kA^2}{2}$. Vi vet att $E=50$ och får då $50=\frac{2.5A^2}{2}$. Vi bryter ut $A$ till $\sqrt{\frac{2*50}{122}}=0.905\;\text{m}$. Sträckan mellan vändlägena är $2A$ vilket i vårt fall innebär ett avstånd på $1.81\;\text{m}$.

Svar: $1.81\;\text{m}$.

### Matematisk pendel

#### Definition

En pendel då approximativa $\theta$ är mycket litet.

#### Samband

Vinkelhastigheten har sambandet $\omega=\sqrt{\frac{g}{L}}$. Om vinkeln $\theta$ blir för stor stämmer detta alltså inte, per definition.

#### Bevis

![matematisk pendel](/Users/alexgustafsson/Dropbox/Skola/Fysik 2/matematisk pendel.png)
$$
F=-mg\sin(\theta)\tag{1}
\phantom{0000000000}
$$

$$
\sin(\theta)=\theta-\frac{\theta^3}{\theta!}+\frac{\theta^5}{5!}+...\tag{2}
\phantom{0}
$$

$$
\begin{array}{}
F=-mg\theta\\
s=\theta*L\Rightarrow\theta=\frac{s}{L}\\
f=-\frac{mg}{L}s
\end{array}
\tag{3}
\phantom{0000000}
$$

$$
\begin{array}{}
F&=-\underbrace{\frac{mg}{L}}_{k}x\\
\omega&=\sqrt{\frac{k}{m}}=\sqrt{\frac{\frac{mg}{L}}{m}}=\sqrt{\frac{g}{L}}
\end{array}
\tag{4}
$$

I steg 1 använder vi den vanliga metoden för komposantuppdelning för att uttrycka $F$.

I steg 2 ersätter vi $\sin(\theta)$ med MacLaurin-polynomet för sinus.

I steg 3 utnyttjar vi definitionen för att avgränsa oss till endast små värden för $\theta$. För dessa kommer de övriga faktorerna att bli så pass små att vi kan säga att $\sin(\theta)=\theta$. Vi uttrycker pendelns rörelse som $s$ med amplituden $L$. Vi får därigenom ett uttryck för $\theta$ baserat på dessa två värden. Vi har även ett liknande uttryck här för $f=-kx$.

I steg 4 använder vi vår nya kunskap och ersätter $-\frac{mg}{L}$ med fjäderkonstanten $k$. Vi kan då slutligen uttrycka $\omega$ som ett samband för gravitationskonstanten $g$ och amplituden (pendelns längd) $L$. Slut på bevis.

### Dämpad svängning

#### Definition

Rörelse som beskrivs av $x(t)=A_0e^{-\frac{\gamma}{2}t}\sin(\omega t + \rho)$.

Erhålls då $F=-kx-bv$.

Här innebär $\gamma$ dämpningen, ett värde som saknar en bestämd enhet. $A_0$ är den ursprungliga amplituden. Med dämpning menas att amplituden avtar med tiden. Värdet $b$ beskriver den *bromsande kraften* eller *motståndskoefficienten*.

#### Samband

$\omega=\sqrt{\omega_0^2-\frac{\gamma^2}{4}}$.

$A=A_0e^{-\frac{\gamma}{2}t}$.

#### Bevis

$$
\begin{array}{}
F=-kx-bv\\
ma=-kx-bv
\end{array}
\tag{1}
$$

$$
\begin{array}{}
a=\frac{dv}{dt}=\frac{d^2x}{dt^2}=\ddot{x}\\
v=\frac{dx}{dt}=\dot{x}
\end{array}
\tag{2}
$$

$$
\begin{array}{}
m\ddot{x}=-kx-b\dot{x}\\
m\ddot{x}+b\dot{x}+kx=0\\
\ddot{x}+\frac{b}{m}\dot{x}+\frac{k}{m}x=0
\end{array}
\tag{3}
$$

$$
\begin{array}{}
\gamma\equiv\frac{b}{m}\\
\omega_0^2=\frac{k}{m}
\end{array}
\tag{4}
$$

$$
\begin{array}{}
\ddot{x}+\gamma\dot{x}+\omega_0^2x=0\\
r^2+\gamma r+\omega_0^2x=0\\
r=\frac{\gamma}{2}\pm\sqrt{\frac{\gamma^2}{4}-\gamma_0^2}
\end{array}
\tag{5}
$$

Om $\frac{\gamma^2}{4}-\omega_0^2>0$ är både $r=r_1,r_2$ reella och $x=Ae^{r_1t}+Be^{r_2}$. Det uppstår då ingen svängning. Vi bortser från sådana fall då detta inte är en dämpad svängning, utan snarare en *överdämpad* svängning.

Om $\frac{\gamma^2}{4}-\omega_0^2=0$ har vi en dubbelrot som ger oss $x=(Ae^r+B)e^{rt}. Det uppstår här inte heller någon svängning. Vi bortser från sådana fall då detta rör sig om *kritisk* dämpning.

Det enda fallet vi bryr oss om är om $\frac{\gamma^2}{4}-\omega^2_0 < 0$ och då är lösningen $r=-\frac{\gamma}{2}\pm\sqrt{\omega_0^2-\frac{\gamma^2}{4}}i$.
$$
\begin{array}{}
r=a\pm bi\\
y=Ae^{ax}\sin(bx+\rho)
\end{array}
\tag{6}
$$

$$
\begin{array}{}
x(t)=A_0e^{-\frac{\lambda}{2}t}\sin(\underbrace{\sqrt{\omega_0^2-\frac{\gamma^2}{4}}}_\omega t+\rho)\\
x(t)=A_0e^{-\frac{\lambda}{2}t}\sin(\omega t + \rho)
\end{array}
\tag{7}
$$

Vid steg 1 använder vi Newtons andra lag för att sätta $F=ma$.

I det andra steget använder vi sambandet mellan sträcka, hastighet och acceleration. Notera att med $\dot{x}$ menas derivatan av $x$ med hänseende på tid - tidsderivatan. $\ddot{x}$ innebär alltså andraderivatan med hänseende på tid.

I det tredje steget löser vi differentialekvationen genom att sätta upp en karakteristisk ekvation.

I det fjärde steget definierar vi att dämpningen $\gamma$ ska ha ett samband med den bromsande kraften $b$ och massan $m$. Vi använder sambandet från harmonisk svängning och beskriver $\omega_0^2$.

I steg fem löser vi den karakteristiska ekvationen. Vidare såg vi att det enda fall då vi har en dämpad svängning är då $\frac{\gamma^2}{4}-\omega^2_0 < 0$.

I steg sex skriver vi slutligen funktionen av lösningen från tidigare steg.

I det sista steget gör vi bytet till $\omega$ för att slutföra vårt bevis. Vi får då även sambandet för $\omega=\sqrt{\omega_0^2-\frac{\gamma^2}{4}}$.

#### Exempel

##### 1

En $500\;g$ boll gungar i en fjäder med fjäderkonstanten $k=5.85\;N/m$. Luftmotståndskoefficienten på bollen är $0.72\;Ns/m$.

**A** Vad är svängningsperioden för bollen?

**Lösning:**

Vi vill få fram perioden $T=\frac{1}{f}$ för svängningen där $f=\frac{\omega}{2\pi}$. För detta behöver vi bestämma $\omega$ och därför även $\omega_0$ och $\gamma$.

Vi utför beräkningen $\omega_0=\sqrt{\frac{k}{m}}=\frac{5.85}{0.500}=3.42\;r/s$ och $\gamma=\frac{b}{m}=\frac{0.72}{0.500}=1.44$. Nu kan vi beräkna $\omega=\sqrt{\omega_0^2-\frac{\gamma^2}{4}} = \sqrt{3.42^2-\frac{1.44}{4}}=3.34\;r/s$ .

Vi kan kontrollera genom att se att $\omega$ varken är $0$ eller imaginärt vilket innebär att den svänger.

Till slut kan vi se att $T=\frac{\frac{1}{\omega}}{2\pi}=\frac{\frac{1}{3.34}}{2\pi}=1.88\;s$.

Svar: $1.88\;s$.

**B** Efter hur lång tid har amplituden halverats?

**Lösning**:

Vi söker $t​$ då $A=\frac{A_0}{2}​$. Vi kan uttrycka $A=A_0e^{-\frac{1.44}{2}t}​$. Då vi har halva amplituden kan vi uttrycka $\frac{A_0}{2}=A_0e^{-0.72\tau}​$. Man brukar som här använda $\tau​$ för att uttrycka halveringstiden.

Vi förkortar tidigare uttryck med $A_0$ på båda sidor och får $\frac{1}{2}=e^{-0.72\tau}$. Vi förenklar vidare genom att invertera bägge led, $2=e^{0.72\tau}$. Nu kan vi enkelt bryta ut $\tau$ till $\tau=\frac{\ln{2}}{0.72}=0.96\;s$.

Svar: $0.96\;s$.

**C** Efter hur lång tid har energin halverats?

**Lösning:**

Vi söker $t$ då $E=\frac{E_0}{2}$. För $E$ gäller $E=\frac{kA^2}{2}$ och för $A$ gäller $A=A_0e^{-\frac{\gamma}{2}t}$. Vi kan då uttrycka energin som $E=\frac{A_0e^{-\frac{\gamma}{2}t}}{2}=\underbrace{\frac{kA_0^2}{2}}_{E_0}*e^{-\gamma t}=E_0e^{-\gamma t}$. Med hjälp av värdet för $\gamma$ från tidigare lösning kan vi beskriva $E$ som $E=E_0e^{-1.44}t$. För halva energin gäller då uttrycket $\frac{E}{2}=E_0e^{-1.44\tau}$. Vi bryter likt föregående uppgift ut $\tau$ och får $\tau=\frac{\ln 2}{1.44}=0.48\;s$.

Svar: $0.48\;s$.

### Tvungen svängning

Erhålls då ett dämpat system utsätts för en extern harmonisk *kraftpåverkan* (fysikers termer) eller *störning* (civilingenjörers termer).

Uttrycks $F=-kx-bv+F_0\sin(\mu t)$.

Här är $F_0$ kraftamplituden och $\mu$ vinkelfrekvens likt $\omega$. Man använder $\omega$ alternativt $\omega_0$ för att uttrycka systemets frekvens och $\mu$ för att beskriva den *tvingande frekvensen*.

Inom mekaniska system ärman nästan alltid intresserad av jämviktsläget, men sällan vad som händer första millisekunderna. Vi kan alltså försumma en homogen lösning. Vi säger därför att $x(t)=x_p(t)$. I tidigare svängningar har vi enbart tagit hänsyn till den homogena lösningen.

Svängningen beskrivs med funktionen $x(t)=A(\mu)\sin(\mu t - \alpha)$. Här innebär $A(\mu)$ respons och $\alpha$ fasskillnaden mellan störning och svängning.

Nedan visas en responskurva. När $\mu$ går mot noll blir responsen låg, men den går inte mot noll. När $\mu$ växer och går mot oändligheten går dock responsen mot noll. Detta kallas *osynlighetsområdet*.

![responskurva](/Users/alexgustafsson/Dropbox/Skola/Fysik 2/responskurva.png)

#### Bevis

$$
F=-kx-bv+F_0\sin(\mu t)
\tag{1}
$$

$$
\begin{array}{}
ma=-kx-bv+F_0\sin(\mu t)\\
m\ddot(x)=-kx-b\dot{x}+F_0\sin(\mu t)\\
m\ddot{x}+b\dot{x}+kx=F_0\sin(\mu t)
\ddot{x}+\frac{b}{m}\dot{x}+\frac{k}{m}x=\frac{F_0\sin(\mu t)}{m}\\
\ddot{x}+\gamma\dot{x}+\omega_0^2x=\frac{F_0}{m}\sin(\mu t)
\end{array}
\tag{2}
$$

$$
\begin{array}{}
x_p=x=A\sin(\mu t - \alpha)\\
\dot{x}=\mu A \cos(\mu t - \alpha)\\
\ddot{x}=-\mu^2\underbrace{A\sin(\mu t - \alpha)}_x=-\mu^2x
\end{array}
\tag{3}
$$

$$
\begin{array}{}
-u^2x+\gamma\dot{x}+\omega_0^2x=\frac{F_0}{m}\sin(\mu t)\\
(\omega_0^2-\mu^2)x+\gamma\dot{x}=\frac{F_0}{m}\sin(\mu t)\\
(\omega_0^2-\mu^2)A\sin(\mu-\alpha)+\gamma\mu A\cos(\mu t - \alpha)=\frac{F_0}{m}\sin(\mu t)\\
\end{array}
\tag{4}
$$

$$
\begin{array}{}
y=A\sin(x+\rho)=A\cos(\rho)\sin(x)+A\sin(\rho)\cos(x)=a\sin(x)+b\cos(x)\\
\frac{b}{a}=\frac{sin(\rho)}{\cos(\rho)}=\tan{\rho}\Rightarrow\rho=\arctan(\frac{b}{a})\\
a^2+b^2=A^2\Rightarrow a=\sqrt{a^2+b^2}\\
\underbrace{A\big((\omega_0^2-\mu^2)^2+\gamma^2\mu^2\big)^\frac{1}{2}}_{=\frac{F_0}{m}\text{ ty samma amplitud}}\sin(\mu t-\underbrace{\alpha+\arctan(\frac{\gamma \mu}{\omega_0^2-\mu^2})}_{=0\text{ ty samma fas}})=\frac{F_0}{m}\sin(\mu t)\\
A=\frac{F_0}{m}\big((\omega_0^2-\mu^2)^2+\gamma^2\mu^2\big)^{-\frac{1}{2}}\\
\alpha=\arctan(\frac{\gamma\mu}{\omega_0^2-\mu^2})
\end{array}
\tag{5}
$$

I steg 1 utgår vi från definitionen för tvungen svängning.

Steg 2 utnyttjar Newtons andra lag för att skriva om kraften.

I steg 3 ansätter vi ett värde för $x$. Då vi har sinus i högerledet måste det även finnas i vår ansättning.

I steg 4 utnyttjar vi vår ansättning och skriver om uttrycket.

Steg 5 utnyttjar definitionen för den dubbla vinkeln för att skriva om en blandning av sinus och cosinus till en funktion som enbart använder sinus, likt det vi söker för harmonisk svängning. Slutligen kommer vi fram till två ytterligare samband som vi kan använda.

#### Samband

$A(\mu)=\frac{F_0}{m\big((\omega_0^2-\mu^2)^2+\gamma^2\mu^2\big)^\frac{1}{2}}=\frac{C}{\big((\omega_0^2-\mu^2)^2+\gamma^2\mu^2\big)^\frac{1}{2}}$. I det andra fallet har vi helt enkelt bytt ut $\frac{F_0}{m}$ mot en annan konstant $C$.

$\alpha=\arctan(\frac{\gamma\mu}{\omega_0^2-\mu^2})$.

För energin gäller $E=\frac{kA^2}{2}=\frac{kC^2}{2\big((\omega_0^2-\mu^2)^2+\gamma^2\mu^2\big)}=\frac{D}{(\omega_0^2-\mu^2)^2+\gamma^2\mu^2}$.

#### Exempel

##### 1

![exempel](/Users/alexgustafsson/Dropbox/Skola/Fysik 2/exempel.png)

Anta att följande är känt $F_0=7\sin(\mu t)\;kN$, $m=0.25\;kg$, $k=10000$ och $\gamma=10$.

Vad är amplituden för låga frekvenser (nära noll)?

**Lösning**
$$
A=\frac{F_0}{m\sqrt{\omega_0^4}}=\frac{F_0}{m\omega_0^2}=\frac{F_0}{m\frac{k}{m}}=\frac{F_0}{k}=\frac{7000}{10000}=70\;cm
$$

##### 2

Vi har en maskin. Vi vet att $\omega_0=800\;r/s$. $A(600)=0.025\;mm$ och den absorberade energin $E(600)=20\;J$ och $\gamma=20$.

**A** Om störningen i maskinen stängs av efter att den störts med $\mu=600\;r/s​$, hur mycket energi är kvar efter $1\;s​$?

**Lösning**

Vi använder $E=E_0e^{-\gamma t}$ för att bestämma $E=20*e^{-20*1}=4.10*10^{-8}=41.2\;nJ$.

Svar: $41.2\;nJ$.

**B** Bestäm energin och amplitud vid $\mu=700\;r/s$.

**Lösning**

$A(600)=25\;\mu m=2.5*10^{-5}\;m$. Från detta kan vi ställa upp $2.5*10^{-5}=\frac{C}{\big((800^2-600^2)^2+20^2*600^2\big)^\frac{1}{2}}$ . Vi kan då bryta ut $C$ till $C=2.5*10^{-5}\big((800^2-600^2)^2+20^2*600^2\big)^\frac{1}{2}=7.00$. Vi kan nu beräkna $A(700)$ genom att sätta in vårt tidigare obekanta $C$.

$A(700)=\frac{7.00}{\big((800^2-700^2)^2+20^2*700^2\big)^\frac{1}{2}}=4.65*10^{-5}=46.5\;\mu m$. För energin gör vi en liknande uträkning men för uttrycket som finns för energin.
$$
\begin{align}
E(600)=20\;J\Rightarrow D&=E(600)*\big((\omega_o^2-\mu^2)^2+\gamma^2\mu^2\big)\\
&=20*\big((800^2-600^2)^2+20^2*600^2\big)\\
&=1.57*10^{12}\;J
\end{align}\\
\;\\
E(700)=\frac{1.57*10^{12}}{(800^2-700^2)^2+20^2*700^2}=69.2\;J
$$

### Resonans

#### Definition

Erhålls då $\mu=\omega_0$.

#### Samband

Resonansamplitud hittas genom att sätta in $\mu=\omega_0$ i $A(\mu)$ för att få $A_{\text{res}}=\frac{F_0}{m\gamma\omega_0}$ för fjädrar eller $A_{\text{res}}=\frac{c}{\gamma\omega_0}$för svårare system.

#### Exempel

Vi har givet $\omega_0=200\;r/s$, $\gamma=10$, $m=0.25$ och $F_0=7000$.

Resonansamplituden $A_\text{res}$ fås då genom $A_\text{res}=\frac{7000}{0.25*700*10}=\frac{3.5}{0.25}=14\;m$.

Svar: $14\;m$.

### Responskurva

![image-20181121181242679](/Users/alexgustafsson/Library/Application Support/typora-user-images/image-20181121181242679.png)

Om vi ritar ett diagram och låter x-axeln vara $\mu$ och y-axeln energin $E$ så får vi en graf som nästan påminner om den som ovan. Det maximala värdet är resonansenergin $E_{res}$. Hälften av $E_{res}$, alltså $\frac{E_{res}}{2}$ skär funktionen i två punkter. Avståndet (halvvärdesbredden) mellan dessa punkter är $\omega_{res}$. Linjen som skär funktionen där $y=E_{res}$ skär x-axeln i $\omega_0$.

Systemet blir osynligt för svängningen - den absorberar ingenting, för mycket höga $\mu$.  

En approximerad formel vi kan använda oss av är från detta $E(\mu_0\pm\frac{\gamma}{2})=\frac{E_{res}}{2}$.

### Kvalitetsfaktorn

Svarar på frågan "är mitt system känsligt för resonans?". Kvalitetsfaktorn tecknas med värdet $Q$. Ett lågt värde innebär mindre absorbering och att systemet alltså är mindre känsligt. Ett högt värde innebär mer absorbering och därmed även ett mer känsligt system.

$Q=\frac{\omega_0}{\gamma}$.

#### Exempel

Ett $8\;kg$ objekt har sluthastigheten $160\;m/s$ vid fritt fall. Detta system hängs i en fjäder med $k=435\;N/m$. Vad är kvalitetsfaktorn $Q$?.

**Lösning**

Vi kan bestämma $\omega_0=\sqrt{\frac{k}{m}}=\sqrt{\frac{435}{8}}=7.37\;r/s$. Vi vet från Newtons lagar att den resulterande kraften i ett föremål i vila är $0$. Uppåt har vi $-bv$ och nedåt $mg$.

Vi kan alltså skriva $mg=bv\Rightarrow=b=\frac{mg}{v}=\frac{8*9.82}{160}=0.491\;Ns/m$. Vilket ger oss $\gamma=\frac{b}{m}=\frac{0.491}{8}=0.0614$. Vi kan nu beräkna $Q=\frac{\omega_0}{\gamma}=\frac{7.37}{0.0614}=120$. För en fjäder anses detta vara en kvalitetsfaktor av grad medel.

Svar: $120$.

### Vågor i en dimension
