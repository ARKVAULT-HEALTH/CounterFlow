# CounterFlow mini: Now with TransfersRx, Problem Tracking, and More!

For too long, pharmacy teams have relied on handwritten scraps of paper, sticky notes, and chaotic faxes to manage their most critical tasks. This system is prone to errors, clutter, and a lack of privacy. **CounterFlow Mini** was built to solve this.

CounterFlow Mini is a simple, powerful, and completely private digital workflow manager for your pharmacy. It provides a clear, real-time view of your queues without needing an internet connection. It now includes three main modules:

* **WaitRx:** The original digital Kanban board for managing the priority fill queue.
* **ProblemRx:** A to-do list for tracking and managing script-related and task-based problems.
* **TransfersRx:** A brand new module to digitize, log, and manage incoming and outgoing prescription transfers.

## 🔒 Security, Privacy, and Data Persistence

The core principle of CounterFlow Mini is security. The application is designed to be HIPAA-compliant by default by leaving no data behind. You have the option to enable a secure, temporary autosave feature to recover from browser crashes.

### Two Modes of Operation

1.  **In-Memory Mode (Default):**
    * By default, all queue data exists **only in your browser's active memory**.
    * It is **not** written to your hard drive or any temporary files.
    * When you close the browser tab, the memory is cleared, and all data is **instantly and permanently gone**. This is the most secure mode.
2.  **Encrypted Local Autosave (Opt-In):**
    * You can enable this feature in the **Settings** menu to protect against accidental browser crashes or reloads.
    * When enabled, your queue data is automatically saved to your browser's localStorage after every change.
    * This data is set to **automatically expire** after a duration you choose (from 1 to 72 hours). After expiration, the data is deleted upon the next page load.

### Encryption Standard: AES-256-GCM

When Local Autosave is enabled, your data is not stored in plain text. It is encrypted using **AES-256-GCM (Galois/Counter Mode)**.

* **AES-256:** This is the Advanced Encryption Standard with a 256-bit key, the same level of encryption used by the U.S. government to protect top-secret information. It is considered quantum-resistant and cannot be broken by brute force.
* **GCM (Authenticated Encryption):** This mode not only encrypts your data but also creates a secure signature (a tag) to verify that the data has not been tampered with or corrupted. If even a single character of the saved data is changed, it will fail decryption, protecting its integrity.

The encryption key is generated securely by your browser and is also stored in localStorage, separate from the data. It never leaves your machine.

### Verifying the Encryption

To provide full transparency, you can prove that the autosave feature is working as described:

1.  Enable "Local Autosave" in the Settings menu.
2.  Add an item to any queue.
3.  In Settings, click the **"View Raw Encrypted Data"** button.
4.  A window will appear showing the garbled, unreadable text exactly as it is stored in your browser. This demonstrates that your data is not being saved in plain text.

## 🚀 Installation & Usage

Getting started with CounterFlow Mini is incredibly simple. No installation is required.

1.  Go to the [**Latest Release**](https://github.com/ARKVAULT-HEALTH/CounterFlow/releases) page.
2.  Under the "Assets" section, download the `CounterFlowMini.html` file.
3.  Open the file in any modern web browser (like Chrome, Firefox, Edge, or Safari).

That's it! You can now use the application completely offline. You can save the `.html` file to your desktop or a shared folder for easy access.

## 🔁 The Workflow Logic

CounterFlow Mini is designed to be flexible and adapt to your team's specific workflow. Use the tabs at the top to switch between modules.

### WaitRx Module (The Prescription Queue)

This is the core queue for managing waiting prescriptions.

1.  **Waiting for Review:** The starting point. Any technician can add a patient's name and script count to this list.
2.  **Ready to Print:** A holding area for pharmacist-reviewed scripts. Once enough scripts accumulate, a tech clicks the **Print Waiters** button to generate a paper list for the filling technicians.
3.  **Waiting to be Filled:** After printing, scripts automatically move here. This is the final active queue for items being filled.
4.  **Completed:** Anyone on the team can mark a script as completed to clear it from the board.

### ProblemRx Module (The To-Do List)

This module is for tracking issues that need resolution.

* **To Do:** The initial queue for new problems.
* **Follow-up:** For problems that have been partially addressed but require further action.

### TransfersRx Module (The Transfer Log)

This new module digitizes the chaotic process of managing prescription transfers.

* **Incoming Transfers:** Quickly generate professional, formatted fax requests to send to other pharmacies. No more handwritten faxes!
* **Outgoing Transfers:** Create a clear, timestamped log of transfers you give out over the phone, ensuring you have a record of what was transferred, to whom, and when.
* **Pharmacy Directory:** Manage a central list of competitor pharmacies, including their contact info, logos, and staff pharmacists, to make creating faxes and logs faster than ever.

## ⚙️ Customization

You can tailor CounterFlow Mini to your exact needs using the **Settings** menu (the gear icon), including Layout/Interaction modes, Visual Styles, and Print Options.

## 🤝 Contributing

This is a project for the pharmacy community, by the pharmacy community. Your feedback and contributions are welcome!

* **Found a bug or have an idea?** Please [open an issue](https://github.com/ARKVAULT-HEALTH/CounterFlow/issues) and describe it in as much detail as possible.
* **Want to add a feature?** Fork the repository, make your changes, and submit a pull request.

## 📜 License

CounterFlow Mini is free software licensed under the **GNU Affero General Public License v3.0**. You can read the full license text [here](https://www.gnu.org/licenses/agpl-3.0.html).
