# LaTeX-Vorlage-Berichtsheft

Dies ist eine Vorlage für ein Berichtsheft einer kaufmännischen Ausbildung.

# Vorschau

![Vorschau Berichtsheft](https://amshove.org/daten/Vorschau_Berichtsheft.png)

# Verwendung

Zur Erstellung eines Monats werden folgende Kommandos genutzt (Beispiel liegt unter Berichte/2015Juli.tex)

Die in spitzen Klammern stehenden Begriffe sind die Parameter.

    \Titelzeile{<MONAT>}{<JAHR>}{<AUSBILDUNGSNACHWEIS_NR>}
    \Monat{
    \Woche{<WOCHENNUMERIERUNG>}{<INHALT DER WOCHE>}
    }
    \Unterschrift

Außerdem sind zwei Metainformationen unter 
> Meta.tex

einzutragen.

# Eclipse

Dem Projekt liegt eine Eclipse-Projektdatei (.project) und ein Eclipse-Settingsordner (.settings/) bei, da ich mein Berichtsheft mit Eclipse erfasst habe.
Wichtig ist das UTF8-Encoding (.settings/).

Zur Einrichtung von Eclipse zur Bearbeitung von LaTeX möchte ich gerne auf einen Blogeintrag meines Ausbilders [Stefan Macke](http://blog.stefan-macke.com/2012/11/02/installing-and-configuring-miktex-texlipse-and-pdf4eclipse-to-write-and-compile-latex-documents/) verweisen.

# Lizenz

[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)  
LaTeX Vorlage für ein Berichtsheft einer kaufmännischen Ausbildung von [Markus Amshove](http://amshove.org) ist lizenziert unter einer [Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International Lizenz](http://creativecommons.org/licenses/by-sa/4.0/).
