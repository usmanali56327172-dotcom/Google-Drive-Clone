# Google Drive File System (Console-Based C++ Project)

A console-based simulation of a Google Drive–like file management system developed in C++ as part of the Data Structures course project.

The system demonstrates the practical use of multiple data structures including Trees, Hash Tables, Stacks, Queues, Graphs, and Linked Lists to manage files, folders, users, sharing, and version control.

---

## Features

### Folder and File Management
- Create, delete, and navigate folders
- Create, read, update, and delete files
- Hierarchical directory structure using Tree

### Fast File Lookup
- File metadata stored in a Hash Table
- O(1) average time complexity for file search

### Recycle Bin
- Deleted files are stored in a Stack
- Restore the most recently deleted file

### Recent Files
- Queue-based tracking of recently accessed files
- Supports Least Recently Used (LRU)-style management

### User Authentication
- Sign up, login, logout
- Security questions for password recovery
- Stores last login and logout information

### File Sharing
- Graph-based sharing system between users

### File Versioning
- Doubly Linked List maintains version history
- Roll back to any previous version

### Access Control
- Admin, Editor, and Viewer roles
- Read, write, and execute permissions

### Compression
- Run-Length Encoding (RLE) compression

### Cloud Synchronization
- Queue-based background sync simulation

---

## Data Structures Used

| Data Structure | Purpose |
|---------------|---------|
| Tree | Folder hierarchy |
| Hash Table | File metadata and fast lookup |
| Stack | Recycle Bin |
| Queue | Recent files and sync tasks |
| Graph | User sharing and permissions |
| Doubly Linked List | File version history |

---

## Project Structure

```text
GoogleDriveFileSystem/
│── main.cpp
│── FileSystem.h
│── FileSystem.cpp
│── UserManager.h
│── UserManager.cpp
│── README.md
│── sample_data/
│── docs/
