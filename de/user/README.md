# Benutzerhandbuch

Hier erhalten Sie Informationen, wie Sie das DMS benutzen.

## Inhalt
* Auflistung der Dokumente im Frontend **(DMS-Auflistung)**
    * Dokumente einer Kategorie anzeigen oder ausblenden
    * Alle Dokumente anzeigen oder ausblenden
    * Suchfunktion
* Verwaltungsansicht im Frontend **(DMS-Auflistung)**
	* Dokumente hochladen 
    * Hinweismeldungen (Meldungen die einem bei der Arbeit mit dem ContaoDMS begegnen können ;-) )
    
---

# Auflistung der Dokumente im Frontend (DMS-Auflistung)

**Gliederung der DMS-Auflistung:**

---

* Suchfunktion  

---

<table>
 <tr>
   	<th>Kategorien</th>
    <th>Anzahl</th>
    <th>Auswahl</th>
 </tr>
 <tr>
   	<td>Die Kategorien als Baumstruktur.</td>
    <td>Die Anzahl der in der jeweiligen Kategorie enthaltenden (veröffentlichten) Dokumente.</td>
    <td>Sobald sich Dokumente in einer Kategorie befinden und das Mitglied das Leserecht hat, wird eine Checkbox angezeigt die bei Ativierung die Dokumente der Kategorie anzeigt.
     </td>
 </tr>     
</table>    

---

* Anzahl gefundener Dokumente

---

* Buttons **Alle Dokumente anzeigen** oder **Alle Dokumente ausblenden**

---
**Und jetzt noch mal als Screenshot:**

![Screenshot Auflistung der Dokumente](screenshot_frontend_dms_listing.png)

---

## Dokumente einer Kategorie anzeigen oder ausblenden

Die in einer Kategorie enthaltenen Dokumente lassen sich mit der Checkbox ein-, und ausblenden. 

![Screenshot Dokumente einer Kategorie anzeigen](screenshot_frontend_dms_listing_view_documents_in_selected_category.png)


## Alle Dokumente anzeigen oder ausblenden

Sie können mit Hilfe der Buttons am Ende der Dokumentenliste auch alle Dokumente ein-, bzw. ausblenden

![Screenshot Alle Dokumente ein oder ausblenden](screenshot_frontend_dms_listing_view_all_or_hide_all_documents.png)

---

## Suchfunktion

Es kann nach Dokumenten gesucht werden. Dafür werden die zwei Suchoptionen **Exakte Suche** sowie **Ähnlichkeitssuche** angeboten.

Die Schaltfläche **Zurücksetzen** löscht den Suchfilter wieder.

Als Suchergebnis bleiben die Auswahlfelder der Kategorien eingeblendet, die Dokumente mit dem Suchbegriff enthalten. Alle anderen werden ausgeblendet. 

In der folgenden Abb. wurde bspw. nach "Boskopp" gesucht. Die Kategorie "Äpfel" enhält ein Dokument mit diesem Suchbegriff und das Auswahlfeld wird eingeblendet.

![Screenshot Suchergebnis](screenshot_frontend_dms_listing_searching_documents.png)

---

![Gefundene Dokumente anzeigen](screenshot_frontend_dms_listing_searching_documents_view_documents.png)

---
# Verwaltungsansicht im Frontend (DMS-Verwaltung)
Über die Verwaltungsansicht laden sie Dokumente hoch. Über die Funktion "Verwalten" stehen die Werkzeuge Veröffentlichen oder ausblenden, löschen und Bearbeiten der Dokumenteigenschaften zur Verfügung.

![Screenshot Verwaltungsansicht](screenshot_frontend_dms_management.png)

---

## Dokumente hochladen
Nachfolgend sind die Schritte beschrieben wie sie Dokumente hochladen.

Klicken sie in der Verwaltungsansicht auf **Hochladen**:

![Screenshot Dokument hochladen](screenshot_frontend_dms_management_document_upload.png)

Dann weiter auf **Durchsuchen**:
![Screenshot Dokument Suchen](screenshot_frontend_dms_management_search_upload_document.png)

Wählen sie das hochzuladene Dokument und bestätigen sie mit **Öffnen**:
![Screenshot Dokument lokal auswählen](/manual/de/user/screenshot_frontend_dms_management_search_upload_document_select.png)

Klicken sie nun auf **Hochladen**:
![Screenshot Dokument hochladen](screenshot_frontend_dms_management_upload.png)

Bestimmen sie die **Dokumenteigenschaften**:
![Screenshot Dokumenteigenschaften bestimmen](screenshot_frontend_dms_management_upload_document_description.png)

---

## Hinweismeldungen
Nachfolgend sind Hinweismeldungen aufgeführt, die Ihnen beim Arbeiten mit dem ContaoDMS begegnen können:

* Die nachfolgende Meldung erhalten sie, wenn ein Dateityp hochgeladen wird der für diese Kategorie nicht freigegeben ist. 

![Screenshot Meldung Nicht erlaubter Dateityp](screenshot_frontend_dms_management_message_forbidden_datatyp.png)

* Die folgende Meldung erhalten sie beim Upload, wenn das System festgestellt, dass es noch mindestens ein Dokument mit gleichem Namen in einer anderen Kategorie gibt. 
![Screenshot Dokument mit gleichen Namen in anderer Kategorie schon vorhanden](screenshot_frontend_dms_management_several_document_versions.png)
