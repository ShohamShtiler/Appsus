# 🗂️ APPSUS – Google Apps Suite Clone

A comprehensive clone of **Google’s productivity suite**, built with **React**, featuring core functionality from **Google Keep** and **Gmail**. This project showcases advanced front-end development, state management, modular design, and cross-app integration.

> ✨ Pixel-perfect · Component-driven · Fully responsive

---

## 🔧 Applications Overview

### 📝 Notes – *Google Keep Clone*
Create, manage, and organize notes in multiple formats:  
Text · Todo Lists · Images · YouTube Videos · Audio · Canvas

**Main Features:**
- 🗒️ Multiple Note Types:
  - Text notes
  - Todo lists with checkbox logic
  - Image notes
  - YouTube embedded video notes
  - Canvas drawings *(in progress)*
  - Audio notes *(in progress)*

- 🎨 Organization:
  - Pin, archive, trash notes
  - Color-coded notes
  - Filter by note type and text

- ✍️ Rich Editing:
  - In-place editing
  - Drawing tools for canvas
  - Todo management UI

---

### 📧 Mail – *Gmail Clone*
A fully-featured email client with folder structure, filters, and note integration.

**Main Features:**
- 📬 Email Management:
  - Compose new emails
  - View inbox, sent, drafts, and trash
  - Star important emails
  - Mark as read/unread

- 💾 Draft Auto-Save:
  - Auto-save every 5 seconds
  - Seamless resume of incomplete drafts

- 🔗 Note-to-Mail Integration:
  - Send notes as emails directly
  - Compose new mail from note content

---

## 🚀 Tech Stack

| Area           | Technologies / Tools                                 |
|----------------|------------------------------------------------------|
| Frontend       | React, React Router, JSX, CSS                        |
| State Mgmt     | React Hooks (`useState`, `useEffect`, `useRef`)     |
| Data Handling  | LocalStorage (custom services for persistence)       |
| UI/UX          | Custom modal system, animations, transitions         |
| Forms          | Controlled components, validation, auto-save drafts |
| Note Types     | Text, Todo, YouTube embeds, Image, Audio, Canvas     |
| Styling        | Component-scoped CSS                                 |
| Integration    | Notes ↔ Mail linkage (send note as email)            |
| Deployment     | GitHub Pages / local browser-based storage           |

---

## 📸 Screenshots

<p float="left">
  <img src="https://res.cloudinary.com/drx3ncwmd/image/upload/v1752781055/appsus1_vrpz9s.png" width="1000" />
  <img src="https://res.cloudinary.com/drx3ncwmd/image/upload/v1752781055/appsus2_wmj9ng.png" width="1000" />
  <img src="https://res.cloudinary.com/drx3ncwmd/image/upload/v1752781054/appsus3_qquqy1.png" width="1000" />
  <img src="https://res.cloudinary.com/drx3ncwmd/image/upload/v1752781056/appsus4_xxvc6u.png" width="1000" />
</p>

---

## 🧩 Key Functionality

### Notes App
- ✅ Create/Edit/Delete notes in various formats
- 📌 Pin/archive/trash features
- 🎨 Color-coding and filtering
- 📝 Rich editing + canvas drawing
- 📹 YouTube and audio embedding

### Mail App
- 📧 Compose and manage emails
- 📂 Folders: inbox, sent, drafts, starred, trash
- ⏳ Auto-save drafts every 5 seconds
- 📎 Send notes as emails

### Cross-App Integration
- 🔁 Compose mail directly from note content
- 🔗 Rich link between Keep & Gmail experiences

---

## 🛠️ Components Breakdown

### 📧 Mail
- `MailIndex` – Main interface
- `MailCompose` – Editor with auto-save
- `MailList` & `MailPreview` – Email list view
- `MailDetails` – Full email view
- `MailFilter` – Search & filter logic
- `MailFolderList` – Navigation sidebar

### 📝 Notes
- `NoteIndex` – Main layout and state
- `NoteAdd` – Create new notes
- `NoteList` & `NotePreview` – Grid view
- `NoteEdit` – Modal editing UI
- `Dynamic Components` – Different note types:
  - `NoteTxt`, `NoteImg`, `NoteTodos`, `NoteVideo`, `NoteCanvas`, `NoteAudio`

---

## 🧪 Future Enhancements

- 🔐 User authentication
- ☁️ Cloud storage integration
- 🧑‍🤝‍🧑 Collaborative notes
- 🏷️ Labels & categories
- 📱 Mobile support / PWA

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an [issue](https://github.com/ShohamShtiler/Appsus/issues) or submit a PR.

---

## 👏 Acknowledgements

- Inspired by **Google Keep** and **Gmail**
- Icons from **Material Design** & **Font Awesome**

---

**Made with ❤️ by Shoham & Shmuel**
