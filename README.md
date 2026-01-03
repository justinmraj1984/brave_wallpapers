# 📸 Brave Browser Wallpaper Extractor

If you've used the **Brave Browser**, you know how stunning their "New Tab" background wallpapers are. This guide helps Windows users locate and save those high-quality images directly from their local machine.

---

## 🛠 How to Collect the Wallpapers

Since Brave caches these images locally, you can find them hidden within your application data. Follow these steps:

### 1. Navigate to the Brave User Data Folder

Open your File Explorer and paste the following path into the address bar (replace `<YourUsername>` with your actual Windows username):

`C:\Users\<YourUsername>\AppData\Local\BraveSoftware\Brave-Browser\User Data`

> **Tip:** You can also press `Win + R`, type `%LOCALAPPDATA%\BraveSoftware\Brave-Browser\User Data`, and hit Enter to get there instantly.

### 2. Search for the Manifest File

In the search bar at the top right of the folder window, search for:
**`photo.json`**

### 3. Locate the Image Assets

The search results will likely show several files or folders.

* Right-click one of the `photo.json` files and select **"Open folder location."**
* In that same folder (or subfolders like `ds` or `resources`), you will find the `.jpg` files.

### 4. Save Your Favorites

Simply copy the `.jpg` files to your **Pictures** or **Wallpapers** folder. You can now use them as your desktop background!

---

## 📝 Important Notes

* **Format:** Most files are already in `.jpg` format. If you find files without extensions, you can try renaming them to include `.jpg` at the end.
* **Updates:** Brave periodically clears its cache or downloads new images, so check back often to see new additions to the collection.

---

### How I improved it:

* **Dynamic Paths:** I added the `%LOCALAPPDATA%` shortcut, which is much easier for users because they don't have to manually find their username.
* **Visual Hierarchy:** Used headers (`#`, `##`) and bold text to make it scannable.
* **Callouts:** Used blockquotes (`>`) for "Pro Tips" to make the guide feel more interactive.
* **Clarity:** Added a "Note" section to handle potential issues with file extensions.
