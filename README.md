# UNIX-like File System
## (C, UNIX, Filesystem, CLI, Shell Scripting)                                                                                                              
-  Designed and implemented a UNIX-like file system module called FUFS
-  Leveraged i-node blocks and data blocks to create and track the hierarchical directory structure of the file system
-  Added full feature coverage with browsing, creating, deleting, moving, and listing abilities for files and directories
-  Implemented system calls, user-level shell commands and basic file abstractions (block management, block maps, directories) to facilitate end-to-end interaction with the filesystem
-  Performed disk reads and writes and utilized disk API to allow for persistent storage and restoration of file contents

```
.
├── CMakeLists.txt cmake 
├── main.c   
├── test.c     
├── shell.h     
├── shell.c
├── shell_command.c
├── shell_command.h   
├── fs.c
├── fs.h              
├── fs_def.h        
├── device_io.c
├── device_io.h       
├── fulfs
│   ├── fulfs.h
│   ├── filesystem.c
│   ├── filesystem.h  
│   ├── file_dir.c
│   ├── file_dir.h    
│   ├── base_file.c   
│   ├── base_file.h
│   ├── base_block_file.c 
│   ├── base_block_file.h
│   ├── superblock.c
│   ├── superblock.h      
│   ├── inode.c
│   ├── inode.h      
│   ├── data_block.c
│   ├── data_block.h    
│   ├── block.h          
│   └── def.h
├── memory
│   ├── alloc.c 
│   └── alloc.h          
├── datastruct
│   ├── string.c
│   └── string.h          
└── utils
    ├── log.c
    ├── log.h       
    ├── math.h       
    ├── path.c
    ├── path.h        
    ├── sys.c      
    ├── sys.h
    ├── testtools.c
    └── testtools.h   
```

- Debian GNU/Linux 8.6 (jessie)，armv7l，2G RAM
- gcc version 4.9.2 (Debian 4.9.2-10)
- GNU gdb (Debian 7.7.1+dfsg-5) 7.7.1
- cmake version 3.0.2，GNU Make 4.0
- git version 2.1.4
