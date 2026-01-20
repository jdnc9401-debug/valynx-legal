---
layout: legal
title: "Datenschutzrichtlinie"
lang: de
doc: privacy
---
# Valynx Datenschutzerklärung

**Letzte Aktualisierung: 19. Januar 2026**

Diese Datenschutzerklärung beschreibt unsere Richtlinien und Verfahren zur Erfassung, Verwendung und Offenlegung Ihrer Informationen, wenn Sie die Valynx-Anwendung verwenden, und informiert Sie über Ihre Datenschutzrechte und wie das Gesetz Sie schützt.

Wir verwenden Ihre personenbezogenen Daten, um den Service bereitzustellen und zu verbessern. Durch die Nutzung des Services stimmen Sie der Erfassung und Verwendung von Informationen gemäß dieser Datenschutzerklärung zu.

---

## Auslegung und Definitionen

### Auslegung

Wörter, deren Anfangsbuchstabe großgeschrieben ist, haben die unter den folgenden Bedingungen definierten Bedeutungen. Die folgenden Definitionen haben die gleiche Bedeutung, unabhängig davon, ob sie im Singular oder Plural erscheinen.

### Definitionen

Für die Zwecke dieser Datenschutzerklärung:

- **Konto** bedeutet ein eindeutiges Konto, das für Sie erstellt wurde, um auf unsere Anwendung oder Teile unserer Anwendung zuzugreifen.

- **Anwendung** bezieht sich auf **Valynx**, das von der Firma bereitgestellte Softwareprogramm, verfügbar für Android- und iOS-Mobilgeräte.

- **Firma** (als "die Firma", "Wir", "Uns" oder "Unser" in dieser Vereinbarung bezeichnet) bezieht sich auf **Valynx**.

- **Land** bezieht sich auf: **Spanien**.

- **Gerät** bedeutet jedes Gerät, das auf den Service zugreifen kann, wie ein Mobiltelefon oder ein digitales Tablet.

- **Personenbezogene Daten** sind alle Informationen, die sich auf eine identifizierte oder identifizierbare Person beziehen.

- **Service** bezieht sich auf die Anwendung.

- **Dienstanbieter** bedeutet jede natürliche oder juristische Person, die Daten im Namen der Firma verarbeitet. Es bezieht sich auf Drittunternehmen oder Einzelpersonen, die von der Firma beschäftigt werden, um den Service zu erleichtern, den Service im Namen der Firma bereitzustellen, mit dem Service verbundene Dienstleistungen zu erbringen oder der Firma bei der Analyse zu helfen, wie der Service verwendet wird.

- **Nutzungsdaten** bezieht sich auf automatisch erfasste Daten, die entweder durch die Nutzung des Services oder durch die Infrastruktur des Services selbst generiert werden (z. B. die Dauer eines Seitenbesuchs).

- **Sie** bedeutet die Person, die auf den Service zugreift oder ihn nutzt, oder das Unternehmen oder die andere juristische Person, in deren Namen diese Person auf den Service zugreift oder ihn nutzt, je nachdem.

---

## Erfassung und Verwendung Ihrer personenbezogenen Daten

### Arten der erfassten Daten

#### Personenbezogene Daten

Während Sie unsere Anwendung verwenden, können wir Sie bitten, uns bestimmte persönlich identifizierbare Informationen bereitzustellen, die zur Kontaktaufnahme oder Identifizierung verwendet werden können. Persönlich identifizierbare Informationen können unter anderem Folgendes umfassen:

**Benutzerprofil-Informationen:**
- Name
- Profilfoto (optional, lokal auf Ihrem Gerät gespeichert)
- Bevorzugte Währung (USD, MXN, EUR, COP, ARS, BRL, CAD, CHF, GBP, CLP, PEN, UYU)
- Bevorzugte Sprache (Spanisch, Englisch, Französisch, Italienisch, Portugiesisch, Deutsch)
- Durchschnittliches monatliches Einkommen
- Monatliches Sparziel

**Finanzinformationen:**
- Erfasste Ausgaben und Einnahmen
- Wiederkehrende Ausgaben und deren Zeitpläne
- Ratenkäufe und Zahlungsverfolgung
- Sparziele und deren Fortschritt
- Budgets und festgelegte Limits
- Finanzielle Vermögenswerte (Bankkonten, Bargeld, digitale Geldbörsen)
- Überweisungen zwischen Vermögenswerten
- Benutzerdefinierte Kategorien von Ausgaben und Einnahmen

