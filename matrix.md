# Tritt unserer Matrix-Instanz bei

Heart of Code hat ein Community-Server, hier ist der Link, um dazu beizutreten: https://matrix.to/#/#community:matrix.heartofcode.org

Wenn du noch nicht weißt, was Matrix ist, unten findest du eine Anleitung, wie du es einrichtest.

### Über Matrix
Wir nutzen [Matrix](https://matrix.org), eine sichere und dezentrale Kommunikationsplattform, um zusammenzuarbeiten und uns auszutauschen. Wenn du auf dem Laufenden bleiben und mit anderen Leuten aus der Heart of Code chatten möchtest, komm gerne in unsere Matrix-Instanz!

### Einrichtung

**Schritt 1: Installiere einen Matrix-Client**

Um Matrix zu nutzen, brauchst du eine App, einen sogenannten *Client*. Es gibt viele davon, wir empfehlen aber **Element**, den am weitesten verbreiteten. Element ist kostenlos und für alle Geräte verfügbar:

* **Im Browser:** öffne https://app.element.io. Du musst nichts installieren.
* **Auf dem Computer:** lade Element Desktop unter https://element.io/download herunter.
* **Auf dem Handy:** installiere **Element X** aus dem App Store oder von Google Play. Falls sich Element X nicht mit deinem Homeserver verbinden kann (siehe Schritt 2), nimm stattdessen die klassische **Element**-App.

Element ist nur die App, dein Account liegt nicht dort. Du kannst dich in jedem Element mit einem Account von jedem beliebigen Homeserver anmelden und denselben Account auf mehreren Geräten gleichzeitig nutzen. Wenn du auf alternative Clients neugierig bist, schau unter https://matrix.org/ecosystem/clients/, um verschiedene Clients zu vergleichen.

**Schritt 2: Registriere einen Account**

Falls du noch keinen Matrix-Account hast, registriere nach dem Start des Clients einen neuen. Dafür kannst du deine E-Mail-Adresse oder Telefonnummer verwenden.

Der Matrix-Homeserver der Heart of Code verwaltet keine Accounts. Du musst dich also bei einem anderen Homeserver registrieren.

Wenn du Matrix zum ersten Mal ausprobierst, kannst du den Homeserver matrix.org wählen. Schau dir aber gerne die folgenden Anleitungen an, um die Vor- und Nachteile zu verstehen und einen passenden Homeserver auszuwählen:

* [„Join Matrix!“-Anleitung: Grundlagen](https://joinmatrix.org/guide/#set-up-your-own-homeserver-or-join-an-existing-homeserver)
* https://servers.joinmatrix.org/users.html

Klicke in Element auf „Konto erstellen“. Als Homeserver ist matrix.org voreingestellt. Klicke daneben auf „Bearbeiten“, wenn du einen anderen nutzen möchtest.

**Schritt 3: Speichere deinen Wiederherstellungsschlüssel**

Bei der ersten Anmeldung fragt dich Element, ob du die *Wiederherstellung* ('recovery') (manchmal auch *secure backup* genannt) einrichten möchtest. Mach das und bewahre den Wiederherstellungsschlüssel an einem sicheren Ort auf, zum Beispiel in einem Passwortmanager. Du brauchst ihn, um deine verschlüsselten Nachrichten auf neuen Geräten zu lesen. Warum, erfährst du unten unter [Über Verschlüsselung](#uber-verschlusselung).

**Schritt 4: Tritt unserem Matrix-Raum bei**

Sobald dein Account eingerichtet ist, such in der Suchliste deines Clients nach der ID oder dem Namen unseres Hauptraums und tritt ihm bei. Unsere Raum-ID lautet: [`#community:matrix.heartofcode.org`](https://matrix.to/#/#community:matrix.heartofcode.org).

**Schritt 5: Richte Benachrichtigungen ein**

Passe deine Benachrichtigungseinstellungen so an, dass du wichtige Neuigkeiten und Nachrichten mitbekommst.

**Schritt 6: Leg los!**

Stell dich gerne vor, stell Fragen und mach bei den Diskussionen mit den anderen Heart-of-Code-Leuten mit!

Viel Spaß und willkommen in unserer Matrix-Instanz!

### Über Verschlüsselung

Matrix kann Nachrichten *Ende-zu-Ende-verschlüsseln*, sodass nur die Leute im Gespräch sie lesen können, nicht einmal die Server dazwischen.

**Verschlüsselung wird pro Raum eingestellt.** Du musst selbst nichts tun: In einem verschlüsselten Raum verschlüsselt deine App jede Nachricht automatisch. Direktnachrichten und private Räume sind meist verschlüsselt, öffentliche Räume oft nicht. Dein Client zeigt dir in der Regel mit einem Symbol, etwa einem Schild oder Schloss, an, ob ein Raum verschlüsselt ist.

**Dein Wiederherstellungsschlüssel hält deinen Verlauf lesbar.** Die Schlüssel zum Lesen verschlüsselter Nachrichten liegen auf deinen Geräten, nicht auf dem Server. Wenn du dich auf einem neuen Gerät anmeldest oder nach einer Abmeldung wieder anmeldest, brauchst du deinen Wiederherstellungsschlüssel (aus Schritt 3), um ältere Nachrichten zu lesen. Wenn du ihn verlierst und nirgendwo sonst angemeldet bist, lassen sich diese Nachrichten nicht wiederherstellen.

Wenn du „Entschlüsselung nicht möglich“ siehst, prüfe, ob die Wiederherstellung eingerichtet ist und ob du dein Gerät verifiziert hast, als Element dich darum gebeten hat.
