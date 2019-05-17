---
title: Pasirinktiniai „Office“ diagnostikos duomenys
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: Ent_O365
ms.custom:
- Ent_Office_ProPlus
- Ent_Office_Privacy
description: Suteikia „Office“ administratoriams informacijos apie pasirinktinius duomenis naudojant „Office“, įskaitant keletą įvykių pavyzdžių.
hideEdit: true
ms.openlocfilehash: 1df576e8f5f1b3ed9fff11651ff4dd2b28d47229
ms.sourcegitcommit: b3fd057154853fc588d0e83b4d632b6e9a051a3c
ms.translationtype: HT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32435863"
---
# <a name="optional-diagnostic-data-for-office"></a>Pasirinktiniai „Office“ diagnostikos duomenys

> [!IMPORTANT]
> Šiame straipsnyje pateikta informacija taikoma 1904 arba naujesnės versijos „Office“ kliento programinei įrangai, įdiegtai „Windows“ kompiuteryje:
> - „Office 365 ProPlus“ ir „Office 365 Business“
> - „Office 365 Personal“, „Office 365 Home“ arba kitos „Office“ versijos, kurios yra „Office 365“ prenumeratos dalis.
> - „Project“ ir „Visio“, kurios įtrauktos į kai kuriuos prenumeratos planus, pvz., planą „Project Online Professional“ arba „Visio Online“ 2 planą.

Diagnostikos duomenys naudojami siekiant apsaugoti ir naujinti „Office“, aptikti, diagnozuoti ir taisyti problemas, taip pat tobulinti produktus. Šie duomenys neapima vartotojo vardo ar el. pašto adreso, vartotojo failų turinio ar informacijos apie programas, nesusijusias su „Office“.

Šie diagnostikos duomenys, susiję su „Office“ kliento programine įranga, naudojama kompiuteriuose, kuriuose įdiegta operacinė sistema „Windows“, renkami ir siunčiami „Microsoft“. Kai kurie diagnostikos duomenys yra būtini, o kiti – pasirinktiniai. Suteikiame jums galimybę pasirinkti, ar siųsti mums būtinuosius, ar pasirinktinius diagnostikos duomenis naudojant privatumo valdiklius, pvz., organizacijoms skirtus strategijos parametrus. Naudodami diagnostikos duomenų peržiūros programą galite matyti mums siunčiamus diagnostikos duomenis.

***Pasirinktiniai diagnostikos duomenys*** yra papildomi duomenys, kurie padeda mums tobulinti produktą ir gauti papildomos informacijos, padedančios aptikti, diagnozuoti ir ištaisyti kilusias problemas.

Jei pasirinksite siųsti mums pasirinktinius diagnostikos duomenis, būtinieji diagnostikos duomenys taip pat bus įtraukti.

Pasirinktinių diagnostikos duomenų pavyzdžiai yra duomenys, kuriuos renkame apie paveikslėlius, kuriuos vartotojai įterpia į „Word“ dokumentus, kad galėtume teikti geresnes vaizdų parinktis, bei duomenys, kuriuos renkame apie tai, per kiek laiko „PowerPoint“ skaidrė pasirodo jūsų ekrane, kad galėtume pagerinti veikimą, jei jis lėtas.

Daugiau informacijos apie diagnostikos duomenis, žr.:

- [Būtinieji „Office“ diagnostikos duomenys](required-diagnostic-data.md)
- [Diagnostikos duomenų peržiūros programos naudojimas su „Office“](https://support.office.com/article/cf761ce9-d805-4c60-a339-4e07f3182855)

Jei esate organizacijos administratorius, galbūt jus domina šios temos:

- [„Office 365 ProPlus“ privatumo valdiklių apžvalga](overview-privacy-controls.md)
- [„Office 365 ProPlus“ privatumo valdiklių valdymas naudojant strategijos parametrus](manage-privacy-controls.md)

## <a name="categories-of-optional-diagnostic-data"></a>Pasirinktinių diagnostikos duomenų kategorijos

Pasirinktinai diagnostikos duomenys skirstomi į šias kategorijas:

- Programinės įrangos sąranka ir inventorius
- Produktų ir tarnybų naudojimas
- Produktų ir tarnybų našumas
- Įrenginių jungiamumas ir konfigūracija

Šios kategorijos rodomos diagnostikos duomenų peržiūros programoje ir jos yra tokios pačios, kaip kategorijos, naudojamos su būtinaisiais diagnostikos duomenimis.

Toliau esančiose sekcijose pateikiamas kiekvienos kategorijos aprašas ir kiekvienos kategorijos įvykių pavyzdžiai.

## <a name="software-setup-and-inventory-events"></a>Programinės įrangos sąrankos ir inventoriaus įvykiai

Šioje kategorijoje yra įvykiai, kurie gali apimti šias sritis:

- Įdiegtas produktas ir versija bei diegimo būsena
- Programinės įrangos papildiniai ir jų parametrai.
- Dokumento, funkcijos ir papildinio sąlygos, kurios gali pažeisti saugą, įskaitant produkto parengimą naujinti.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**   | **Įvykio aprašas**  |
| ---- | ---- |
| Office\_Extensibility\_AppCommands\_GetRibbonUpdatesForUserId | Šis įvykis nurodo, ar „Word“ sėkmingai atnaujina juostelę „Word“ vartotojo sąsajoje, kai vartotojas pakeičia savo tapatybę. Šį įvykį naudojame siekdami aptikti neteisingą sąranką ir kitas problemas, kurios gali turėti įtakos „Office“ vartotojo sąsajai. |
| Office.Extensibility.AppCommands.AppCmdInstall   | Šis įvykis suteikia informacijos apie vartotojo įdiegtą „Office“ papildinį, įskaitant programos ID, operacinės sistemos versiją ir komponavimo versiją, informaciją, ar diegimas pavyko, ir diegimo trukmę.  |

## <a name="product-and-service-usage-events"></a>Produktų ir tarnybų naudojimo įvykiai

Šioje kategorijoje yra įvykiai, kurie gali apimti šias sritis:

- Informacija apie tai, ar sėkmingai veikia programos funkcijos. Tik programos ir dokumentų atidarymas ir uždarymas, failų redagavimas ir failų bendrinimas (bendradarbiavimas).
- Nustatymas, ar įvyko specifiniai funkcijų įvykiai, pvz., paleidimas ar sustabdymas, ir ar funkcija veikia.
- „Office“ pritaikymo neįgaliesiems funkcijos

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**   | **Įvykio aprašas**  |
| ------ | ------- |
| Office.Word.Commanding.Highlight  | Šis įvykis nurodo, kad „Word“ įvykdė teksto paryškinimo komandą. Naudojame šį įvykį, kad aptiktume klaidas teksto paryškinimo komandoje.  |
| Office.Translator.AddInLoaded   | Kontrolinis signalas, nurodantis, kad vertyklės funkcija įkelta ir sėkmingai pateikta.  |
| Office.Graphics.InsertPictureCommandActivity  | Seka paveikslėlio įterpimo funkcijos pavykimą arba nepavykimą bei praneša informaciją apie įterptų paveikslėlių tipus ir šaltinį.|
| Office.PowerPoint.PPT.Desktop.SummaryZoomInsertionRule   | Šis įvykis nustato, ar dokumente yra sekcijų, kai vartotojas įterpia interaktyviąją suvestinės peržiūrą, ir ar vartotojas pasirenka panaikinti esamas sekcijas. |
| Office.Security.SecureReaderHost.ProtectedViewValidation | Seka kada ir kodėl failas atidaromas apsaugotame rodinyje. Naudojama tam, kad būtų galima diagnozuoti sąlygas, kai apsaugotas rodinys gali būti netinkamai suaktyvintas, siekiant užtikrinti, kad funkcija veiktų tinkamai. |

## <a name="product-and-service-performance-events"></a>Produktų ir tarnybų našumo įvykiai

Šioje kategorijoje yra įvykiai, kurie gali apimti šias sritis:

- Nenumatytas programų uždarymas (užstrigimas) ir programos būsena, kai taip nutinka.
- Scenarijų, tokių kaip programos paleidimas ar failo atidarymas, prastas atsakymo laikas ar našumas.
- Funkcijos ar vartotojo patirties veikimo klaidos.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**    | **Įvykio aprašas**   |
| --------------- | -------------- |
| Office\_Word\_Word\_CoreSaveTime100ns     | Šis įvykis užfiksuoja „Word“ dokumento įrašymo veiksmo našumą. Šį įvykį naudojame siekdami aptikti „Word“ dokumento įrašymo veiksmų klaidas ir našumo problemas.|
| Office.Identity.SignInForWamAccountAad  | Šis įvykis siunčiamas, kai vartotojas yra prisijungęs prie „Azure Active Directory“ paskyros naudodamas žiniatinklio paskyrų tvarkytuvo (WAM) biblioteką. Jei šis įvykis nepavyko, jis siunčia metaduomenis, tokius kaip AppName, AppVersion ir ErrorCode. |
| Office.PowerPoint.PPT.Desktop.FileOpen.FirstSlideMasterThumbnailRenderTime | Šis įvykis fiksuoja, kiek laiko trunka atvaizduoti pirmąją „PowerPoint“ skaidrių ruošinio miniatiūrą.  |
| Office.Extensibility.Diagnostics   | Šis įvykis suteikia bendrą „Office“ papildinių diagnostikos informaciją, tokią kaip derinimui skirtos gedimų ataskaitos.|

## <a name="device-connectivity-and-configuration-events"></a>Įrenginių jungiamumo ir konfigūracijos įvykiai

Šioje kategorijoje yra įvykiai, kurie gali apimti šias sritis:

- Tinklo ryšio būsena ir įrenginio parametrai, tokie kaip atmintis.

Šioje lentelėje pateikiami šios kategorijos įvykių pavyzdžiai ir šių įvykių aprašymas.

| **Įvykio pavadinimas**                    | **Įvykio aprašas**                                                                                                                                                     |
| ------ | ----- |
| Office\_Graphics\_ArtViewValidate | Šis įvykis fiksuoja grafinių elementų rodinio, kuris palaiko grafinę sąsają, rezultatų tikrinimą. Įvykį naudojame, kad galėtume rinkti naudojimo ir klaidų duomenis apie grafinių elementų atvaizdavimą. |
| Office.Graphics.ARCExceptionScope | Šis įvykis seka atvaizdavimo triktis, vykstančias atvaizdavimo modulyje. |
| Office.Extensibility.ODPLatency   | Šis įvykis suteikia informacijos apie vartotojo tinklo ryšį ir greitį.     |