**Personen-Informationen (für geteilte Ausgaben):**
- Namen von Personen, mit denen Sie Ausgaben teilen
- Beziehung zu diesen Personen (optional)

**Sicherheitsinformationen:**
- Zugriffs-PIN (als SHA256-Hash gespeichert, niemals im Klartext)
- Biometrische Authentifizierungspräferenzen (Face ID / Touch ID)
- Sicherheitsfragen zur PIN-Wiederherstellung (als Hash gespeichert)

**Einstellungen und Präferenzen:**
- Benachrichtigungseinstellungen
- Automatische Backup-Einstellungen
- Abonnementstatus (Testzeitraum, aktives Abonnement)
- Theme-Präferenzen (Hell-/Dunkelmodus)

#### Nutzungsdaten

Nutzungsdaten werden automatisch bei der Nutzung des Services erfasst. **Valynx ist jedoch hauptsächlich für die lokale Nutzung konzipiert**, daher ist die Erfassung von Nutzungsdaten minimal:

- **Firebase Remote Config**: Wir verwenden Firebase Remote Config ausschließlich, um Remote-Konfigurationen zu erhalten (z. B. den Review-Modus der App). **Wir erfassen keine personenbezogenen Daten über Firebase Remote Config**. Diese Funktionalität liest nur vordefinierte Konfigurationswerte.

- **Google Drive (Optional)**: Wenn Sie die Google Drive-Backup-Funktionalität verwenden möchten, ist eine OAuth 2.0-Authentifizierung erforderlich. Zugriffstoken werden lokal auf Ihrem Gerät gespeichert. Backup-Dateien werden in Ihrem Google Drive-Konto unter Ihrer Kontrolle gespeichert. **Wir greifen nicht auf andere Daten aus Ihrem Google Drive-Konto zu**.

- **Lokale Benachrichtigungen**: Benachrichtigungen werden lokal auf Ihrem Gerät geplant und verwaltet. Es werden keine Daten an externe Server für Benachrichtigungen gesendet.

**Wichtig**: Valynx **erfasst KEINE** Nutzungsdaten wie IP-Adressen, Geräte-IDs, Browsing-Informationen oder Diagnosedaten, da die Anwendung hauptsächlich offline und lokal arbeitet.

---

## Verwendung Ihrer personenbezogenen Daten

Die Firma kann personenbezogene Daten für folgende Zwecke verwenden:

- **Bereitstellung und Wartung unseres Services**: Alle Ihre Finanzdaten werden lokal auf Ihrem Gerät mit SQLite gespeichert. Wir verwenden Ihre personenbezogenen Daten ausschließlich, um Anwendungsfunktionen bereitzustellen, wie z. B.:
  - Erfassung und Verfolgung von Ausgaben und Einnahmen
  - Berechnung monatlicher Zusammenfassungen und Finanzanalysen
  - Planung von Benachrichtigungen für wiederkehrende Zahlungen und Ratenkäufe
  - Verwaltung von Budgets und Sparzielen
  - Generierung von Berichten und Datenexporten

- **Verwaltung Ihres Kontos**: Verwaltung Ihres Benutzerprofils und Ihrer Einstellungen innerhalb der Anwendung.

- **Benachrichtigungen**: Senden geplanter lokaler Benachrichtigungen bezüglich:
  - Budget-Warnungen (bei Erreichen von 80%, 90% oder 100% des Limits)
  - Erinnerungen an wiederkehrende Zahlungen
  - Erinnerungen an Ratenkäufe
  - Benachrichtigungen zu Sparzielen

- **Backup und Wiederherstellung**: Wenn Sie die Google Drive-Backup-Funktionalität verwenden, werden Ihre Daten in Ihrem Google Drive-Konto gespeichert, um die Wiederherstellung auf anderen Geräten zu ermöglichen. Backups können auch lokal auf Ihrem Gerät durchgeführt werden.

- **Sicherheit**: Verwendung Ihrer PIN (gehasht) und biometrischen Präferenzen zum Schutz des Zugriffs auf Ihre Finanzinformationen.

