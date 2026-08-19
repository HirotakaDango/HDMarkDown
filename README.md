# Welcome to HDMarkDown 

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e5e0a757-392b-4c67-aec7-2a1baad4a0ba" />

A modern **Markdown Live Workspace** built with pitch dark theme, **Find & Replace**, **Undo/Redo**, and **JSON Import/Export**.

## Features
- **IndexedDB Engine**: Securely persists large document structures locally with high performance and zero data loss.
- **Multiple Files**: Manage all your markdown notes seamlessly from the sidebar.
- **Synchronized Live Preview**: Auto-updates code blocks and formatted tables as you edit.

```javascript
// Quick example of IndexedDB initial setup
const request = indexedDB.open('HDMarkDownDB', 1);
request.onsuccess = (e) => {
  console.log("IndexedDB Loaded successfully!");
};

```

| Feature | Supported |
| --- | --- |
| Persistent IndexedDB | ✅ |
| Undo & Redo | ✅ |
| Find & Replace | ✅ |
| Import/Export JSON | ✅ |
| YouTube & Video | ✅ 
