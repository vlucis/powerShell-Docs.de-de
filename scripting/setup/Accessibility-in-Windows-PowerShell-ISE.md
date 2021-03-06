---
title: Barrierefreiheit in Windows PowerShell ISE
ms.date: 2016-05-11
keywords: powershell,cmdlet
description: 
ms.topic: article
author: jpjofre
manager: dongill
ms.prod: powershell
ms.assetid: a078f9d1-dd6b-4323-b16d-0622cd993aa8
translationtype: Human Translation
ms.sourcegitcommit: 3222a0ba54e87b214c5ebf64e587f920d531956a
ms.openlocfilehash: b4d97b1c96a99bcfc43fb20ce9a4ecfa528ea024

---

# Barrierefreiheit in Windows PowerShell ISE
In diesen Thema werden die Barrierefreiheitsfeatures von Windows PowerShell® Integrated Scripting Environment (ISE) geschrieben, die Sie ggf. hilfreich finden.

* [Ändern der Größe und Position des Konsolen- und Skriptbereichs](#bkmk_1)
* [Tastenkombinationen zum Bearbeiten von Text](#bkmk_2)
* [Tastenkombinationen zum Ausführen von Skripts](#bkmk_3)
* [Tastenkombinationen zum Anpassen der Ansicht](#bkmk_4)
* [Tastenkombinationen zum Debuggen von Skripts](#bkmk_5)
* [Tastenkombinationen für Windows PowerShell-Registerkarten](#bkmk_6)
* [Tastenkombinationen für Starten und Beenden](#bkmk_7)

Microsoft ist bestrebt, seine Produkte und Dienste so benutzerfreundlich wie möglich zu gestalten. In den folgenden Abschnitten werden Informationen zu den Funktionen, Produkten und Dienstleistungen vermittelt, mit deren Hilfe Personen mit Behinderungen der Zugriff auf Windows PowerShell ISE erleichtert wird.

Windows PowerShell ISE unterstützt den Modus für hohen Kontrast. Für Sehbehinderte stehen Haltepunktinformationen über die Cmdlets zum Verwalten von Haltepunkten zur Verfügung, wie z. B. [Get-PSBreakpoint](https://technet.microsoft.com/en-us/library/0bf48936-00ab-411c-b5e0-9b10a812a3c6) und [Set-PSBreakpoint](https://technet.microsoft.com/en-us/library/6afd5d2c-a285-4796-8607-3cbf49471420). Weitere Informationen finden Sie unter „Verwalten von Haltepunkten“ in [Debuggen von Skripts in der Windows PowerShell ISE](../core-powershell/ise/How-to-Debug-Scripts-in-Windows-PowerShell-ISE.md#bkmk_1). Neben den Barrierefreiheitsfeatures und Hilfsprogrammen von Microsoft Windows sorgen die folgenden Windows PowerShell ISE-Features für Personen mit Behinderungen für mehr Barrierefreiheit:

-   Tastenkombinationen

-   Syntaxfarbtabelle und Möglichkeit des Änderns anderer Farbeinstellungen mithilfe des Skripterstellungsobjekts [$psISE.Options](https://technet.microsoft.com/en-us/library/75e2a76f-f3d1-490b-ad5d-e3829946aabb)

-   Änderung der Textgröße

## <a name="bkmk_1"></a>Ändern der Größe und Position des Konsolen- und Skriptbereichs
Sie können über die folgenden Schritte die Größe und Position des Konsolen- und Skriptbereichs ändern. Die vorgenommenen Größen- und Positionsänderungen werden beibehalten, wenn Sie Windows PowerShell ISE erneut öffnen.

### So ändern Sie Größe des Skript- und Konsolenbereichs

1.  Setzen Sie den Mauszeiger auf die Trennlinie zwischen Skript- und Konsolenbereich.

2.  Wenn sich der Mauszeiger in einen Pfeil mit zwei Spitzen ändert, ziehen Sie den Rand zum Ändern der Größe des Bereichs.

### So verschieben Sie den Skript- und Konsolenbereich
Führen Sie eines der folgenden Verfahren aus:

-   Drücken Sie zum Verschieben des Skriptbereichs über den Konsolenbereich **STRG+1**. Alternativ können Sie auf der Symbolleiste auf das Symbol **Skriptbereich oben anzeigen** oder im Menü **Ansicht** auf **Skriptbereich oben anzeigen** klicken.

-   Drücken Sie zum Verschieben des Skriptbereichs rechts neben den Konsolenbereich **STRG+2**. Alternativ können Sie auf der Symbolleiste auf das Symbol **Skriptbereich rechts anzeigen** oder im Menü **Ansicht** auf **Skriptbereich rechts anzeigen** klicken.

-   Drücken Sie zum Maximieren des Skriptbereichs **STRG+3**. Alternativ können Sie auf der Symbolleiste auf das Symbol **Skriptbereich maximiert anzeigen** oder im Menü **Ansicht** auf **Skriptbereich maximiert anzeigen** klicken.

-   Klicken Sie zum Maximieren des Konsolenbereichs und Ausblenden des Skriptbereich ganz rechts in der Reihe der Registerkarten auf das Symbol **Skriptbereich ausblenden**. Oder deaktivieren Sie im Menü **Ansicht** die Option **Skriptbereich anzeigen**.

-   Klicken Sie Anzeigen des Skriptbereichs, wenn der Konsolenbereich maximiert ist, ganz rechts in der Reihe der Registerkarten auf das Symbol **Skriptbereich anzeigen**. Oder aktivieren Sie im Menü **Ansicht** die Option **Skriptbereich anzeigen**.

## <a name="bkmk_2"></a>Tastenkombinationen zum Bearbeiten von Text
Sie können die folgenden Tastenkombinationen verwenden, wenn Sie Text bearbeiten.

|Aktion|Tastenkombinationen|Verwenden in|
|----------|----------------------|----------|
|**Kopieren**|STRG + C|Skriptbereich, Konsolenbereich|
|**Ausschneiden**|STRG+X|Skriptbereich, Konsolenbereich|
|**In Skript suchen**|STRG+F|Skriptbereich|
|**Im Skript weitersuchen**|F3|Skriptbereich|
|**Vorheriges im Skript suchen**|UMSCHALT+F3|Skriptbereich|
|**Einfügen**|STRG+V|Skriptbereich, Konsolenbereich|
|**Wiederholen**|STRG+Y|Skriptbereich, Konsolenbereich|
|**In Skript ersetzen**|STRG+H|Skriptbereich|
|**Speichern**|STRG+S|Skriptbereich|
|**Alle auswählen**|STRG+A|Skriptbereich, Konsolenbereich|
|**Rückgängig machen**|STRG+Z|Skriptbereich, Konsolenbereich|

## <a name="bkmk_3"></a>Tastenkombinationen zum Ausführen von Skripts
Sie können die folgenden Tastenkombinationen verwenden, wenn Sie Skripts im Skriptbereich ausführen.

|Aktion|Tastenkombination|
|----------|---------------------|
|**„Neu“,**|STRG+N|
|**Öffnen**|STRG+O|
|**Ausführen**|F5|
|**Auswahl ausführen**|F8|
|**Ausführung beenden**|STRG+UNTBR. STRG+C kann verwendet werden, wenn der Kontext eindeutig ist (es ist kein Text ausgewählt).|
|**Registerkarte** (zum nächsten Skript)|STRG+TAB **Hinweis:** Mit STRG+TAB zum nächsten Skript wechseln funktioniert nur, wenn Sie eine einzige PowerShell-Registerkarte geöffnet haben, oder wenn Sie mehrere PowerShell-Registerkarten geöffnet haben und sich der Fokus im Skriptbereich befindet.|
|**Registerkarte** (zum vorherigen Skript)|STRG+UMSCHALT+TAB **Hinweis:** Mit STRG+UMSCHALT+TAB zum vorherigen Skript wechseln funktioniert nur, wenn Sie eine einzige PowerShell-Registerkarte geöffnet haben, oder wenn Sie mehrere PowerShell-Registerkarten geöffnet haben und sich der Fokus im Skriptbereich befindet.|

## <a name="bkmk_4"></a>Tastenkombinationen zum Anpassen der Ansicht
Sie können die folgenden Tastenkombinationen verwenden, um die Ansicht in Windows PowerShell ISE anzupassen. Diese Tastenkombinationen sind in allen Bereichen in der Anwendung wirksam.

|Aktion|Tastenkombination|
|----------|---------------------|
|**Zum Konsolenbereich wechseln**|STRG+D|
|**Zum Skriptbereich wechseln**|STRG+I|
|**Skriptbereich anzeigen**|STRG+R|
|**Skriptbereich ausblenden**|STRG+R|
||
|**Skriptbereich nach oben verschieben**|STRG+1|
|**Skriptbereich nach rechts verschieben**|STRG+2|
|**Skriptbereich maximieren**|STRG+3|
|**Vergrößern**|STRG+PLUSZEICHEN|
|**Verkleinern**|STRG+MINUSZEICHEN|

## <a name="bkmk_5"></a>Tastenkombinationen zum Debuggen von Skripts
Sie können die folgenden Tastenkombinationen verwenden, wenn Sie Skripts debuggen.

|Aktion|Tastenkombination|Verwenden in|
|----------|---------------------|----------|
|**Ausführen/Fortsetzen**|F5|Skriptbereich beim Debuggen eines Skripts|
|**Einzelschritt**|F11|Skriptbereich beim Debuggen eines Skripts|
|**Überspringen**|F10|Skriptbereich beim Debuggen eines Skripts|
|**Rücksprung**|UMSCHALT+F11|Skriptbereich beim Debuggen eines Skripts|
|**Aufrufliste anzeigen**|STRG+UMSCHALT+D|Skriptbereich beim Debuggen eines Skripts|
|**Haltepunkte auflisten**|STRG+UMSCHALT+L|Skriptbereich beim Debuggen eines Skripts|
|**Haltepunkt umschalten**|F9|Skriptbereich beim Debuggen eines Skripts|
|**Alle Haltepunkte entfernen**|STRG+UMSCHALT+F9|Skriptbereich beim Debuggen eines Skripts|
|**Debugger beenden**|UMSCHALT+F5|Skriptbereich beim Debuggen eines Skripts|

> [!NOTE]
> Sie können beim Debuggen von Skripts in der Windows PowerShell ISE auch die Tastenkombinationen verwenden, die für die Windows PowerShell-Konsole vorgesehen sind. Um diese Tastenkombinationen zu verwenden, müssen Sie die jeweilige Kombination im Konsolenbereich eingeben und die EINGABETASTE drücken.

|Aktion|Tastenkombination|Verwenden in|
|----------|---------------------|----------|
|**Fortsetzen**|C|Konsolenbereich, wenn ein Skript debuggt wird|
|**Einzelschritt**|E|Konsolenbereich, wenn ein Skript debuggt wird|
|**Überspringen**|V|Konsolenbereich, wenn ein Skript debuggt wird|
|**Rücksprung**|O|Konsolenbereich, wenn ein Skript debuggt wird|
|**Letzten Befehl wiederholen** (für Einzelschritt oder Überspringen)|EINGABETASTE|Konsolenbereich, wenn ein Skript debuggt wird|
|**Aufrufliste anzeigen**|K|Konsolenbereich, wenn ein Skript debuggt wird|
|**Debuggen beenden**|Q|Konsolenbereich, wenn ein Skript debuggt wird|
|**Das Skript auflisten**|L|Konsolenbereich, wenn ein Skript debuggt wird|
|**Konsolendebugbefehle anzeigen**|H or ?|Konsolenbereich, wenn ein Skript debuggt wird|

## <a name="bkmk_6"></a>Tastenkombinationen für Windows PowerShell-Registerkarten
Sie können die folgenden Tastenkombinationen verwenden, wenn Sie Windows PowerShell-Registerkarten verwenden.

|Aktion|Tastenkombination|
|----------|---------------------|
|**PowerShell-Registerkarte schließen**|STRG+W|
|**Neue PowerShell-Registerkarte**|STRG+T|
|**Vorherige PowerShell-Registerkarte**|STRG+UMSCHALT+TAB. Diese Tastenkombination funktioniert nur, wenn keine Dateien in irgendeiner Windows PowerShell-Registerkarte geöffnet sind.|
|**Nächste Windows PowerShell-Registerkarte**|STRG+TAB. Diese Tastenkombination funktioniert nur, wenn keine Dateien in irgendeiner Windows PowerShell-Registerkarte geöffnet sind.|

## <a name="bkmk_7"></a>Tastenkombinationen für Starten und Beenden
Sie können die folgenden Tastenkombinationen verwenden, um die Windows PowerShell-Konsole (PowerShell.exe) zu starten oder Windows PowerShell ISE zu beenden.

|Aktion|Tastenkombination|
|----------|---------------------|
|**Beenden**|ALT+F4|
|**PowerShell.exe starten** (Windows PowerShell-Konsole)|STRG+UMSCHALT+P|

## Weitere Informationen
[Verwenden der Windows PowerShell ISE](../core-powershell/ise/Using-the-Windows-PowerShell-ISE.md)




<!--HONumber=Aug16_HO4-->


