---
title: 'Neuerungen? Versionshinweise: Dienst für die automatische Formularkonvertierung'
description: Erfahren Sie mehr über die neuesten Funktionen und Fehlerbehebungen für den Dienst für die automatische Formularkonvertierung
solution: Experience Manager Forms
feature: Adaptive Forms
topic: Administration
topic-tags: forms
role: Admin, Developer
level: Beginner, Intermediate
exl-id: fccafbc9-28c1-4736-922c-24d675b25213
TQID: 'https://experienceleague.adobe.com/5c2zcJqsjOyH--SIp-DbEyQtflWnBy67-ja0BZY8aC8'
product_v2:
  - id: e8f6de9b-cf88-4405-8d10-15efa08c230e
    internal-label: Experience Manager Forms
  - id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
    internal-label: Experience Manager
feature_v2:
  - id: d49d6117-dd89-469c-a774-cc96b7eee433
    internal-label: Administration
  - id: e72c079d-d036-46d5-b43d-29b276a174c2
    internal-label: Authoring and publishing content
subfeature_v2:
  - id: a26f372d-6d7c-452b-81df-594dd4365ae1
    internal-label: Adaptive Forms
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
    internal-label: Beginner
topic_v2:
  - id: eddd9b14-83bd-4ff4-9072-54a4a484abb7
    internal-label: Administration
source-git-commit: e40aeabffdc79dbf5d42a89b8e37c298e016cb90
workflow-type: tm+mt
source-wordcount: '500'
ht-degree: 85%
---
# Versionshinweise

Dienst für die automatische Formularkonvertierung wird ständig verbessert. Um auf dem Laufenden zu bleiben über die neuesten Entwicklungen, besuchen Sie diese Seite regelmäßig. Diese Seite bietet Ihnen Informationen über:

* Früher Zugang
* Letzte Veröffentlichungen
* Neue Funktionen
* Verbesserungen
* Fehlerbehebungen
* Veraltete Funktionalität
* Spezielle Anweisungen
* Zukünftige Pläne für Änderungen

## &#x200B;24. Februar 2022 (AFC-2022.02.0) {#feb-2022}

* Es wurde die Möglichkeit hinzugefügt, [Abschnitte automatisch in Fragmente zu konvertieren](convert-existing-forms-to-adaptive-forms.md), um die Darstellungsgeschwindigkeit von konvertierten Formularen zu verbessern und das Laden großer Formulare im Editor für adaptive Formulare zu erleichtern.

## &#x200B;29. August 2021 (AFC-2021.08.0) {#aug-2021}

* Es wurde eine Funktion hinzugefügt, mit der PDF-Formulare auf in italienischer oder portugiesischer Sprache in adaptive Formulare konvertiert werden können.

## &#x200B;29. Juli 2021 (AFC-2021.07.2) {#july-2021}

* Es wurde eine Funktion hinzugefügt, mit der ein PDF-Formular in französischer, deutscher oder spanischer Sprache in ein adaptives Formular konvertiert werden kann.

## &#x200B;24. Juni 2021 (AFC-2021.06.2) {#june-2021}

### Verbesserte Funktionen {#june-2021-improvements}

Verbesserte Genauigkeit bei der automatischen Erkennung logischer Abschnitte in den Quellformularen und bei der Konvertierung dieser Abschnitte in entsprechende Panels adaptiver Formulare.

## &#x200B;03. März 2021 (AFC-2021.02.2) {#mar-2021}

### Verbesserte Funktionen {#march-2021-improvements}

Verbesserungen beim Organisieren von Formularinhalten in Auswahlgruppen und Felder beim Konvertieren eines Quellformulars in ein adaptives Formular.

## &#x200B;02. Februar 2021 (AFC-2021.01.2) {#feb-2021}

### Verbesserte Funktionen {#feb-2021-improvements}

Verbesserungen beim Organisieren von Formularinhalten in Panels und beim Erstellen von Titeln für Panels beim Konvertieren eines Quellformulars in ein adaptives Formular.

## &#x200B;16. Juli 2020 (AFC-2020.07.2) {#jul-2020}

### Neue Funktionen {#whats-new-jul-2020-}

Es wurde Unterstützung für das Konvertieren farbiger PDF-Formulare in adaptive Formulare hinzugefügt.

### Verbesserte Funktionen {#jul-2020-improvements}

Verbesserungen bei der automatischen Konvertierung von Text-, Formular- und Auswahlgruppenfeldern in entsprechende adaptive Formularkomponenten.

## &#x200B;20. März 2020 (AFC-2020.03.1) {#mar-2020}

### Früher Zugang {#early-access}

**Logische Abschnitte in einem Formular automatisch erkennen**

Standardmäßig erstellt der Dienst für jede Seite eines PDF-Formulars ein separates Panel der obersten Ebene. Jetzt können Sie die Option **[!UICONTROL Logische Abschnitte automatisch erkennen]** verwenden, um Bereiche auf Seitenebene (Bereiche auf Seitenzahlbasis) zu löschen und nur logische Bereiche zu erstellen. Außerdem werden die Felder, die zu keinem Abschnitt gehören, mit dem vorhergehenden logischen Abschnitt zusammengefasst, und die Felder eines logischen Abschnitts, die sich über zwei benachbarte Seiten erstrecken, werden zu einem einzigen logischen Abschnitt zusammengefasst. Wenn sich beispielsweise einige Felder eines logischen Abschnitts am Ende von Seite eins und einige am Anfang von Seite zwei befinden, werden alle diese Felder in einem einzigen logischen Abschnitt zusammengefasst.

### Verbesserte Funktionen {#mar-2020-improvements}

**Verbesserungen bei der Listenerkennung**

Der Dienst erkennt jetzt Listen mit Aufzählungszeichen und Nummern effizienter.

### Spezielle Anweisungen {#special-instructions}

**Connector-Paket für den Dienst für die automatische Formularkonvertierung installieren**

Sie benötigen das Connector-Paket 1.1.38 oder höher, um die neuesten Funktionen und Verbesserungen der Version AFC-2020.03.1 verwenden zu können.

Wenn Sie bereits über eine Service-Umgebung für die automatische Formularkonvertierung (AEM 6.5 oder AEM 6.5 LTS) verfügen, installieren Sie das neueste Service Pack, das neueste AEM Forms-Add-on-Paket und das neueste Connector-Paket in der genannten Reihenfolge, um die neuesten Funktionen des Konvertierungs-Services zu verwenden. Für AEM Forms as a Cloud Service werden Aktualisierungen automatisch bereitgestellt. Genaue Anweisungen finden Sie unter [Dienst zur automatischen Formularkonvertierung konfigurieren](configure-service.md).

