---
title: <mtr>
slug: Web/MathML/Element/mtr
tags:
  - MathML
  - MathML:Element
  - Referenz
translation_of: Web/MathML/Element/mtr
---
{{MathMLRef}}

Das `<mtr>-E`lement erzeugt eine Zeile in einer Tabelle oder Matrix. Es ist innerhalb von {{ MathMLElement("mtable") }} erlaubt. `<mtr>` ähnelt dem {{ HTMLElement("tr") }}-Element in [HTML](/de/docs/HTML).

## Attribute

- class, id, style
  - : Zur Einbindung von [CSS-Stylesheets](/de/docs/Web/CSS) und zur direkten Anwendung von CSS-Angaben auf einzelne Elemente.
- columnalign
  - : Gibt die _horizontale_ Ausrichtung des Inhalts der Tabellenzellen an. Dieses Attribut für die Zeile `<mtr>` überschreibt entsprechende Angaben für `columnalign` für das Elternelement `<mtable>`. Die Angabe mehrerer Werte ist erlaubt, diese werden in der angegebenen Reihenfolge auf die Spalten angewandt (z.B. `columnalign="left right center"`). Mögliche Werte sind `left`, `center` und `right`.
- groupalign
  - : {{ unimplemented_inline() }}
- href
  - : Mit diesem Attribut kann ein Link gesetzt werden.
- mathbackground
  - : Die Hintergrundfarbe. Folgende Notationen sind erlaubt: [`#rgb`](https://developer.mozilla.org/de/docs/Web/CSS/Farben#rgb%28%29), [`#rrggbb`](https://developer.mozilla.org/de/docs/Web/CSS/Farben#rgb%28%29) und [HTML-Farbnamen](/de/docs/Web/CSS/Farben#Werte).
- mathcolor
  - : Die Textfarbe. Folgende Notationen sind erlaubt: [`#rgb`](https://developer.mozilla.org/de/docs/Web/CSS/Farben#rgb%28%29), [`#rrggbb`](https://developer.mozilla.org/de/docs/Web/CSS/Farben#rgb%28%29) und [HTML-Farbnamen](/de/docs/Web/CSS/Farben#Werte).
- rowalign
  - : Gibt die _vertikale_ Ausrichtung des Inhalts der Tabellenzellen an. Dieses Attribut für die Zeile `<mtr>` überschreibt entsprechende Angaben für `rowalign` für das Elternelement `<mtable>`. Die Angabe mehrerer Werte ist erlaubt, diese werden dann in der angegebenen Reihenfolge auf die Zeilen angewandt, (z.B. `rowalign="top bottom axis"`). Mögliche Werte sind `axis`, `baseline`, `bottom`, `center` und `top`.

## Spezifikationen

| Standard                                                                         | Status                       | Bemerkung             |
| -------------------------------------------------------------------------------- | ---------------------------- | --------------------- |
| {{ SpecName('MathML3', 'chapter3.html#presm.mtr', 'mtr') }} | {{ Spec2('MathML3') }} | Current specification |
| {{ SpecName('MathML2', 'chapter3.html#presm.mtr', 'mtr') }} | {{ Spec2('MathML2') }} | Initial specification |

## Browserkompatibilität

{{Compat}}

## Siehe auch

- {{ MathMLElement("mtable") }}
- {{ MathMLElement("mtd") }}