- **Serviceverbesserung**: Verwendung aggregierter und anonymisierter Daten (falls vorhanden) zur Verbesserung der Anwendungsfunktionen.

**Wir teilen Ihre personenbezogenen Daten nicht mit Dritten**, außer in folgenden Situationen:

- **Mit Dienstanbietern**:
  - **Google Drive**: Nur wenn Sie die Cloud-Backup-Funktionalität verwenden. Daten werden in Ihrem eigenen Google Drive-Konto unter Ihrer Kontrolle gespeichert.
  - **Firebase**: Nur zum Abrufen von Remote-Konfigurationen (Remote Config). Es werden keine personenbezogenen Daten geteilt.

- **Mit Ihrer ausdrücklichen Zustimmung**: Wir teilen Ihre Daten nur, wenn Sie uns Ihre ausdrückliche Zustimmung dazu geben.

---

## Aufbewahrung Ihrer personenbezogenen Daten

**Lokale Speicherung**: Die meisten Ihrer personenbezogenen Daten werden lokal auf Ihrem Gerät mit SQLite und AsyncStorage gespeichert. Diese Daten verbleiben auf Ihrem Gerät, bis Sie:
- Die Anwendung löschen
- Daten manuell aus der Anwendung löschen
- Ein Werksreset Ihres Geräts durchführen

**Google Drive-Backup (Optional)**: Wenn Sie die Google Drive-Backup-Funktionalität verwenden, werden Backup-Dateien in Ihrem Google Drive-Konto gespeichert. Sie können diese Backups jederzeit aus Ihrem Google Drive-Konto oder aus der Anwendung löschen.

**Aufbewahrung von Sicherheitsdaten**: PIN- und Sicherheitsfragen-Hashes werden aufbewahrt, solange die Sicherheitsfunktion aktiv ist. Sie können diese Daten löschen, indem Sie die PIN in den Anwendungseinstellungen deaktivieren.

Die Firma behält Ihre personenbezogenen Daten nur so lange auf, wie es für die in dieser Datenschutzerklärung festgelegten Zwecke erforderlich ist und um gesetzliche Verpflichtungen zu erfüllen, Streitigkeiten zu lösen und Vereinbarungen durchzusetzen.

---

## Übertragung Ihrer personenbezogenen Daten

**Primäre Speicherung**: Ihre personenbezogenen Daten werden hauptsächlich auf Ihrem lokalen Gerät gespeichert. **Wir übertragen Ihre personenbezogenen Daten nicht an externe Server**, außer im optionalen Fall des Google Drive-Backups.

**Google Drive-Backup (Optional)**: Wenn Sie die Google Drive-Backup-Funktionalität verwenden, können Ihre Daten auf die Server von Google übertragen und dort gespeichert werden, die sich außerhalb Ihres Wohnsitzlandes befinden können. Durch die Nutzung dieser Funktionalität stimmen Sie zu, dass Ihre Daten gemäß den Datenschutzrichtlinien von Google auf die Server von Google übertragen werden können.

**Firebase Remote Config**: Die Kommunikation mit Firebase Remote Config umfasst nur das Lesen von Konfigurationswerten. Es werden keine personenbezogenen Daten an Firebase übertragen.

Ihre Informationen können auf Computer übertragen und dort gespeichert werden, die sich außerhalb Ihres Landes befinden, wo die Datenschutzgesetze unterschiedlich sein können. Durch die Annahme dieser Richtlinie und die Nutzung optionaler Cloud-Backup-Funktionen stimmen Sie einer solchen Übertragung zu.

---

## Löschen Ihrer personenbezogenen Daten

Sie haben das Recht, die Löschung Ihrer personenbezogenen Daten zu verlangen. Sie können dies auf folgende Weise tun:

**Aus der Anwendung:**
- Einzelne Daten löschen (Ausgaben, Einnahmen, Personen, Kategorien usw.) aus den jeweiligen Abschnitten der Anwendung
- Ihr Benutzerprofil aus den Einstellungen löschen
- Backups aus dem Backup-Bereich löschen

**Vollständige Löschung:**
- Die Deinstallation der Anwendung löscht alle lokal auf Ihrem Gerät gespeicherten Daten
- Wenn Sie Google Drive-Backups verwendet haben, müssen Sie diese manuell aus Ihrem Google Drive-Konto löschen

