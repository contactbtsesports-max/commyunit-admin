# Discord Bot Configuration

## Bot Information

**Bot Name:** Commyunit Admin

### Erforderliche Links

#### 1. Datenschutzerklärung URL
Eine Link zur Datenschutzerklärung deiner Anwendung
- **Beispiel:** `https://example.com/privacy`
- **Erforderlich für:** Discord Developer Portal
- **Aktueller Wert:** `[BITTE EINFÜGEN]`

#### 2. Deep-Link URL
Die URL, die geöffnet wird, wenn ein Benutzer eine Aktivitätseinladung in der Discord-Mobile-App annimmt
- **Format:** `discord://activities/{APP_ID}/{INSTANCE_ID}`
- **Beispiel:** `discord://activities/1234567890/activity-instance-123`
- **Aktueller Wert:** `[BITTE EINFÜGEN]`

### Bot Berechtigungen

```
- Administrator
- Manage Guild
- Manage Roles
- Manage Channels
- Manage Messages
- Kick Members
- Ban Members
- View Audit Log
```

### OAuth2 Scopes

```
- bot
- applications.commands
```

## Discord Developer Portal Einrichtung

1. Gehe zu https://discord.com/developers/applications
2. Erstelle eine neue Anwendung
3. Gehe zum "OAuth2" Tab
4. Kopiere die **Client ID** (wird zu APP_ID)
5. Gehe zum "Bot" Tab
6. Erstelle einen Bot
7. Kopiere den **Token** (DISCORD_TOKEN)
8. Trage die Datenschutzerklärung URL ein
9. Konfiguriere die Deep-Link URL

## Umgebungsvariablen

Siehe `.env.example` für alle erforderlichen Variablen.
