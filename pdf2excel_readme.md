# Global Survey PDF2Excel Converter 📄➡️📊
This application offers a friendly way to pull data from Global Survey PDF reports and turn it into neat Excel files. It's designed to make extracting information about manhole locations, and incoming and outgoing pipes from many PDFs a breeze!

## ✨ Features
Batch Processing: Convert multiple PDF files from one folder to Excel files in another. 📁➡️📂

Smart Data Extraction: Get key info like:

Location Details: Node Reference, Coordinates, Location Description, Survey Date, Node Type, Cover specifics, Chamber Size, and more. 🗺️📍

Incoming Pipes: ID, Upstream Reference, Pipe Shape, Size, Material, Lining, Depths, and Invert Levels. ⬇️📏

Outgoing Pipes: ID, Upstream Reference, Pipe Shape, Size, Condition, Criticality, Material, Lining, Depths, and Invert Levels. ⬆️📐

Easy-to-Use Interface: A simple GUI, built with Tkinter, helps you pick folders and start conversions effortlessly. 🖥️🖱️

Basic Error Handling: Catches common issues during file processing. ⚠️

## 🚀 How to Use

Choose Input Folder: Click "Browse" next to "Select Input Folder" and pick the folder with your Global Survey PDF files. 📁

Choose Output Folder: Click "Browse" next to "Select Output Folder" and select where you want your new Excel files to go. 📂

Start Converting: Click "Process"! You'll get a message when everything's done. ✅

## 📊 What Your Excel Files Will Look Like


Raw Data: The raw text from the PDF, broken down into columns. Good for quick checks! 📝

Location Details: A clear table with all the location-specific information. 🗺️

Incoming Pipes: A table showing all the details for incoming pipes. ⬇️

Outgoing Pipes: A table with all the details for outgoing pipes. ⬆️

###💡 Important Things to Note
PDF Format Matters: This tool works best with Global Survey PDFs that have a consistent layout. If a PDF looks very different, some data might not extract correctly. ⚠️

Accuracy Depends: We've tried to make it super accurate, but the quality of extraction can depend on how clear and consistent the text is in your PDFs. 🧐

"Node Reference": The "Node Reference" will be highlighted at the top of the "Location Details", "Incoming Pipes", and "Outgoing Pipes" sheets for easy spotting! ✨

## 🧑‍💻 Developer
Anurag Kashyap

📧 Email: anuragkr.kashyap@gmail.com

🔗 GitHub: github.com/KashyapAnurag/GlobalSurveyManholeTool