**Direkte Anfrage:**
Sie können uns direkt unter **valynxsolutions@outlook.com** kontaktieren, um die Löschung aller Daten anzufordern, die möglicherweise in unseren Systemen gespeichert sind (falls vorhanden).

---

## Offenlegung Ihrer personenbezogenen Daten

Die Firma kann Ihre personenbezogenen Daten in folgenden Situationen offenlegen:

### Geschäftstransaktionen

Wenn die Firma an einer Fusion, Übernahme oder einem Vermögensverkauf beteiligt ist, können Ihre personenbezogenen Daten übertragen werden. Wir werden Sie benachrichtigen, bevor Ihre personenbezogenen Daten übertragen werden und einer anderen Datenschutzerklärung unterliegen.

### Rechtliche Anforderungen

Unter bestimmten Umständen kann die Firma verpflichtet sein, Ihre personenbezogenen Daten offenzulegen, wenn dies gesetzlich vorgeschrieben ist oder als Reaktion auf gültige Anfragen von Behörden (z. B. ein Gericht oder eine Regierungsbehörde).

### Andere rechtliche Anforderungen

Die Firma kann Ihre personenbezogenen Daten offenlegen, wenn sie in gutem Glauben davon ausgeht, dass eine solche Maßnahme erforderlich ist, um:
- Eine gesetzliche Verpflichtung zu erfüllen
- Die Rechte oder das Eigentum der Firma zu schützen und zu verteidigen
- Mögliches Fehlverhalten in Verbindung mit dem Service zu verhindern oder zu untersuchen
- Die persönliche Sicherheit der Service-Nutzer oder der Öffentlichkeit zu schützen
- Vor rechtlicher Haftung zu schützen

---

## Sicherheit Ihrer personenbezogenen Daten

Die Sicherheit Ihrer personenbezogenen Daten ist uns wichtig, aber denken Sie daran, dass keine Übertragungsmethode über das Internet oder elektronische Speichermethode zu 100% sicher ist. Obwohl wir uns bemühen, kommerziell akzeptable Mittel zum Schutz Ihrer personenbezogenen Daten zu verwenden, können wir deren absolute Sicherheit nicht garantieren.

**Implementierte Sicherheitsmaßnahmen:**

- **Verschlüsselte lokale Speicherung**: Daten werden lokal auf Ihrem Gerät mit SQLite gespeichert, was einen grundlegenden Schutz bietet.

- **PIN-Authentifizierung**: Ihre PIN wird als SHA256-Hash gespeichert, niemals im Klartext. Das bedeutet, dass selbst wenn jemand auf die Datenbank zugreift, er Ihre ursprüngliche PIN nicht sehen kann.

- **Biometrische Authentifizierung**: Wir bieten Unterstützung für Face ID (iOS) und Touch ID / Fingerabdruck (Android) als zusätzliche Authentifizierungsmethode. Biometrische Daten werden vom Betriebssystem Ihres Geräts verwaltet und niemals in unserer Anwendung gespeichert.

- **Sicherheitsfragen**: Antworten auf Sicherheitsfragen werden ebenfalls als SHA256-Hashes gespeichert.

- **Optionales Backup**: Wenn Sie die Google Drive-Backup-Funktionalität verwenden, werden Dateien in Ihrem Google Drive-Konto gespeichert, das durch die Sicherheitsmaßnahmen von Google geschützt ist.

**Sicherheitsempfehlungen:**
- Verwenden Sie eine starke PIN (4-6 Ziffern)
- Aktivieren Sie die biometrische Authentifizierung, wenn Ihr Gerät dies unterstützt
- Richten Sie Sicherheitsfragen zur PIN-Wiederherstellung ein
- Halten Sie Ihr Gerät mit einem Passcode oder Muster geschützt
- Führen Sie regelmäßige Backups Ihrer Daten durch

---

## Datenschutz von Kindern

Unser Service **richtet sich nicht an Kinder unter 13 Jahren** (oder dem Mindestalter, das in Ihrer Gerichtsbarkeit erforderlich ist, um der Verarbeitung personenbezogener Daten zuzustimmen).

