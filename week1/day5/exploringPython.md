# Ukuhlola iPython

## Jupyter Notebook

Kuze kube manje sisebenzisa i-Spyder IDE noma imvelo yokubhala ikhodi yePython. Ngiyethemba usujwayelene nayo. Manje kukhona abanye abaningi laphaya eyakhelwe izinhloso ezahlukene. NjengePyCharm ne-VS Code, nokunye okuningi. Kodwa-ke, uma ufunda iPython futhi uyisebenzisa kolunye uhlelo lokusebenza lwesayensi yedatha, kufanele wazi ngeJupyter Notebooks.

I-Jupyter Notebook iyizinhlelo zokusebenza zewebhu ezisebenzisanayo ezisiza ukudala nokwabelana ngamadokhumenti aqukethe ikhodi ebukhoma, izibalo, ukubonwa, nombhalo olandisayo. Zisetshenziswa kakhulu kwisayensi yedatha, ucwaningo lwesayensi, kanye nemfundo.

Othisha abaningi bayisebenzisela ukwethula okuqukethwe, njengoba uzobona evikini lesi-2. Izifundo eziningi kulayini zisebenzisa iJupyter Notebooks ukudlulisa imibono nezimiso. Ngakho-ke kubaluleke kakhulu ukuqonda ukuthi isetshenziswa kanjani, uma ufuna ukulandela okokufundisa noma isifundo.

Kukhona inguqulo entsha ye-Jupyter Notebook ebizwa ngokuthi i-Jupyter Lab, kodwa into efanayo. Ezakamuva zinezici ezengeziwe.

### Ukuqalisa

Ngakho-ke into yocingo mayelana nendawo yokusebenzela ye-Anaconda oyifakile ukuthi ine-Jupyter Notebook esivele ifakelwe wena. Ngakho-ke uma uya kuwe windows app, bese uthayipha "Jupyter", kufanele ubone:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/41143f23-2e3c-42c7-9749-00baa74e2f51)

Chofoza lokho futhi kufanele ubone iwindi letheminali liphuma kanye newindi lesiphequluli:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/41b75678-384d-40f8-a49f-1d3492d891e6)

Iya kuthebhu "Entsha" bese uchofoza "Python 3 (ipykernal").

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/1a0d0608-54b4-4bf1-a92b-06479e6a1cb1)

Kufanele ubone okulandelayo:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/d6f57945-a452-4a34-97a5-1ada1ce26fa9)

Ngakho-ke yini umehluko phakathi kweJupyter Notebook nefayela leskripthi sePython.

Yebo kuyasebenzisana kakhulu, kufana nenhlanganisela yeskripthi sePython kanye nekhonsoli. Ungaphinda ubhale ngezindlela ezimbili, ikhodi enye ifana nedokhumenti yamagama. Lokhu kusiza ukuchaza ukuthi wenzani kuyo yonke idokhumenti.

Ake sibone izibonelo ezimbalwa ezisebenzayo.

Ake sibuyele kwesinye sezifundo zethu zokuqala ngenkathi sisebenzisa ifayela le-country_data.csv. Siqale safunda ukufaka le datha ezinhlwini. Masenze okufanayo kuJupyter Notebook. Faka uhlu olulandelayo bese uchofoza ku-"Run":

```
iminyaka = [30,40,30,49,22,35,22,46,29,25,39]
```

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/78a26b20-73cf-4156-92c9-9a315389890e)

Manje ukuphrinta idatha "yeminyaka" esikrinini singavele sifake "iminyaka" bese uchofoza ku-"Run":

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/bef151c4-5232-4980-9169-baafc96234c3)

Okufanayo nalokho esikuthola kukhonsoli yePython. Nokho, manje usungakwazi ukususa noma wengeze iseli, njengoba wenza esikriphweni. Qaphela ukuthi ungasebenzisa futhi umsebenzi `print()` ukuze uwubonise kodwa akudingekile.

Esikhundleni sokucindezela cindezela ungacindezela u-"Shift" + "F5" ukuze uqalise iseli.

Manje uzoqaphela ukuthi kukhona okuya phansi okusho ikhodi, uma uchofoza uzobona izinketho ezimbalwa zombhalo:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/41d27805-49d5-4ea1-8a59-1965a7205741)

Manje ngengeze umbhalo othile, hhayi ikhodi, bese kuba isithombe ekugcineni:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/93a44532-9eba-462c-a5cc-567292da3a9c)

Yilokhu okwenza i-Jupyter Notebook ibe usizo ngempela ekufundiseni njengoba ungakwazi ukwengeza kalula izinto ezingezona ikhodi kuwe I-Jupyter Notebook, futhi empeleni uxoxe indaba yekhodi yakho.

### Panda

Ake sizame ukufunda kwenye idatha.

Masiqale silayishe ifayela, sikwenze lokho ngokuya kokuthi Ifayela->Vula:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/8b78cef7-e037-4502-883d-0d0753a3613d)

Bese uchofoza inkinobho ethi "Layisha" bese ukhetha okuthi "country_data.csv":

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/776fbaa2-901c-458c-b851-b7b72bd54ae4)

Buyela kuJupyter Notebook yakho bese ufaka ikhodi elandelayo:

```
ngenisa ama-panda njenge-pd

df = pd.read_csv("country_data.csv")

df
```

Uma uchofoza ku-"Run", uthola okulandelayo:

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/548031e9-3cc5-4b3b-b764-ba951dc83e25)

Okungumfanekiso omuhle impela.

### Ukubukwa

Manje sizobheka ukuhlela amagrafu athile.

![image](https://github.com/ChpcTraining/css2024_notes/assets/157092105/c44058a9-b289-402e-98cf-b8db81942de1)




### Phansi Izinhlangothi

Ngenkathi ama-Jupyter Notebooks eyithuluzi elidumile nelinamandla lokuhlaziya idatha, ikhompuyutha yesayensi, kanye nezinhlelo ezisebenzisanayo ePython, kukhona ukwehla nezizathu zokuthi kungani zinganconyelwa abasaqalayo, ikakhulukazi lapho beqala ukufunda iPython:

1. Ukubulawa Okungalandeleli:

Kuma-Notebook e-Jupyter, ikhodi ingenziwa ngaphandle kwe-oda, okuholela ekudidekeni kwabaqalayo. Indlela amaseli abulawa ngayo ibalulekile, futhilokhu kungenza kube inselele ukuqonda ukuhamba kohlelo.

2. Isimo Esifihliwe:

Okuguquguqukayo namanani akho kuyaqhubeka kuwo wonke amaseli, okungenza kube nzima ukulandelela isimo sohlelo. Lesi simo esifihliwe singadideka kwabaqalayo abasabamba umqondo wobubanzi obuguquguqukayo nokugeleza kohlelo.

3. Izinselele zokulungisa iphutha:

Ukulungisa iphutha ku-Jupyter Notebooks kungaba inselele kakhulu uma kuqhathaniswa nezimo zendabuko ezisekelwe kumbhalo. Abasaqalayo bangase bakuthole kunzima ukuthola nokulungisa amaphutha, ikakhulukazi uma kubhekwana nokubulawa okungaqondile kanye nesimo esifihliwe.

4. Ukushoda kwe-Ecapsulation:

I-Jupyter Notebooks ikhuthaza isitayela sokusebenzisana nesokuhlola, kodwa ingase ingakhuthazi izinqubo ezinhle zokuhlela ezifana ne-encapsulation kanye ne-modularization. Abasaqalayo bangase baphuthelwe amakhono abalulekile okubhala ikhodi ehlanzekile, ehlelekile, negcinekayo.

5. Ukuncika Emyalweni Wokubulawa:

Ukuqalisa kabusha amaseli noma ukusebenzisa amaseli ngendlela ehlukile kungaholela emiphumeleni engalindelekile. Lokhu kuncika ku-oda lokukhishwa kungase kudide kwabasaqalayo, abangase balindele ukuthi ikhodi iziphathe ngendlela efanayo kungakhathaliseki ukuthi isetshenziswa kanjani.

6. Izici zokuhlela amakhodi anomkhawulo:

Ngenkathi ama-Jupyter Notebooks ehlinzeka ngendawo enhle yokuhlola ikhodi, awanazo ezinye zezici zokuhlela zekhodi ezithuthukisiwe ezitholakala ku-Integrated Development Environments (IDE). Abasaqalayo bangase bazuze kuzici ezifana nokuqedela ngokuzenzakalela kwekhodi, ukuhlanganisa, nokulungisa amaphutha okuhlanganisiwe, okuvame ukuqina kakhulu kuma-IDE.

7. Izinselelo Zokulawula Inguqulo:

Amasistimu okulawula inguqulo (njenge-Git) angaba inselele kakhulu ukuwasebenzisa nama-Jupyter Notebooks uma kuqhathaniswa nemibhalo evamile. Ukulandelela izinguquko endaweni yokuhlanganyela kungase kungabi lula kakhulu. Futhi awubhali iskripthi sePython, ifayela leJupyter Notebook ngefomethi yalo.

8. Ijika lokufunda eliwumqansa:

I-Jupyter Notebooks yethula imiqondo eyengeziwe (isb., amaseli, izinhlobo zamaseli) abaqalayo okudingeka bayiqonde eduze nokufunda iPython ngokwayo. Lokhu kunganezela ejikeni lokuqala lokufunda futhi kungase kuphazamise inqubo yokufunda.

Yize ama-Jupyter Notebooks anezinkinga zawo, kubalulekile ukuqaphela ukuthi angamathuluzi amahle kakhulu emisebenzi ethile, ikakhulukazi kusayensi yedatha nocwaningo. Kodwa-ke, kwabaqalayo abagxile ekufundeni okuyisisekelo kwezinhlelo ze-Python, ukuqala ngendlela engokwesiko esekelwe kuskripthi kusetshenziswa umhleli wombhalo noma indawo yokuthuthukisa edidiyelwe (IDE) ingase inikeze ulwazi lokufunda oluqondile noluhlelekile. Njengoba abasebenzisi bekhululeka kakhulu ngePython, bangakwazi ukuhlola futhi bahlanganise I-Jupyter Notebooks ekuhambeni komsebenzi wabo njengoba kudingeka.


## Ikhodi ye-VS

## Sakaza

## Ezinye Izihloko

### Ingabe I-Python Yanele?

## Buyekeza Izihloko



##HPC
