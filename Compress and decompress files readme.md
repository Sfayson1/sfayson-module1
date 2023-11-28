# Compress and decompress files

## Compressing files using the `gzip` command
In the image below you can see that the command `gzip` was used to compress the file Cat.txt. Upon executing the command, when the directory is listed you can see that the Cat.txt file now has a `.gz` destination showing that the file was correctly compressed. 

<img width="715" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/6850a536-f827-46ed-a359-b2fd6be94d30">

## Decompressing files using the `gunzip` command
In the image below you see that the command `gunzip` was to decompress the file Cat.txt.gz. Once the command was executed we listed the contents of the directory where you can now see that the Cat.txt file no longer has the `.gz` destination showing that the file has been decompressed.

<img width="708" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/efd103c2-99da-43a5-8484-a1d103319e05">

## Compressed archive using the `tar` command
In the image below you can see that the command `tar` was used to create a compressed archive and compressed multiple files. 
<img width="925" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/67276686-c8a3-4dde-8622-9427f183cd22">

## Extract the Files from the Compressed Archive
In the image below you see that the command `tar -xzvf archive.tar.gz` is used to decompress the files and extract the files from the archive. 
`-x`: Extracts files from an archive.
`-z`: Uncompresses the archive using gzip.
`-v`: Verbose mode, shows progress in the terminal.
`-f archive.tar.gz`: Specifies the archive file to extract from.

<img width="872" alt="image" src="https://github.com/Sfayson1/sfayson-module1/assets/137829671/360c43b6-165a-44dd-a465-4cd95f6bf022">
