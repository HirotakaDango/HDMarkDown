# Welcome to HDMarkDown 

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/c788dd15-9a98-4dff-b652-a6ae18ee6ac9" />

A modern **Markdown Live Workspace** built with pitch dark theme, local **OPFS** file storage, **Find & Replace**, **Undo/Redo**, and **JSON Import/Export**.

## Features
- **OPFS Engine**: Handles large document structures locally inside origin private storage.
- **Multiple Files**: Manage all your markdown notes seamlessly from the sidebar.
- **Synchronized Live Preview**: Auto-updates code blocks and formatted tables as you edit.

```javascript
// Quick example of JavaScript highlight
async function loadStorage() {
  const root = await navigator.storage.getDirectory();
  console.log("OPFS Loaded successfully!");
}
```

| Feature | Supported |
| :--- | :---: |
| Undo & Redo | ✅ |
| Find & Replace | ✅ |
| Import/Export JSON | ✅ |
