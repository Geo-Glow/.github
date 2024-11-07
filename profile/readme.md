# GeoGlow Organisation

GeoGlow ist ein innovatives Gadget, das Freunden dabei hilft, ihre Beziehung zu vertiefen, indem es eine neuartige Form der visuellen Kommunikation bietet. GeoGlow ermöglicht es Freunden, Eindrücke aus ihrem täglichen Leben auf eine unaufdringliche und beiläufige Weise zu teilen. Durch eine intuitive App können einfache visuelle Signale vermittelt werden.

Die App erlaubt es, aus einem aufgenommenen Bild die zentralen Farben zu extrahieren und diese an die Nanoleafs der Freunde zu übertragen. Dies ermöglicht es, die eigenen Freunde mehr am eigenen Leben teilhaben zu lassen, indem sie eine abstrakte Darstellung der Umgebung erhalten, in der man sich befindet. Die Idee ist, dass Fotos der Umgebung aufgenommen werden, und durch die abstrahierten Farben den Freunden auf eine kreative Art und Weise vermittelt wird, wo man sich gerade befindet.

GeoGlow stellt sicher, dass Freunde nicht mit Informationen überflutet werden. Stattdessen liefert es einen Anstoß zur tieferen, persönlichen Kommunikation. Zum Beispiel kann über die empfangenen Farben gerätselt werden: Was war wohl das ursprüngliche Bild oder die Umgebung? Wenn mehr Informationen zum Originalbild gewünscht sind, können Freunde in direkten Kontakt treten und so die emotionale Bindung stärken.

## Architektur

Das GeoGlow-System gliedert sich in verschiedene Komponenten. Zurzeit werden hauptsächlich Nanoleafs unterstützt. Jeder Nutzer sollte daher Nanoleafs zu Hause haben, um die volle Funktionalität nutzen zu können. Die API von Nanoleaf ist nur im selben Netzwerk verfügbar, in dem sich die Nanoleafs befinden, daher gibt es eine zusätzliche Komponente: den GeoGlow-Controller.

Dieser Mikrocontroller (ESP8266) fungiert als Brücke zwischen den Nanoleafs (bzw. der API) und der GeoGlow-App. Diese App ist nicht nur benutzerfreundlich, sondern auch darauf ausgelegt, die Aufnahme von Fotos, die Extraktion von Farben und die Übertragung an Freunde so einfach wie möglich zu gestalten. Technisch gesehen, werden die Daten an die jeweiligen GeoGlow-Controller gesendet und nicht direkt an die Nanoleafs. Die Controller verarbeiten die empfangenen Daten und steuern daraufhin das Aufleuchten der Paneele.

Durch diese Architektur wird ein reibungsloses und inspirierendes Benutzererlebnis geboten, das sowohl einfach zu bedienen als auch emotional bereichernd ist. GeoGlow verschafft eine neue Dimension der Kommunikation und bringt Freunde auf eine subtile, dafür aber kreative Weise näher zusammen.