**Wir erfassen nicht wissentlich persönlich identifizierbare Informationen von Kindern unter 13 Jahren**. Wenn Sie ein Elternteil oder Erziehungsberechtigter sind und wissen, dass Ihr Kind uns personenbezogene Daten bereitgestellt hat, kontaktieren Sie uns bitte. Wenn wir feststellen, dass wir personenbezogene Daten von Personen unter 13 Jahren ohne Überprüfung der elterlichen Zustimmung erfasst haben, ergreifen wir Maßnahmen, um diese Informationen von unseren Servern zu entfernen.

Wenn wir auf Zustimmung als Rechtsgrundlage für die Verarbeitung Ihrer Informationen angewiesen sind und Ihr Land die elterliche Zustimmung erfordert, können wir die Zustimmung Ihrer Eltern verlangen, bevor wir diese Informationen erfassen und verwenden.

---

## Links zu anderen Websites

Unsere Anwendung kann Links zu anderen Websites enthalten, die nicht von uns betrieben werden. Wenn Sie auf einen Link eines Dritten klicken, werden Sie zur Website dieses Dritten weitergeleitet. Wir empfehlen Ihnen dringend, die Datenschutzerklärung jeder Website zu überprüfen, die Sie besuchen.

Wir haben keine Kontrolle über und übernehmen keine Verantwortung für den Inhalt, die Datenschutzrichtlinien oder Praktiken von Websites oder Diensten Dritter.

---

## Änderungen an dieser Datenschutzerklärung

Wir können unsere Datenschutzerklärung von Zeit zu Zeit aktualisieren. Wir werden Sie über Änderungen informieren, indem wir die neue Datenschutzerklärung auf dieser Seite veröffentlichen und das Datum der "Letzten Aktualisierung" oben in dieser Datenschutzerklärung aktualisieren.

Wir können Sie auch per E-Mail und/oder durch einen auffälligen Hinweis in unserer Anwendung benachrichtigen, bevor die Änderung wirksam wird.

Wir empfehlen Ihnen, diese Datenschutzerklärung regelmäßig auf Änderungen zu überprüfen. Änderungen an dieser Datenschutzerklärung werden wirksam, wenn sie auf dieser Seite veröffentlicht werden.

---

## Ihre Datenschutzrechte gemäß DSGVO (Datenschutz-Grundverordnung)

Wenn Sie Einwohner des Europäischen Wirtschaftsraums (EWR) oder des Vereinigten Königreichs sind, haben Sie bestimmte Datenschutzrechte. Die Firma beabsichtigt, angemessene Schritte zu unternehmen, um Ihnen zu ermöglichen, Ihre personenbezogenen Daten zu korrigieren, zu ändern, zu löschen oder die Verwendung einzuschränken.

Wenn Sie über die personenbezogenen Daten informiert werden möchten, die wir über Sie haben, und wenn Sie möchten, dass sie aus unseren Systemen entfernt werden, kontaktieren Sie uns bitte unter **valynxsolutions@outlook.com**.

Unter bestimmten Umständen haben Sie folgende Datenschutzrechte:

- **Das Recht auf Auskunft**: Sie haben das Recht, Kopien Ihrer personenbezogenen Daten anzufordern.

- **Das Recht auf Berichtigung**: Sie haben das Recht zu verlangen, dass wir alle Informationen korrigieren, die Sie für ungenau halten. Sie haben auch das Recht zu verlangen, dass wir Informationen vervollständigen, die Sie für unvollständig halten.

- **Das Recht auf Löschung**: Sie haben das Recht zu verlangen, dass wir Ihre personenbezogenen Daten unter bestimmten Bedingungen löschen.

- **Das Recht auf Einschränkung der Verarbeitung**: Sie haben das Recht zu verlangen, dass wir die Verarbeitung Ihrer personenbezogenen Daten unter bestimmten Bedingungen einschränken.

- **Das Recht auf Datenübertragbarkeit**: Sie haben das Recht zu verlangen, dass wir die von uns erfassten Daten an eine andere Organisation oder direkt an Sie übertragen, unter bestimmten Bedingungen.

- **Das Widerspruchsrecht**: Sie haben das Recht, der Verarbeitung Ihrer personenbezogenen Daten unter bestimmten Bedingungen zu widersprechen.

