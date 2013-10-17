#Open Source

#### Meðlimir þessa hóps eru: ####

 * Almar Daði Kristjánsson
 * Atli Freyr Einarsson

## 1. Linux uppsetning

**Almar**: Það eru mörg ár síðan ég setti Linux upp fyrst. Árið var 2002, ég 10 ára gamall og distroið Red Hat. Það gekk með herkjum, en einhvern veginn tókst mér að setja þetta upp í dual boot á heimilstölvuna við mismikla hrifningu annarra íbúa heimilisins. Gamanið kárnaði fljótt, tölvan þurfti straujun og ég hélt mig frá Linux um nokkurra ára skeið. Árið 2005 setti ég svo upp Ubuntu og gerði það að aðalstýrikerfinu mínu. Í vor ákvað ég að breyta til og skipti yfir í Mint. Mér líkaði Mint 14 ágætlega, það laut oftast nær vilja mínum og engin teljanleg vandræði komu upp. Síðan uppfærði ég í Mint 15. Núna upp á síðkastið hefur stýrikerfið strítt mér óþarflega mikið. Stríðni þessi felst m.a. í því að það virðist algjörum duttlungum háð hvort þráðlaus nettenging næst. Verri þykir mér þó sú tilhneiging tölvunnar að ræsa stundum ekki sem skyldi. Stundum sýnir skjárinn orðarunur flæða til allra átta, upp og niður, og Linux Mint logoið hoppandi í forgrunni. Þegar verst lætur birtist ekkert nema truflanir. Þetta á líka til að gerast þegar drepið er á tölvunni. Til stendur að kippa þessu ástandi í liðinn núna um helgina, en vegna þessara hvimleiðu kringumstæðna tek ég mér það bessaleyfi að birta hér mynd af tölvunni minni ræstri — en ekki að ræsa. Á henni getur að líta nákvæmlega þetta skjal, opið í Vim og gluggakerfið er i3. 

![Linux Mint 15](http://i.imgur.com/eX5Riul.jpg)    

**Atli**: 
Ég byrjaði á því að setja upp Linux Mint í dual-boot ásamt Win7 á tölvuna mína fyrir u.þ.b. mánuði síðan. Það gekk vel og en fór þó fljótt að bera á alls kyns stýrikerfisvillum. Líklega voru þessar villur orsakaðar af fikti í skrám sem ekki á að fikta í. 
Fyrir þetta verkefni ákvað ég að setja Linux Mint 15 upp á Virtualbox í Windows 7. Það reyndist vera mjög einfalt og þægilegt og gekk því snuðrulaust.
![Mint-Atli](http://oi44.tinypic.com/29byizc.jpg)


## 2. Uppsetning á vim && git

Uppsetningin á þessum tveimur forritum gekk mjög fljótt og gjörsamlega hnökralaust, enda apt-get skipunin göldrum líkust. Þar sem hvorugur okkar hafði nokkra reynslu af þessum tveimur forritum, þá nýttum við okkur leiðbeiningar gefnar í verkefnislýsingunni. Eftir svolítið fikt komumst við á þá sameiginlegu niðurstöðu að Vim sé ákaflega vænn og viðmótsþýður ritþór, vel þess virði að tileinka sér og stúdera. 

## 3. Unnið með Git (1. hluti)

Forkunin gekk vel. Leiðbeiningum í verkefnislýsingu á MySchool var fylgt í einu og öllu og ekkert vafðist fyrir okkur í framkvæmdinni fyrst um sinn.
Einu teljanlegu vandræðin voru þau að ég (Almar) gleymdi að tilgreina Atla sem collaborator í INTOmarkdown. Fyrir vikið klónaði hann repositoryið án þess að vera collaborator og þegar hann reyndi að vinna með möppuna fékk hann framandi villumeldingar. Þessu var kippt í liðinn með því að eyða möppunni og klóna hana aftur eftir að hafa verið gerður collaborator. Að því loknu gekk allt eins og í sögu og ekkert fór úrskeiðis að okkur vitandi.

Afraksturinn má nálgast hér: [INTOprufa](https://github.com/arumaru/INTOPrufa)

## 4. Uppsettur hugbúnaður

 * **Almar**
1. **PyRoom** er lítið ritvinnsluforrit gert með það í huga að ekkert trufli augað á meðan ritvinnslu stendur. Því er dreift undir GNU General Public License version 3 og kóðann má nálgast [hér](https://code.launchpad.net/pyroom).
2. **WeeChat** er spjallforrit sem styður staðlana IRC og Jabber. Þar sem það er með einfalt textaviðmót og keyrir í skelinni er það létt í keyrslu og hraðvirkt. Því er dreift undir GNU General Public License version 3 og kóðann má nálgast [hér](http://weechat.org/dev/roadmap/).
3. **zathura** er minimalískur og þægilegur skjalalesari sem sparar manni mikla músarnotkun. Forritinu er dreift undir zlib License og kóðann má nálgast [hér](http://git.pwmt.org/).

 * **Atli**
1. **Mozilla Firefox** er mjög vinsæll vafri og eitt stærsta open source verkefni í heimi. Honum er dreift undir Mozilla Public License og kóðann má nálgast [hér](http://www.ohloh.net/p/firefox).
2. **VLC** er mjög vinsæll myndbandaspilari sem styður fjölbreytt úrval svonefndra codeca. Honum er dreift undir GNU General Public License og GNU Lesser General Public License. Kóðann má nálgast [hér](http://www.videolan.org/vlc/download-sources.html).
3. **GIMP (GNU Image Manipulation Program)** er myndvinnsluforrit sem fylgir með mörgum Linux-distróum og hentar vel í ýmsa hversdagslega vinnslu. Það er gefið út undir GNU General Public License 3 og GNU Lesser General Public License 3. Kóðann má nálgast á [hér](http://www.gimp.org/source/).

## 5. Unnið með Git (2. hluti)

Hér þarf ekkert að gera annað en að setja niðurstöður úr 4. fyrstu liðunum inn í þetta skjal.
