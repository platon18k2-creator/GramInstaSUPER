# SuperGram — GitHub Pages ready

## Upload
Загрузи **содержимое этой папки** в корень GitHub-репозитория.
После загрузки структура должна быть:

```
index.html
.nojekyll
README.md
```

## GitHub Pages
Repository → Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

## Firebase
В `index.html` уже вставлен Web App config проекта SuperGram.
В Firebase Console должны быть включены:
- Authentication → Email/Password
- Firestore Database
- Storage (для файлов/голосовых/фото)

## Важно
`firestore.rules` и `storage.rules` не входят в этот ZIP, потому что правила зависят от твоих настроек безопасности. Не открывай Firestore/Storage для всех без ограничений.
