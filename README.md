# 📥 GitHub DL-EBox Download Manager  

An automated GitHub Actions workflow that downloads files directly from commit messages and saves them to your repository. 

## 👤 Author

**ElectronicBox**
- 🔗 GitHub: [@ElectronicBox](https://github.com/ElectronicBox)

## 📋 What This Does

When you include a special command in your commit message, this workflow automatically downloads the files and adds them to your repository.

## 🚀 How to Use






**Single file:**

```
download: https://example.com/file.pdf
```

**Multiple files:** (separate URLs with spaces)

```
download: https://example.com/file1.zip https://example.com/file2.jpg https://example.com/file3.mp4
```

**Download as one ZIP archive:**

```
download-zip: https://example.com/file1.pdf https://example.com/file2.png https://example.com/file3.docx
```

