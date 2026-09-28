# NotesAI Privacy Policy

Publisher: Monad Cosmos Labs

Privacy contact: [monad.cosmos.labs@gmail.com](mailto:monad.cosmos.labs@gmail.com)

Effective date: September 28, 2026

NotesAI stores captures, tags, topics, source URLs and search indexes on your Windows device. It reads clipboard text only when you invoke a capture shortcut. Closing the window keeps background capture, indexing and enabled backups running; choose Quit NotesAI in the tray to stop them. Login startup is optional.

Embedding inference runs locally. Initial setup downloads the BGE Small model and tokenizer from Hugging Face; that service receives the download request and network metadata, but NotesAI does not send it your notes for embedding. Saving web or YouTube URLs contacts those sites to retrieve content and transcripts. They receive the requested URLs and network metadata. The bundled yt-dlp reader does not load browser cookies, user configuration or plugins.

AI generation uses the profile you select. Loopback profiles keep inference on your device. Remote profiles send your question, retrieved note passages and bounded recent conversation history to the configured provider. Topic suggestions send a bounded excerpt, title and existing topic labels to the organizer profile. Model discovery contacts the configured service; local Ollama discovery can also check OLLAMA_HOST and loopback defaults. Provider privacy terms, retention rules, account requirements and charges apply. Remote AI endpoints require HTTPS.

Windows DPAPI encrypts saved API keys and Google OAuth tokens for the current Windows user. Keys are decrypted in application memory when needed. Notes, indexes and exported snapshots are not encrypted by NotesAI; protect your Windows account and disk. Old plaintext settings are migrated on launch, but copies in old backups or filesystem history cannot be erased by this migration. Rotate previously exposed keys if needed.

Google Drive backup is optional and uses the drive.file permission, PKCE and a local loopback callback. Connecting authorizes access to files created/opened with the app. When you run or enable Drive backups, snapshots containing your notes, tags, topics, source URLs and timestamps are uploaded to your chosen Drive folder. Snapshots exclude model API keys and Google credentials. They are compressed, not end-to-end encrypted. Disconnect removes local Google credentials; it does not delete backups already in Drive. You can also revoke access in your Google account.

Delete individual captures in the app. Export or restore snapshots in Settings > Backup. Delete exported files and Drive snapshots separately when you no longer need them. Uninstall/reset of the Store app may remove its private local data; export first. This build contains no developer-operated analytics or advertising SDK. Third-party services and the Microsoft Store may process data under their own policies.

For privacy questions or requests, contact Monad Cosmos Labs at the email address above. Do not send API keys, passwords, or private note contents. Publishing this policy on GitHub does not give the publisher access to notes stored on your device or backups in your Google Drive. GitHub processes visits to this page under its own privacy policy. If this policy changes, the updated version and effective date will be published on this page.
