🏢 Web-Based Active Directory Console & IT Tools Suite
A powerful, single-page application (SPA) that mimics a native Windows Active Directory environment directly in the browser. Built entirely with Vanilla HTML, CSS, and JavaScript, it connects to a Google Apps Script backend to serve as a fully functional IT administration portal.

It features user management, audit logging, an IT ticketing system, a token counter, Google Drive integration, and a massive suite of built-in IT utilities.

✨ Features
🛠️ Core Administration Modules
👥 User Management (Active Directory): Create, edit, and delete user objects. Manage roles, custom permissions, and reset passwords. Enable or disable accounts with a native-feeling property inspector.

📊 System Dashboard: Real-time overview of system stats, user roles, ticket statuses, and recent audit activity with CSS-based charting.

📋 Audit Log: Tracks all system actions (logins, user creations, permission changes, file uploads) with advanced filtering and CSV export capabilities.

🖴 Local Disk (D:) / Cloud Drive: Google Drive integration acting as a local file system. Supports file uploading, deleting, and visual storage capacity tracking.

🎫 IT Ticketing System: Create, assign, update, and close IT support tickets. Features SLA tracking, priority levels (High, Medium, Low), and status filtering.

🔢 Token Counter System: Manage digital queue tokens. Features increment, decrement, repeat, reset, and live display integration.

⬛ Terminal Shell: A built-in command prompt interface to execute backend commands directly from the UI.

🧰 The "IT Tools" Suite
A massive collection of client-side utilities built directly into the console, operating primarily within the browser for maximum privacy and speed:

File & Document Tools: PDF Manipulation (Merge, Split, Compress, Watermark, Rotate), Text Diff/Compare tool, and Google Drive Upload + instant QR Code generation.

Network & Sysadmin: Subnet Calculator, Ping/Latency Monitor (with live Canvas charting), IP/DNS/Hosting Lookups, and MAC Vendor Lookup.

Generators & Converters: Secure Password Generator, Base64 Encode/Decode, Hex/Decimal/Binary Converter, and custom QR Code & Barcode (Code128) generators.

System Diagnostics: In-depth System Info Viewer (CPU, RAM, GPU, Battery, Local/Public IP, Screen DPR).

Quick Links Hub: A categorized directory for external proxies, AI tools, software archives, and browser emulators.

💻 Tech Stack
Frontend: Vanilla HTML5, CSS3, JavaScript (ES6+). No heavy frameworks (React/Vue) used, ensuring a lightning-fast load time in a single file structure.

Backend: Google Apps Script (GAS) acting as a serverless REST API to handle user authentication, database operations, and file storage.

Theming: Fully responsive design with native CSS Variables supporting seamless Light and Dark modes.

Libraries Used:

pdf-lib (Client-side PDF manipulation)

JsBarcode (Barcode generation)

QRCode.js (QR Code generation)

<img width="1919" height="1079" alt="Screenshot 2026-03-06 130429" src="https://github.com/user-attachments/assets/5f312292-072c-4599-8a2e-237c15df28fd" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130415" src="https://github.com/user-attachments/assets/92fadc78-1399-473c-a138-858d72dbdf0b" />
<img width="1919" height="883" alt="Screenshot 2026-03-06 130308" src="https://github.com/user-attachments/assets/980388af-3d21-42c0-957c-4d3d90dc56f5" />
<img width="1538" height="780" alt="Screenshot 2026-03-06 131618" src="https://github.com/user-attachments/assets/49c1ef0f-3f9c-499c-b327-2d4c760280a5" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130724" src="https://github.com/user-attachments/assets/dbe73b34-72bd-439d-bec4-44472a4afc03" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130636" src="https://github.com/user-attachments/assets/7df32731-fa06-45e8-9da7-a3513abd549e" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130629" src="https://github.com/user-attachments/assets/6a532060-17d5-4603-8bb1-1be5477ed63d" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130612" src="https://github.com/user-attachments/assets/3c26276f-2904-4911-8432-cfafb1c6a725" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130602" src="https://github.com/user-attachments/assets/ed95e8df-1ed4-4dcc-844d-a8dfc2a3a07f" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130505" src="https://github.com/user-attachments/assets/f36cf67d-137e-415e-a136-0415850ba824" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130455" src="https://github.com/user-attachments/assets/6ded872d-53e9-4807-bd57-d586fd59c66e" />
<img width="1919" height="1079" alt="Screenshot 2026-03-06 130440" src="https://github.com/user-attachments/assets/d2a2bad6-c8bb-4c49-8d14-e2d466c6b892" />



🚀 Installation & Usage
Because the frontend is a standalone HTML file, setup is incredibly simple:

Clone the repository:

Bash
git clone https://github.com/yourusername/active-directory-console.git
Open the index.html file directly in any modern web browser.

(Optional) To host it live, you can deploy it directly via GitHub Pages, Vercel, or Netlify with zero build steps required.

Note: The application expects a Google Apps Script backend URL to authenticate users and fetch data. You will need to configure the API constant at the top of the <script> tag to point to your own deployment if you are forking this project.

⌨️ Global Keyboard Shortcuts
Ctrl + K: Focus Search Bar

Ctrl + E: Export all current IT Tool outputs to a text file

Ctrl + D: Toggle Light/Dark Theme

Escape: Clear search focus

📜 License
Created by aman5z.in. All rights reserved.
