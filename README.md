CounterFlow Mini: A Modern Workflow Manager for Pharmacy
For too long, pharmacy teams have relied on handwritten scraps of paper, sticky notes, and chaotic faxes to manage their most critical tasks. This system is prone to errors, clutter, and a lack of privacy. CounterFlow Mini was built to solve this.
CounterFlow Mini is a simple, powerful, and completely private digital workflow manager for your pharmacy. It provides a clear, real-time view of your queues without needing an internet connection.
✨ What's New in This Version?
This release is a massive leap forward, introducing powerful new modules and features requested by the pharmacy community:
 * NEW TransfersRx Module: A complete system to digitize, log, and manage incoming and outgoing prescription transfers.
 * Professional Fax Generation: Create clean, professional, and complete transfer request faxes in seconds—no more handwriting.
 * Central Pharmacy Directory: Manage a list of competitor pharmacies with their logos, contact info, and staff lists to make transfers a breeze.
 * End-of-Day Reporting: Print a summary of all outstanding problems and logged transfers for easy follow-up and record-keeping.
 * Pharmacist Credentials: Store and display credentials (RPh, PharmD) for a professional touch on all communications.
 * Enhanced Editing: Robust editing modals for all queue items, making it easy to correct mistakes.
 * Timestamps Everywhere: All logged items now have a clear, visible timestamp for better record-keeping.
🚀 The Modules
CounterFlow Mini is organized into three powerful modules:
 * WaitRx: The original digital Kanban board for managing the priority fill queue.
 * ProblemRx: A to-do list for tracking and managing script-related and task-based problems.
 * TransfersRx: The new hub for managing all prescription transfers.
🔒 Security, Privacy, and Data Persistence
The core principle of CounterFlow Mini is security. The application is designed to be HIPAA-compliant by default by leaving no data behind. You have the option to enable a secure, temporary autosave feature to recover from browser crashes.
Two Modes of Operation
 * In-Memory Mode (Default):
   * By default, all queue data exists only in your browser's active memory.
   * It is not written to your hard drive or any temporary files.
   * When you close the browser tab, the memory is cleared, and all data is instantly and permanently gone. This is the most secure mode.
 * Encrypted Local Autosave (Opt-In):
   * You can enable this feature in the Settings menu to protect against accidental browser crashes or reloads.
   * When enabled, your queue data is automatically saved to your browser's localStorage after every change.
   * This data is set to automatically expire after a duration you choose (from 1 hour to 10 years). After expiration, the data is deleted upon the next page load.
Encryption Standard: AES-256-GCM
When Local Autosave is enabled, your data is not stored in plain text. It is encrypted using AES-256-GCM (Galois/Counter Mode).
 * AES-256: This is the Advanced Encryption Standard with a 256-bit key, the same level of encryption used by the U.S. government to protect top-secret information. It is considered quantum-resistant and cannot be broken by brute force.
 * GCM (Authenticated Encryption): This mode not only encrypts your data but also creates a secure signature (a tag) to verify that the data has not been tampered with or corrupted.
The encryption key is generated securely by your browser and is also stored in localStorage, separate from the data. It never leaves your machine.
Verifying the Encryption
To provide full transparency, you can prove that the autosave feature is working as described:
 * Enable "Local Autosave" in the Settings menu.
 * Add an item to any queue.
 * In Settings, click the "View Raw Encrypted Data" button.
 * A window will appear showing the garbled, unreadable text exactly as it is stored in your browser. This demonstrates that your data is not being saved in plain text.
📦 Installation & Usage
Getting started with CounterFlow Mini is incredibly simple. No installation is required.
 * Go to the Latest Release page.
 * Under the "Assets" section, download the CounterFlowMini.html file.
 * Open the file in any modern web browser (like Chrome, Firefox, Edge, or Safari).
That's it! You can now use the application completely offline. You can save the .html file to your desktop or a shared folder for easy access.
⚙️ Customization
You can tailor CounterFlow Mini to your exact needs using the Settings menu (the gear icon), including Layout/Interaction modes, Visual Styles, and Print Options.
🤝 Contributing
This is a project for the pharmacy community, by the pharmacy community. Your feedback and contributions are welcome!
 * Found a bug or have an idea? Please open an issue and describe it in as much detail as possible.
 * Want to add a feature? Fork the repository, make your changes, and submit a pull request.
📜 License
CounterFlow Mini is free software licensed under the GNU Affero General Public License v3.0. You can read the full license text here.
