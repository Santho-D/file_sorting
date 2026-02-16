# File Sorting

Sorts files according to extensions (.txt, .jpg, etc.) Currently being used for ~/Downloads/

##  Overview

Python script that automatically sorts files in a Directory according to categories based on extensions.

**Features**:

- Automatic file sorting
- Creates category folders
- cross platform (Windows/Linux)
- Error handling for locked / inaccessible files 

## Quick start:

```bash
# Clone the repository
git clone https://github.com/**YOUR-USERNAME**/file_sorting.git
cd file_sorting

# Run the script
python file_organizer.py
```

## File Categories

| Category | File Types |
|----------|-----------|
| Text_Documents | .txt, .md, .doc, .docx |
| Images | .jpg, .jpeg, .png, .gif |
| Videos | .mp4, .avi, .mov |
| PDF_Documents | .pdf |
| Excel_Sheets | .xlsx |
| Zip_Files | .zip, .rar |
| Setup_Exe | .exe |
| Projects | .py |
| ISO_files | .iso |

## Requirements

- Python3.6 or higher
- No external dependencies

## How It Works

1. Scans the specified folder
2. Identifies file extensions
3. Moves files to matching category folders
4. Skips files that can't be moved (locked, etc.)

## Author

Santho-D
Fachinformatiker Anwendungsentwicklung in training