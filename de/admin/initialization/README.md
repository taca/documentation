# Initialisierung

Hier erhalten Sie Informationen über die Initialisierung.

**Inhalt**
<!-- toc -->


## Mitglieder und Mitgliedergruppen anlegen

Bevor man mit dem eigentlichen Aufbau der Dokumentenablage beginnt (also Kategorien anlegt, Zugriffsrechte zuordnet usw.), sollten sie im Vorfeld über die Benutzerverwaltung von Contao Mitglieder und Mitgliedergruppen anlegen

Dies kann zwar auch zu einem späteren Zeitpunkt erfolgen. Allerdings macht das Vorhandensein von Mitgliedergruppen spätestens beim Anlegen der Kategorien die Arbeitsschritte effizienter. 

![Screenshot Benutzerverwaltung](screenshot_user_management.png)


## Dateityp-Sets erstellen
Dateityp-Sets enthalten erlaubte Dateitypen die in eine Kategorie abgelegt werden dürfen. Ein Set muss mindestens ein erlaubten Dateityp enthalten.
Die Sets stehen dann bei der Neuanlage von Kategorien bzw. Anpassung von bestehenden Kategorien zur Verfügung und können leicht ausgewählt werden. Dateityp-Sets erleichtern die Zuweisung erlaubter Dateitypen die in eine Kategorie abgelegt werden dürfen erheblich.

![Screenshot Werkzeug Dateityp-Sets](screenshot_datatype-set.png)


1. Im Menü unter DMS
2. Dateityp-Sets
3. dann auf **„Neues Dateityp-Set“**

![Screenshot Neues Dateityp-Set anlegen](screenshot_add_new_datatyp_set.png)

* **Name:** Aussagekräftigen Namen vergeben (z.B. Word Dokumente)
* **Beschreibung:** optionale Angabe einer Beschreibung
* **Erlaubte Dateitypen:** doc,docx (Gross oder Kleinschreibung spielt keine Rolle)  
Sollen mehrere Dateitypen in einem Set enthalten sein, werden diese durch Komma getrennt eingetragen. Z.B. doc, docx oder jpg, gif, tif 
* **Dateityp-Set veröffentlichen:** Checkbox aktivieren

![Screenshot Dateityp-Sets konfigurieren](screenshot_datatyp_set_settings.png)


**Speichern** nicht vergessen

Jetzt hat man ein Dateityp-Set vom Typ *doc,docx* angelegt.

Auf diese Weise können beliebig viele Sets angelegt werden.

![Screenshot Dateityp-Sets Liste](screenshot_file_type_sets_list.png)

Informationen wie sie **Dateityp-Sets** weiterverarbeiten, z.B. über die Vererbung, erhalten sie im Kapitel [Kategorien](../views/categories.md) im Abschnitt **Kategorieeinstellungen** --> Erlaubte Dateitypen
