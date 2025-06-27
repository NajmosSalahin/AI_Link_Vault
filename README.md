# AI_Link_Vault: Your Enhanced Bookmark Sanctuary with AI Power

LinkVault is a modern, intuitive, and **AI-powered bookmark manager** designed to help you organize, search, and discover web content more efficiently. Beyond traditional bookmarking, LinkVault leverages artificial intelligence to provide **smart search capabilities, summarize your collections, recommend new sites, and automatically fetch details for your saved links.**

---

✨ Features

* **Intuitive Interface**: Clean, responsive design with a drag-and-drop grid for easy organization.
* **Smart Search (AI-Powered)**: Use natural language queries to find relevant bookmarks based on their content, descriptions, and tags.
* **Collection Summarization (AI-Powered)**: Get a concise summary of your entire bookmark collection, highlighting main themes and common topics.
* **AI-Driven Site Discovery**: Find new websites related to specific topics, categorized by 'Paid', 'Free', or 'Open Source'.
* **Auto-Fill Link Details (AI-Powered)**: Automatically fetch titles, descriptions, and relevant tags for your links using AI.
* **Bookmark Management**: Add, edit, delete, and sort bookmarks by name or date.
* **Import/Export**: Easily import and export your bookmarks in JSON or HTML (Netscape Bookmark File) formats.
* **Duplicate Removal**: Clean up your collection with a single click to remove duplicate URLs.
* **Dark Mode**: Toggle between light and dark themes for comfortable viewing.
* **Local Storage**: All your bookmarks are saved directly in your browser's local storage, ensuring privacy and offline access.

---

🚀 How to Use

1.  **Open the Application**: Simply open the `AI_Link_Vault.html` file in your web browser. No server or installation is required!
2.  **Add a Bookmark**:
    * Click on an empty **`+ Add Bookmark`** box.
    * Enter the URL of the website.
    * (Optional) Click ✨ **`Auto-Fill Details`** to let the AI fetch a title, description, and tags for you.
    * (Optional) Add a custom title, description, and comma-separated tags manually.
    * Click **`Save Link`**.
3.  **Edit a Bookmark**:
    * **Ctrl + Click** (or **Cmd + Click** on Mac) on an existing bookmark to open the edit modal.
    * Make your changes and click **`Save Link`**.
    * You can also **`Delete`** the link from this modal.
4.  **Open a Bookmark**: Simply click on any bookmark box to open the link in a new tab.
5.  **Organize Bookmarks**: Drag and drop bookmark boxes to reorder them in the grid.
6.  **Search**: Type your query into the 🔍 **`Search or ask a question...`** bar. The grid will filter automatically.
7.  **Smart Search**: After typing a query, click ✨ **`Smart Search`** to use AI to find the most relevant links based on content.
8.  **Summarize Collection**: Click ✨ **`Summarize Collection`** to get an AI-generated overview of your entire visible bookmark collection.
9.  **Ask About Link**: Click the **`?`** icon on a bookmark to ask the AI questions about that specific linked page.
10. **Find Sites**: Click 🌐 **`Find Sites`**, enter a prompt (e.g., "free photo editing software"), and let the AI suggest new websites.
11. **Import/Export**: Use the ⬇️ **`Export JSON`**, ⬆️ **`Import JSON`**, 📤 **`Export HTML`**, and 📁 **`Import HTML`** buttons to manage your data.
12. **Deduplicate**: Click 🗑️ **`Deduplicate`** to remove any duplicate URLs from your collection.
13. **Remove All**: Click 💥 **`Remove All`** to clear your entire bookmark collection.
14. **Dark Mode**: Use the 🌙 toggle to switch between light and dark themes.

---

🛠️ AI Integration

LinkVault utilizes the **Gemini API** for its advanced AI features. The `callGeminiAPI` function handles requests to the `gemini-2.0-flash` model for various tasks:

* `generateDetailsWithGemini()`: Fetches a summary, title, and tags for a given URL.
* `smartSearchWithGemini()`: Identifies relevant bookmarks from your collection based on a user query.
* `summarizeCollectionWithGemini()`: Provides a high-level summary of your entire bookmark collection.
* `askAboutLinkWithGemini()`: Answers questions about the content of a specific linked website.
* `findSitesWithGemini()`: Recommends websites based on a user's prompt, categorizing them by type (Paid, Free, Open Source).

**Note**: The API key for Gemini is handled internally by the Canvas environment and is not exposed in the code.

---

⚙️ Development

LinkVault is built as a single-page HTML application using vanilla JavaScript and CSS.

**Technologies Used**:

* **HTML5**: Structure
* **CSS3**: Styling (with responsive design and dark mode)
* **JavaScript (ES6+)**: Core logic and AI integration
* **Google Gemini API**: For all AI functionalities
* **Sortable.js**: For drag-and-drop functionality
* **Microlink.io API**: (Used for favicon fetching, though Google's favicon service is a fallback)

**Running Locally**:

1.  Clone this repository or download the `AI_Link_Vault.html` file.
2.  Open `AI_Link_Vault.html` in your preferred web browser (e.g., Chrome, Firefox, Edge).

---

🤝 Contributing

Contributions are welcome! If you have suggestions for improvements, new features, or bug fixes, please feel free to open an issue or submit a pull request.

---

📄 License

This project is open-source and available under the [MIT License](LICENSE).
