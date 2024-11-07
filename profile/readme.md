# GeoGlow Organisation
*(english version below)*

GeoGlow ist ein innovatives Gadget, das Freunden dabei hilft, ihre Beziehung zu vertiefen, indem es eine neuartige Form der visuellen Kommunikation bietet. GeoGlow ermöglicht es Freunden, Eindrücke aus ihrem täglichen Leben auf eine unaufdringliche und beiläufige Weise zu teilen. Durch eine intuitive App können einfache visuelle Signale vermittelt werden.

Die App erlaubt es, aus einem aufgenommenen Bild die zentralen Farben zu extrahieren und diese an die Nanoleafs der Freunde zu übertragen. Dies ermöglicht es, die eigenen Freunde mehr am eigenen Leben teilhaben zu lassen, indem sie eine abstrakte Darstellung der Umgebung erhalten, in der man sich befindet. Die Idee ist, dass Fotos der Umgebung aufgenommen werden, und durch die abstrahierten Farben den Freunden auf eine kreative Art und Weise vermittelt wird, wo man sich gerade befindet.

GeoGlow stellt sicher, dass Freunde nicht mit Informationen überflutet werden. Stattdessen liefert es einen Anstoß zur tieferen, persönlichen Kommunikation. Zum Beispiel kann über die empfangenen Farben gerätselt werden: Was war wohl das ursprüngliche Bild oder die Umgebung? Wenn mehr Informationen zum Originalbild gewünscht sind, können Freunde in direkten Kontakt treten und so die emotionale Bindung stärken.

## Architektur

Das GeoGlow-System gliedert sich in verschiedene Komponenten. Zurzeit werden hauptsächlich Nanoleafs unterstützt. Jeder Nutzer sollte daher Nanoleafs zu Hause haben, um die volle Funktionalität nutzen zu können. Die API von Nanoleaf ist nur im selben Netzwerk verfügbar, in dem sich die Nanoleafs befinden, daher gibt es eine zusätzliche Komponente: den GeoGlow-Controller.

Dieser Mikrocontroller (ESP8266) fungiert als Brücke zwischen den Nanoleafs (bzw. der API) und der GeoGlow-App. Diese App ist nicht nur benutzerfreundlich, sondern auch darauf ausgelegt, die Aufnahme von Fotos, die Extraktion von Farben und die Übertragung an Freunde so einfach wie möglich zu gestalten. Technisch gesehen, werden die Daten an die jeweiligen GeoGlow-Controller gesendet und nicht direkt an die Nanoleafs. Die Controller verarbeiten die empfangenen Daten und steuern daraufhin das Aufleuchten der Paneele.

Durch diese Architektur wird ein reibungsloses und inspirierendes Benutzererlebnis geboten, das sowohl einfach zu bedienen als auch emotional bereichernd ist. GeoGlow verschafft eine neue Dimension der Kommunikation und bringt Freunde auf eine subtile, dafür aber kreative Weise näher zusammen.

# GeoGlow Organization

GeoGlow is an innovative gadget that helps friends deepen their relationship by offering a novel form of visual communication. GeoGlow allows friends to share impressions from their daily lives in a non-intrusive and casual way. Through an intuitive app, simple visual signals can be conveyed.

The app allows for the extraction of central colors from a captured image and transmits them to the friends' Nanoleafs. This enables friends to be more involved in each other's lives by receiving an abstract representation of the environment one is in. The idea is to capture photos of the surroundings and creatively convey to friends, through the abstracted colors, where one is currently located.

GeoGlow ensures that friends are not overwhelmed with information. Instead, it provides a stimulus for deeper, personal communication. For example, the received colors can be a guessing game: What might the original image or environment have been? If more information about the original image is desired, friends can get in direct contact and thus strengthen their emotional bond.

## Architecture

The GeoGlow system is divided into various components. Currently, mainly Nanoleafs are supported. Therefore, each user should have Nanoleafs at home to fully utilize the functionality. The Nanoleaf API is only available within the same network as the Nanoleafs, hence an additional component is required: the GeoGlow Controller.

This microcontroller (ESP8266) serves as a bridge between the Nanoleafs (or the API) and the GeoGlow app. This app is not only user-friendly but also designed to make capturing photos, extracting colors, and transmitting them to friends as simple as possible. Technically, the data is sent to the respective GeoGlow Controllers and not directly to the Nanoleafs. The controllers process the received data and subsequently control the illumination of the panels.

Through this architecture, a seamless and inspiring user experience is provided, which is both easy to use and emotionally enriching. GeoGlow introduces a new dimension of communication and brings friends closer together in a subtle yet creative way.
