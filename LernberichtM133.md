# Lern-Bericht
Michael Saugy

## Einleitung

In diesem Eintrag berichte ich über das Arbeiten mit JSF im Modul 133

## Was habe ich gelernt?

Ich habe gelernt, wie man eine Weiterleitung mithilfe eines Commandlinks verwendet, um eine XHTML-Seite korrekt mit JSF dazustellen.

## Beschreibung

Mit dem unten gezeigten Code ist es möglich, eine Weiterleitung zu einer anderen Seite zu erstellen. Anders als im gewöhnlichen HTML funktioniert der ein Link mit dem ```<a>```-Tag nicht, da die Seite sonst ohne JSF aufgerufen wird. Damit die Seite richtig lädt, muss man einen sogenannten Commandlink verwenden. Dieser Commandlink muss in einem ```<h:Form>``` verwendet werden, damit alles funktioniert.
     
     <h:form> 
         <h:commandLink action="weiter.xhtml" value="Weiter">
     </h:form>
  

https://user-images.githubusercontent.com/112411426/187266571-a66afe3f-663f-464f-941a-155accfb1c8f.mp4


## Verifikation

Durch den Code und das Video ist ersichtlich, dass die Weiterleitung ohne Probleme funktioniert. Auch erkennt man, dass ich den Commandlink problemlos verwenden kann.

# Reflektion zum Arbeitsprozess

Während meiner Arbeit war ich sehr konzentriert und konnte ohne grössere Unterbrüche arbeiten. Des Weiteren habe ich die vorgegebenen Zeiten für die Pausen stets eingehalten.

Leider habe ich sehr lange versucht, eine normale Weiterleitung mithilfe des ```<a>```-Tags zu erstellen. Schlussendlich habe ich dies auch geschafft.  Später stellte sich aber heraus, dass diese Methode zwar funktioniert, jedoch sehr unsicher ist.

Da ich sehr lange gebraucht habe, bis ich den Commandlink entdeckt habe, werde ich den Lehrer in Zukunft früher um Hilfe bitten.
