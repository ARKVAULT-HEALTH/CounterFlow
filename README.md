# **WaitRx \- A Secure, Offline-First Prescription Queue**

For too long, pharmacy teams have relied on handwritten scraps of paper, sticky notes, and whiteboards to manage their priority prescription queue. This system is prone to errors, clutter, and a lack of privacy. **WaitRx** was built to solve this problem.

WaitRx is a simple, powerful, and completely private digital Kanban board for your pharmacy's waiting prescriptions. It's designed to be intuitive for the entire team, from technicians to pharmacists, providing a clear, real-time view of the waiter queue without needing an internet connection.

**The core principle of WaitRx is security and privacy.** All data is stored locally in your browser and is **permanently deleted** when the page is closed. Nothing is ever sent to a server.

## **🚀 Installation & Usage**

Getting started with WaitRx is incredibly simple. No installation is required.

1. Go to the [**Latest Release**](https://github.com/ARKVAULT-HEALTH/waitrx/releases) page.  
2. Under the "Assets" section, download the WaitRx.html file.  
3. Open the file in any modern web browser (like Chrome, Firefox, Edge, or Safari).

That's it\! You can now use the application completely offline. You can save the WaitRx.html file to your desktop or a shared folder for easy access.

## **🔁 The WaitRx Workflow Logic**

WaitRx is designed to be flexible and adapt to your team's specific workflow. Here’s the core logic behind each queue:

### **1\. Waiting for Review**

* **Purpose:** This is the starting point. Any technician can add a patient's name to this list to get it on the pharmacist's radar.  
* **Action:** A **Pharmacist** reviews the prescription in the main pharmacy system to ensure it's clinically appropriate and ready for the next step. Once verified, they advance the script in WaitRx.

### **2\. Ready to Print**

* **Purpose:** This queue acts as a holding area for scripts that have been pharmacist-reviewed but not yet printed for the filling techs.  
* **Action (Standard Workflow):** Once enough scripts accumulate (based on your team's preference set in Settings), a tech clicks the **Print** button. This generates a clean, paper list for the filling technicians. All printed scripts automatically move to the next queue.  
* **Action (Tablet/Paperless Workflow):** In "Tablet Mode," this queue is hidden. The "Reviewed" action sends scripts directly to the final queue.

### **3\. Printed and Waiting to be Filled**

* **Purpose:** This is the final active queue. It contains all prescriptions that are currently being filled by technicians or are physically ready for the patient.  
* **Action:** *Anyone* on the team (the filling tech, the front-end tech, or the pharmacist) can select the prescription and click **"Mark as Completed"** to clear it from the board, keeping the list clean and up-to-date.

## **⚙️ Customization**

You can tailor WaitRx to your exact needs using the **Settings** menu (the gear icon):

* **Layout/Interaction:**  
  * **Cards \- Direct:** The fastest mode. Every card has its own action buttons.  
  * **Cards \- Select:** A cleaner view. Click any card to select it, then use the central Action Bar that appears.  
  * **Desktop:** A high-density data grid view, perfect for dedicated terminals.  
* **Visual Style:**  
  * **Modern:** The default, clean interface.  
  * **Classic:** A retro look with GroupBox-style sections.  
  * **Classic \- Windows XP:** A special version of the Classic style with authentic beveled, gray headers on the data grid for a true retro software feel.  
  * **Terminal:** A green-screen-like, monospaced layout for the nostalgic.  
* **Theme:**  
  * Change the color palette of the application.  
* **Tablet Mode:** A Paperless Workflow  
  * For teams using tablets or who prefer a fully digital process, **Tablet Mode** streamlines the workflow by removing the print step entirely. You can enable it in the **Settings** menu. When active:  
    * The **"Print"** and **"Print Preview"** buttons are hidden.  
    * The **"Ready to Print"** queue is removed from the main view.  
    * When a pharmacist marks a script as **"Reviewed"**, it now moves directly to the **"Printed and Waiting to be Filled"** queue, allowing the filling technician to work directly from their screen without paper.

## **🤝 Contributing**

This is a project for the pharmacy community, by the pharmacy community. Your feedback and contributions are welcome\!

* **Found a bug or have an idea?** Please [open an issue](https://github.com/ARKVAULT-HEALTH/waitrx/issues) and describe it in as much detail as possible.  
* **Want to add a feature?** Fork the repository, make your changes, and submit a pull request.

## **📜 License**

WaitRx is free software licensed under the **GNU Affero General Public License v3.0**. This means you are free to use, modify, and distribute the software. However, if you create a modified version and make it available to others (even over a network), you must also make your source code available under the same license.

You can read the full license text [here](https://www.gnu.org/licenses/agpl-3.0.html).
