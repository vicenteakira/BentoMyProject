# Bento you projects

<img width="100%" alt="Screenshot 2021-05-16 at 17 54 49" src="https://user-images.githubusercontent.com/29678262/118403707-ef755000-b66f-11eb-8ff4-c2c29291d9c7.png">

# About
A macOS app created with Automator that triggers bash scripts to create a personal folder structure for graphic design projects.
Organization is key to deliver a successful project and offer a great service, sometimes is a tedious and time-consuming task, this app imposes a folder structure that:

- Keeps projects organized
- Lowers the time organizing
- Avoids messy folders and losing files
- Standardizes a workflow
- Avoids breaking links
- Easy archival and retrieval of projects
- Short learning curve for new collaborators

## Table of contents
- [Installation](#installation)
- [How it works](#how-it-works)
  * [Folder and  File Structure](#folder-and--file-structure)
  * [File Naming](#file-naming)

# Installation

https://user-images.githubusercontent.com/29678262/118462875-6d346c80-b6ff-11eb-9a0d-8f916471ccf9.mp4

1. Download the latest release and unzip the folder
2. Open it the first time by right-clicking the app and selecting open, macOS will pop up a warning sign
<img width="372" alt="Screenshot 2021-05-17 at 10 33 30" src="https://user-images.githubusercontent.com/29678262/118459327-f0ec5a00-b6fb-11eb-9727-cd090ccd0fb0.png">
3. Open again the app by right-clicking and selecting open, this time the OS will allow you to use the app
<img width="372" alt="Screenshot 2021-05-17 at 10 33 39" src="https://user-images.githubusercontent.com/29678262/118459347-f6e23b00-b6fb-11eb-88c7-75c5fa3d24c2.png">
4. Locate the app in your docker, desktop or anywhere in finder

# How it works
The app asks for the name of the project following the syntax `Client_ProjectTitle`, this helps to group all projects of the same client. Once the name is set, asks for a location to save the project. Creates the folder structure and opens the saving location.

The combination of folder paths and naming ensures the optimal workflow. According to the project, the folder structure may be morphed to fulfill the project needs.

## Folder and  File Structure
The folder structure has been designed to standardize all projects, making it agile to share with other professionals and maintain a certain order. It also allows sharing specific folders with the client, maintaining the progress of the project private. Each folder is detailed below:

### Folders

#### `00_Paperwork`
This folder contains, as its name indicates, all the bureaucracy of the project.

#### `01_Input`
This folder must contain all the information and data provided by the client. All original files must be kept here.

#### `02_Output`
This folder contains `Deliveries` and `Presentations`, both organized by date. This folder is meant to be sent and shared with the client, providing them a clean and organized deliverables without the clutter of other technical files.

#### `Assets`
This folder contains all assets organized by categories. By the fault a `fonts`, `img` and `video` folders are created.

#### `Files`
This folder hosts all the files used to develop the project. Organized by apps.

#### `Moodboard`
All images, videos, pdf, notes... must be located here. The naming of the files in this folder, has to be the original file name, for easy finding of the source.

### Files

### `README.txt`
A text file that details new collaborators and team members to respect the structure and the importance of a tidy project. Instructs on folder structure and the standard to name files.

### `brief.txt`
The project brief by the client and its respective modifications.

### `stakeholders.txt`
This file contains all the contact information of clients and providers involved in the project.

## File Naming
Standardizing a nomenclature system, ensures a fast retrieval of documents and avoids breaking links.

### Hierarchy
#### `Version`
To order folders and files, a two digit followed by an underscore must be placed `00_`. Combined with the finder feature to order by name, we can ensure a list of items. Used to determinate priority or the latest version of the file.

#### `CAPS`
Used for files or folders with a high priority, but are not part of the list. CALLS ATTENTION.

#### `lower case`
Short and non-complex files, must be named in lower case. An example could be: `brief.txt`

#### `TitleCase`
For long and complex phrases. An example could be: `00_NameOfTheFile`

### Underscore
The underscore `_` is used to separate data inputs in the file name. An example could be: `00_FileName`.

### Dates
Use it for deliveries and exports. Can be combined with file version. The format is `ddMM`, using the month abbreviation for shorter file names. An example could be: `14June_`.

| Month     | Abbreviation  |
|-----------|---------------|
| January   | Jan.          |
| February  | Feb.          |
| March     | Mar.          |
| April     | Apr.          |
| May       | May           |
| June      | Jun.          |
| July      | Jul.          |
| August    | Aug.          |
| September | Sep. or Sept. |
| October   | Oct.          |
| November  | Nov.          |
| December  | Dec.          |

------

_The bento emoji is copyrighted under Apple's terms and conditions. This emoji is not used for commercial purposes, it just helps integrate the app well with macOS_
