# Welcome to HDMarkDown 

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b8d38e75-9fb3-4ffc-9f7b-c43785b3fece" />

A modern **Markdown Live Workspace** built with pitch dark theme, local **OPFS** file storage, **Find & Replace**, **Undo/Redo**, and **JSON Import/Export**.

## Media Embedding Support

### YouTube Video
<div class="video-container">
  <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### HTML5 Native Video
<video controls width="100%">
  <source src="https://interactive-examples.mdn.mozilla.net/media/cc0-videos/flower.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

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
| YouTube & Video | ✅ |
