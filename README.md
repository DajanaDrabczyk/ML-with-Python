# Klasyfikacja- Raport z analizy i modelowania zbioru danych zawierającego informacje o właściwościach wody
Classification - ML

Celem analizy zbioru danych jest klasyfikacja próbek wody na zdatną lub niezdatną do picia. Modelowana będzie zmienna "potability" - oznaczająca czystą wodę, która nadaje się do spożycia.

Motywacja: "Dostęp do bezpiecznej wody pitnej jest niezbędny dla zdrowia. Jest podstawowym prawem człowieka i elementem skutecznej polityki ochrony zdrowia. Ważna jest również jako kwestia rozwoju na poziomie krajowym, regionalnym i lokalnym. W niektórych regionach wykazano, że inwestycje w zaopatrzenie w wodę i urządzenia sanitarne mogą przynieść korzyści ekonomiczne netto, ponieważ zmniejszenie negatywnych skutków zdrowotnych i kosztów opieki zdrowotnej przewyższają koszty podjęcia interwencji."

Opis modelowanej zmiennej:

Woda pitna - czysta woda, która nadaje się do spożycia (bez zagrożenia dla zdrowia). Powinna ona zawierać odpowiednią ilość soli mineralnych, a nie zawierać zanieczyszczeń organicznych i nieorganicznych. Wodę pitną można czerpać ze studni lub innych ujęć, a na terenach zurbanizowanych jej podstawowym rodzajem jest woda wodociągowa. W krajach rozwiniętych coraz powszechniej spożywa się wodę mineralną.Czasami wodę pitną można uzyskać przez przegotowanie wody powierzchniowej, lecz nie daje to gwarancji unieszkodliwienia wszystkich drobnoustrojów. Spożywanie wody skażonej bakteriologicznie może być przyczyną zatrucia, którego najczęstszymi objawami są nudności, wymioty i biegunka.

Opis danych:

(1) pH - jest ważnym miernikiem w określaniu równowagi kwasowo-zasadowej wody. Może być również używany do określenia, czy woda ma odczyn kwaśny lub zasadowy. Maksymalna dopuszczalna granica pH została ustalona przez WHO na 6,5 do 8,5.

(2) Hardness - twardość wody to właściwość wynikająca z obecności w niej soli wapnia, magnezu i innych metali, a dokładnie – z ich stężenia. Czas kontaktu wody z materiałem powodującym twardość wpływa na stopień twardości wody surowej.

(3) Solids - substancje stałe, które składają się ze wszystkich zawieszonych, koloidalnych i rozpuszczonych substancji. Są to wszelkie rozpuszczone sole, takie jak chlorek sodu (NaCl) i cząstki stałe, takie jak muł i plankton.W zależności od kryteriów oceny, wysoki poziom całkowitej zawartości części stałych może spowodować, że próbka zostanie uznana za skażoną.

(4) Chloramines - chloramina jest popularnym środkiem odkażającym, stosowanym w roztworach wodnych, o lepszym działaniu od roztworów samego chloru, gdyż jest od niego trwalsza w roztworach, a ze związkami organicznymi nie tworzy szkodliwych dla zdrowia halometanów.

(5) Sulfate - do wody dostają się ze ściekami przemysłowymi oraz opadami atmosferycznymi, w wodzie podziemnej występują w najwyższych stężeniach i pochodzą ze źródeł naturalnych. Są jednymi z najmniej toksycznych anionów, chociaż przy ich wysokich stężeniach następuje odwodnienie i podrażnienie przewodu pokarmowego. Obecność siarczanów w wodzie do spożycia może również powodować wyczuwalną zmianę jej smaku oraz może przyczyniać się do korozji systemów wodociągowych.

(6) Conductivity - przewodność jest wskaźnikiem całkowitej ilości rozpuszczonych minerałów zawartych w wodzie. Woda deszczowa ma niską przewodność, natomiast woda ściekowa czy ta w dolnych biegach rzek – wysoką. Wyższa przewodność sama w sobie nie powoduje problemów zdrowotnych. Wręcz przeciwnie – wody mineralne (tj. wody z wysoką zawartością minerałów) są często lecznicze. Jednak pod względem długotrwałej konsumpcji zbyt zmineralizowana woda nie jest idealna.

(7) Organic carbon - ogólny węgiel organiczny to miara ilości związków organicznych zawartych w próbce wody. Związki zawierające węgiel organiczny mogą być rozpuszczone w wodzie lub występować jako nierozpuszczona w wodzie zawiesina materiału lub płynu. Ta materia organiczna może dostawać się do wody w sposób naturalny, ale także ze źródeł i w wyniku procesów obsługiwanych przez człowieka. Przykładami substancji organicznych są substancje pochodzenia roślinnego lub zwierzęcego oraz syntetyczne, które zawierają węgiel i inne pierwiastki tworzące związki organiczne.

(8) Trihalomethanes - powstają w wodzie do picia głównie na skutek reakcji chloru z naturalnie występującymi składnikami organicznymi i znajdującymi się w wodzie bromkami. Spośród związków należących do omawianej grupy, w wodzie najczęściej stwierdza się obecność chloroformu, o stężeniu sporadycznie sięgającym nawet kilkuset mikrogramów na litr. W wyniku wprowadzenia chloroformu drogą doustną, w organizmie może powstać kilka czynnych przejściowych metabolitów. Długotrwałe narażenie na dużą dawkę może w konsekwencji powodować zmiany w wątrobie, nerkach i tarczycy.

(9) Turbidity - mętność wody powodują nierozpuszczone substancje zawieszone w wodzie. Może chodzić o substancje nieorganiczne ( piaski, iłły, wytrącone związki żelaza i manganu, a także związki chemiczne pochodzące ze ścieków) lub organiczne ( gliny, związki humusowe, obumarłe cząstki roślin, plankton, bakterie oraz nierozpuszczalne związki organiczne ze ścieków przemysłowych).

Opis jednostek w jakich podane są zmienne:

Pochodzenie danych: https://www.kaggle.com/adityakadiwal/water-potability
