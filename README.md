# 🗂️ Advanced File Organizer  

## 📌 Overview  
The **Advanced File Organizer** is a Python script that automatically sorts files into categorized folders based on their file types. It helps keep directories clean and organized by moving files into appropriate subfolders.  

## 🚀 Features  
✅ Automatically detects and moves files based on extensions  
✅ Supports multiple file categories (Images, Documents, Videos, etc.)  
✅ Keeps a **log file (`file_organizer_log.txt`)** for tracking moved files  
✅ Provides a **summary of files moved** after execution  

## 📂 Supported File Categories  
- **Images** (`.jpg, .png, .gif, .bmp, .svg`)  
- **Documents** (`.pdf, .docx, .txt, .xlsx, .pptx, .csv`)  
- **Videos** (`.mp4, .avi, .mov, .mkv, .flv`)  
- **Music** (`.mp3, .wav, .aac, .flac`)  
- **Archives** (`.zip, .rar, .tar, .gz, .7z`)  
- **Executables** (`.exe, .apk, .bat, .sh, .msi`)  
- **Programming Files** (`.py, .java, .cpp, .js, .html, .css`)  

## 🔧 Installation  
Ensure you have **Python 3.x** installed. No additional libraries are required.  

## ▶️ How to Run  
1. **Download the script** (`file_organizer.py`).  
2. Open a terminal and navigate to the script location.  
3. Run the script using:  
   ```sh
   python file_organizer.py

4. Enter the path of the folder you want to organize (e.g., C:/Users/YourName/Downloads or /storage/emulated/0/Downloads).



📝 Example Output

Enter the path of the folder to organize: /storage/emulated/0/Downloads
Moved: project.py → Programming Files
Moved: song.mp3 → Music
Moved: movie.mp4 → Videos
Moved: report.pdf → Documents
Moved: setup.exe → Executables
Moved: data.csv → Documents

File organization complete! 6 files moved.

📜 Log File (file_organizer_log.txt)

Every action is recorded in a log file. Example log entry:

2025-03-03 10:15:22 - Moved project.py to Programming Files  
2025-03-03 10:15:23 - Moved song.mp3 to Music  
2025-03-03 10:15:24 - Moved movie.mp4 to Videos

🔍 Notes

If a category folder doesn’t exist, it will be created automatically.

Files that don’t match any category will not be moved.


📜 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Developed by Jayapriya!? -hmm
