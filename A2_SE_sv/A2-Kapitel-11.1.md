## 11.1 Så fungerar drönaren

### Drönarens hjärna

Alla drönare har ett **styrsystem**. Det är den del i drönaren som närmast kan beskrivas som hjärnan. Den hanterar, tar hänsyn till och för vidare information till drönarens fartreglage för motorn för att kunna hålla stabilitet och position.  
En viktig del i styrsystemet kallas **IMU** (Inertial Measurement Unit). Det är den enhet som känner av drönarens attityd och förflyttning i förhållande till marken och som är avgörande för att drönaren ska hållas stabil.  
Två andra viktiga delar i många drönares styrsystem är **GPS-mottagaren** som beräknar drönarens position och drönarens **barometer** som kompenserar GPS-mottagarens mindre noggranna höjdberäkning för att få en ännu säkrare höjduppfattning.

![Figur 47 Styrsystem](A2_SE_sv/Figur_047.png)
Figur 47 Styrsystem

### Hur fungerar drönarens motor?

Motorns uppgift är att driva propellern som skapar lyftkraft. Genom att variera motorvarvtalet skapas exakt så mycket lyftkraft som krävs från varje enskild arm för att armarna tillsammans ska hålla drönaren i luften.

### ESC kontrollerar motorns varvtal

Drönaren har ett fartreglage, eller ESC (Electronic Speed Controller), som kontrollerar motorns varvtal. Hur ofta den kan förändra varvtalet mäts i Hz (Hertz).

### Gimbal – för stabila bilder

Drönare kan stabilisera sin kamera med hjälp av en så kallad gimbal. Den kan vara tvåaxlad eller treaxlad. Om den är tvåaxlad stabiliserar den kameran i höjd och roll. När den är treaxlad mjukar den upp rörelser om drönaren roterar runt sin egen axel.  
Gimbalen har i varje axel motorer som jobbar för att hålla den stabil mot horisonten. Motorerna är ofta ömtåliga och ska hanteras varsamt.

### Drönare med propellrar

Den vanligaste drönartypen är den helikopterliknande **multirotordrönaren**. Den kallas så eftersom den nästan alltid har fler än en propeller. Dessa drönare är ofta tillverkade i plast, men propellrarna kan i vissa fall vara gjorda av kolfiber.  
Multirotordrönare utmärker sig genom sin förmåga att hovra – och därför behöver de inte heller någon start- och landningsbana. 

![Figur 48 En drönare med fasta vingar och en multirotor](./A2_SE_sv/Figur_048.png)  
Figur 48 En drönare med fasta vingar och en multirotor

### Drönare med vingar
En typ av drönare liknar flygplan, eftersom de har **fasta vingar**. Vingarna är ofta byggda av lätta material, som frigolit, för att väga så lite som möjligt. Vingarna gör att den inte är helt beroende av den elektriska drivkraften som batterierna skapar. Den kan på så sätt öka flygtiden och dessutom hantera ett motorhaveri bättre än en multirotordrönare, som i värsta fall bara faller rakt ner mot marken.  
Till skillnad från multirotordrönare måste drönare med fasta vingar ofta kastas eller skjutas igång och dessutom landa på landningsbana.

### Hybrider med både vingar och propellrar
Drönare med vingar finns både med och utan propellrar. Även om drönare med fasta vingar kan ha en eller flera propellrar, är de som har två eller fler propellrar inte sällan **hybrider** – med egenskaper som både liknar multirotordrönare och vanliga vingdrönare. För att en drönare ska klassas som hybrid måste den gå att hovra och alltså kunna starta och landa i en vertikal rak linje (precis som multirotordrönare). Hybrider är mer vindkänsliga än multirotordrönare.

![Figur 49 Hybridvariant](./A2_SE_sv/Figur_040.png)  
Figur 49 Hybridvariant

![Transport Styrelsen](./images/Logga.png)
