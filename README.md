# quick-clipboard
A lightweight CLI tool written in Java which lets the user load any predefined content into the clipboard.

## Download
The newest version of qc can always be found on the ["Releases" tab on GitHub](https://github.com/nwawrzyniak/quick-clipboard/releases).

## Usage
Write a text file which contains the content you want to load later.

Place it in the ".qc" directory in your user home directory. This directory is created upon the first start of "qc.jar".

Instead of calling qc via the command ```java -jar "path/to/qc.jar" "secret_file"``` you can place the attached script file to any directory within your PATH. If you move only the script and not the .jar file aswell, you should specify the new path in the script file.

Done.

If you want to load the contents of (e.g.) the file "ssh-key" just call ```qc ssh-key``` from the "run" dialog or from the command line.