- **Das Recht auf Widerruf der Einwilligung**: Sie haben das Recht, Ihre Einwilligung zu widerrufen, wenn sich die Firma auf Ihre Einwilligung zur Verarbeitung Ihrer personenbezogenen Daten verlassen hat.

Sie können diese Rechte ausüben, indem Sie uns unter **valynxsolutions@outlook.com** kontaktieren.

Bitte beachten Sie, dass wir Sie möglicherweise bitten, Ihre Identität zu überprüfen, bevor wir auf solche Anfragen antworten.

---

## Ihre Datenschutzrechte gemäß CCPA (California Consumer Privacy Act)

Wenn Sie Einwohner von Kalifornien sind, haben Sie bestimmte Rechte gemäß dem California Consumer Privacy Act (CCPA). Diese Rechte umfassen:

- **Das Recht zu wissen**: Sie haben das Recht zu verlangen, dass wir Sie über Folgendes informieren:
  - Die Kategorien personenbezogener Informationen, die wir über Sie erfassen
  - Die Kategorien von Quellen, aus denen wir personenbezogene Informationen erfassen
  - Der geschäftliche oder kommerzielle Zweck für die Erfassung oder den Verkauf personenbezogener Informationen
  - Die Kategorien von Dritten, mit denen wir personenbezogene Informationen teilen
  - Die spezifischen Teile personenbezogener Informationen, die wir über Sie erfassen

- **Das Recht auf Löschung**: Sie haben das Recht zu verlangen, dass wir Ihre personenbezogenen Informationen löschen, die wir von Ihnen erfasst haben, vorbehaltlich bestimmter Ausnahmen.

- **Das Recht auf Opt-out**: Sie haben das Recht, sich gegen den "Verkauf" personenbezogener Informationen zu entscheiden. **Valynx verkauft KEINE personenbezogenen Informationen**.

- **Das Recht auf Nichtdiskriminierung**: Wir werden Sie nicht diskriminieren, weil Sie Ihre Rechte gemäß CCPA ausüben.

Um diese Rechte auszuüben, können Sie uns unter **valynxsolutions@outlook.com** kontaktieren. Wir werden auf Ihre Anfrage innerhalb von 45 Werktagen antworten.

---

## Rechte von Kindern

**Schutz von Kindern unter 13 Jahren**: Wie oben erwähnt, richtet sich unser Service nicht an Kinder unter 13 Jahren. Wir erfassen nicht wissentlich personenbezogene Informationen von Kindern unter 13 Jahren.

**Kinder im Alter von 13 bis 16 Jahren (DSGVO)**: Wenn Sie zwischen 13 und 16 Jahre alt sind und im EWR oder im Vereinigten Königreich wohnen, erfordert die Verarbeitung Ihrer personenbezogenen Daten die Zustimmung Ihrer Eltern oder Erziehungsberechtigten.

**Kinder im Alter von 13 bis 18 Jahren (CCPA)**: Wenn Sie zwischen 13 und 18 Jahre alt sind und in Kalifornien wohnen, können Sie die Verarbeitung Ihrer personenbezogenen Daten selbst autorisieren, haben aber das Recht, jederzeit die Löschung Ihrer Daten zu verlangen.

Wenn Sie ein Elternteil oder Erziehungsberechtigter sind und glauben, dass Ihr minderjähriges Kind uns ohne Ihre Zustimmung personenbezogene Daten bereitgestellt hat, kontaktieren Sie uns bitte sofort unter **valynxsolutions@outlook.com**.

---

## Kontakt

Wenn Sie Fragen zu dieser Datenschutzerklärung haben, können Sie uns kontaktieren:

**Per E-Mail:**
📧 **valynxsolutions@outlook.com**

**Firmeninformationen:**
- **Name**: Valynx
- **Anwendung**: Valynx (Persönliche Finanz-App)

---

## Annahme dieser Richtlinie

Durch die Nutzung der Valynx-Anwendung akzeptieren Sie diese Datenschutzerklärung. Wenn Sie dieser Richtlinie nicht zustimmen, verwenden Sie bitte unsere Anwendung nicht.

Wenn Sie Fragen oder Bedenken zu dieser Datenschutzerklärung haben, zögern Sie bitte nicht, uns zu kontaktieren.
