---
source-git-commit: 5da9119f156bb8947f25b41f7e75b12ee2eadec3
workflow-type: tm+mt
source-wordcount: '767'
ht-degree: 2%
---
# Richtlinien für Beiträge zur Adobe Experience Manager-Dokumentation

## Dokumentationsphilosophie

Wir wissen, dass Adobe Experience Manager-Anwender in einem hart umkämpften Umfeld arbeiten und sich bemühen, digitale Erlebnisse zu schaffen, die sie von ihren Mitbewerbern unterscheiden. Deshalb ist es wichtig, dass, wenn Adobe fortschrittliche neue Tools in AEM bereitstellt, diese durch genaue und klare Dokumentation ergänzt werden, damit der Kunde sofort seine AEM-Investition nutzen und den ROI maximieren kann.

Ziel der AEM-Dokumentation ist es, AEM-Benutzenden die Dokumentation so schnell wie möglich zur Verfügung zu stellen. Deshalb setzen wir auf genaue, brauchbare Dokumentation und bemühen uns, sie kontinuierlich zu aktualisieren und zu verbessern.

## Dokumentationsbeiträge

Im Interesse einer kontinuierlichen Verbesserung der AEM-Dokumentation ist die gesamte Community von AEM-Benutzenden herzlich eingeladen, zur Dokumentation beizutragen. Sei es durch Pull-Anfragen oder -Probleme, Verbesserungen an der Dokumentation können Korrekturen, Klarstellungen, Erweiterungen und zusätzliche Beispiele sein.

## Dokumentationsstandards

Auch wenn wir Beiträge zu unserer Dokumentation begrüßen, sollte jeder Beitrag zur AEM-Dokumentation, entweder in Form einer Pull-Anfrage oder eines Problems, unseren Beitrags- und Dokumentationsstandards entsprechen.

Beiträge, die diese Standards nicht erfüllen, können abgelehnt werden.

### Wir dokumentieren Standard-Anwendungsfälle.

Die Dokumentation zu AEM deckt Standardanwendungsfälle ab. Anwendungsfälle, die über den Umfang der Standardinstallation und -verwendung des Produkts hinausgehen, sind nicht Teil der Dokumentation zu AEM.

### Generell dokumentieren wir keine Fehler oder Problemumgehungen.

Die Dokumentation zu AEM deckt Standardanwendungsfälle ab. Aus diesem Grund werden Fehler, durch Bugs verursachte Auswirkungen und Problemumgehungen für Bugs im Allgemeinen nicht dokumentiert.

Ausnahmen von dieser Regel gelten für die Versionshinweise, in denen bekannte Probleme mit möglichen Lösungen aufgelistet werden können, die vom AEM-Produktmanagement genehmigt wurden.

### Dokumentationsbeiträge dienen nicht zur Beantwortung technischer Fragen.

Alle Ideen, die Sie zur Verbesserung der AEM-Dokumentation haben, sind als Beiträge willkommen. Kommentare, Probleme und Pull-Anfragen sind jedoch nur für *Beiträge* vorgesehen. Sie sind nicht zur Beantwortung Ihrer Fragen über die Verwendung von AEM, Implementierung Ihres AEM-Projekts oder zur Lösung technischer Probleme vorgesehen.

Fragen zur Verwendung von AEM oder zu technischen Fehlern, die möglicherweise bei Ihnen auftreten, sollten entsprechend dem herkömmlichen Support-Vorgang über das [Support-Portal für Experience Manager gemeldet &#x200B;](https://experienceleague.adobe.com/de?support-solution=Experience+Manager&lang=de#home) in der [Experience Manager-Community diskutiert &#x200B;](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community?profile.language=de).

***AEM-Dokumentationsbeiträge sind kein Ersatz für den Adobe-Support*** und Beiträge, die um Antwort auf Support-Fragen bitten, werden abgelehnt.

### Die Beiträge müssen klar auf die betroffenen Dokumentationsseiten verweisen.

Wenn Sie ein Problem erstellen, um Verbesserungen an der Dokumentation vorzuschlagen, müssen Sie Links zu den betroffenen Seiten einfügen. Wenn Sie ein Problem über den Link **Diese Seite bearbeiten** auf einer Dokumentationsseite erstellen, wird das Problem automatisch mit einem Link zur Seite erstellt.

Dies gilt nicht für Pull-Anforderungen, da Pull-Anforderungen ihrer Art nach auf die betroffene(n) Seite(n) verweisen.

## Dokumentationsrichtlinien

Wir bitten darum, dass alle Beiträge zu unserer Dokumentation bestimmten Stilrichtlinien entsprechen.

Die Befolgung dieser Richtlinien erleichtert die Überprüfung Ihres Beitrags und ermöglicht eine schnellere Integration in unsere Dokumentation.

### Sprache und Stil

#### Sprache

* Die AEM-Dokumentation wird in englischer Sprache verfasst und verwaltet.
* Halten Sie Sätze so einfach wie möglich.
* Halten Sie die Sprache klar und prägnant.

Denken Sie daran, dass die Leser der AEM-Dokumentation auf der ganzen Welt zu finden sind und von ihnen nicht erwartet werden kann, dass sie fließend Englisch sprechen oder Muttersprachler sind. Umgangssprachliche Formulierungen vermeiden und die Sprache so klar und einfach wie möglich halten.

#### Folgen Sie dem Microsoft Manual of Style

[Das Manual of Style von Microsoft](https://docs.microsoft.com/en-us/style-guide/welcome/) ist ein kostenloses Stil-Handbuch zur Dokumentation von Software. Die AEM-Dokumentation folgt soweit möglich diesem Modell.

### Formatierung

| Element | Stil |
|---|---|
| Element oder Option der Benutzeroberfläche | **fett** |
| Dateiname, Pfad, Benutzereingabe, Parameterwerte | `monospaced` |
| Code, Befehlszeile | ```Code Block``` |

### Screenshots

Screenshots sind umsichtig und nur dann zu verwenden, wenn eine textliche Beschreibung nicht ausreicht.

Markierungen oder andere Anmerkungen in Screenshots (wie rote Rahmen, Pfeile oder Text) sollten nicht verwendet werden. Auf diese Weise sind die Screenshots in lokalisierten Versionen der Dokumentation einfacher wiederzuverwenden oder zu replizieren.

### Versionsspezifische Verweise

Versuchen Sie möglichst im gesamten Dokumentationsinhalt direkte Verweise auf eine bestimmte Version zu vermeiden. Dies macht die Dokumentation flexibler und erweiterbar für zukünftige Versionen.

### Verwendung von Day, AEM, CQ, CRX

Das Produkt sollte in einem Artikel zum ersten Mal immer mit dem vollständigen Namen **Adobe Experience Manager** genannt und anschließend als **AEM** bezeichnet werden.

Day, Day-Software, CQ und CRX sollten nur verwendet werden, wenn dies unvermeidlich ist, z. B. bei Klassennamen oder bei Verweisen auf die Historie von AEM.
