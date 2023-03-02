# File Management in Operating Systems
(Quick Explanation)

## Introduction
In an operating system, file management is the process of organizing and controlling computer data files. File management ensures that the files are stored efficiently and can be accessed and used by the computer system and its users. File management is an important part of an operating system because it enables users to manage their data and programs.

## Functions of File Management
File management performs the following functions:
  - File creation and deletion
  - File organization
  - File naming and assignment of attributes
  - File access control and protection
  - File backup and recovery

## Types of File Management
There are several types of file management systems, including:

<details><summary><h3>File System</h3></summary>
  <p>A file system is a type of file management system that organizes and manages files and directories. It defines how files are named, stored, and accessed. Some popular file systems include FAT, NTFS, HFS+, and ext4.</p>
</details>

<details><summary><h3>File Attributes</h3></summary>
  <p>File attributes are metadata that describe the characteristics of a file. Attributes can include file type, size, creation date, and permissions. File attributes are used to manage and protect files.</p>
</details>

<details><summary><h3>File Operations</h3></summary>
  <p>File operations are actions that can be performed on files, such as create, open, read, write, and delete. These operations are managed by the file system.</p>
</details>

<details><summary><h3>File Naming</h3></summary>
  <p>File naming is the process of assigning a unique name to a file. File names are used to identify and access files. File naming conventions may vary by operating system and organization.</p>
</details>

<details><summary><h3>File Types</h3></summary>
  <p>There are many types of files, including text files, image files, audio files, video files, and executable files. Each file type has its own format and characteristics.</p>
</details>

<details><summary><h3>File System Architecture</h3></summary>
  <p>File system architecture refers to the way in which files are organized and managed on a storage device. The two main types of file system architectures are:</p>
  <details><summary><h4>FAT</h4></summary>
    <p>The File Allocation Table (FAT) file system was developed by Microsoft for use in MS-DOS and Windows operating systems. The FAT file system uses a table to allocate space on a storage device for files.</p>
  </details>
  <details><summary><h4>NTFS</h4></summary>
    <p>The New Technology File System (NTFS) is a file system developed by Microsoft for use in Windows operating systems. NTFS uses a tree-like structure to organize files and directories on a storage device.</p>
  </details>
  <details><summary><h4>FAT and NTFS Classification</h4></summary>
    <p>The following table provides a comparison of the features of FAT and NTFS file systems:</p>
    <table>
      <thead>
        <th>Feature</th>
        <th>FAT</th>
        <th>NTFS</th>
      </thead>
      <tbody>
        <tr>
          <td>Maximum file size</td>
          <td>4 GB</td>
          <td>16 TB</td>
        </tr>
        <tr>
          <td>Maximum volume size</td>
          <td>2 TB</td>
          <td>256 TB</td>
        </tr>
        <tr>
          <td>File system journaling</td>
          <td>No</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>File compression</td>
          <td>Yes</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Encryption</td>
          <td>No</td>
          <td>Yes</td>
        </tr>
        <tr>
          <td>Access control</td>
          <td>No</td>
          <td>Yes</td>
        </tr>
      <tbody>
    </table>
  </details>
</details>

<details><summary><h3>Directory Structure</h3></summary>
  <details><summary><h3>Tree-Structured Directory</h3></summary>
    <p>A tree-structured directory is a type of file system architecture that organizes files and directories in a hierarchical structure, similar to a tree. This structure is commonly used in modern operating systems such as Windows and UNIX/Linux. In a tree-structured directory, there is a single root directory that branches out to other directories and files. Each directory can contain subdirectories, which can also contain subdirectories, and so on. This creates a hierarchical structure where each directory has a parent directory and can have one or more child directories.

    The advantages of a tree-structured directory include:</p>

    <ul>
      <li>Easy navigation and organization of files and directories</li>
      <li>Efficient searching and retrieval of files</li>
      <li>Consistent naming conventions</li>
      <li>Allows for access control and security measures to be implemented on specific directories or files</li>
    </ul>
  </details>
  <details><summary><h3>Acyclic-Graph Directory</h3></summary>
    <p>An acyclic-graph directory is a type of file system architecture that allows for multiple parent directories for a single file or directory. This structure is commonly used in older operating systems such as the original Macintosh operating system. In an acyclic-graph directory, files and directories are represented as nodes in a graph, where each node can have multiple parent nodes but no cycles are allowed.
    
    The advantages of an acyclic-graph directory include:</p>
    <ul>
      <li>Flexibility in organizing files and directories without being constrained by a strict hierarchy</li>
      <li>Reduction of duplicate files and directories</li>
      <li>Efficient use of storage space by linking files and directories to multiple locations</li>
    </ul>
  </details>
</details>

## Conclusion
We have covered various aspects of file management, including the functions of file management, types of file management, file system architecture, and the advantages and disadvantages of different file system architectures such as tree-structured directory and acyclic-graph directory. We have also discussed the differences between FAT and NTFS file systems and their classification based on features such as maximum file size, maximum volume size, file system journaling, file compression, encryption, and access control.

Overall, file management is a critical component of an operating system as it enables users to organize and manage their data and programs efficiently. The choice of file system architecture depends on specific needs and requirements, such as scalability, access control, security, and performance. By understanding the different types of file management and file system architectures, users can make informed decisions on how to best manage their files and directories.

<hr>

## Ubuntu File System Exercise

1. Create Dir

   <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080705495557472386/image.png" width="500px">
   <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080706066234474506/image.png" width="500px">
2. Create File
   
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080707473889050644/image.png" width="500px">

3. Write a File

  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080707858146000917/image.png" width="500px">
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080707912638410763/image.png" width="500px">

4. Write File With Echo Command
  
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080708438994210896/image.png" width="500px">
5. Read File With Cat
   
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080708549421838417/image.png" width="500px">

6. Delete File and DIr
   
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080709182967255151/image.png" width="500px">

7. Search File by name
   
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080709555945754766/image.png" width="500px">

8. Truncate File
   
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080710229139935293/image.png" width="500px">

9.  Copy file to another dir
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080710660117241856/image.png" width="500px">

10. Move file to other dir

  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080710972387368970/image.png" width="500px">

11. Login with "sudo"
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080711366643556403/image.png" width="500px">

12. Changing permission file
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080711871251877898/image.png" width="500px">

13. Transfer permission to another user
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080712402582118410/image.png" width="500px">

14. Create user1 and user2
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080712874089000981/image.png" width="500px">

15. Login user1 and create 3 file with 100 bytes size
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080713570301526036/image.png" width="500px">

16. Login User2 and create 3 file with 200 bytes size
    
  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080715001754566676/image.png" width="500px">

17. Change access directory

  <img src="https://cdn.discordapp.com/attachments/940456976234729542/1080716056911417434/image.png" width="500px">
