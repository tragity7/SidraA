good luck to me I guess

DIRECTORIES
$ pwd: Display path of current working directory
$ cd <directory>: Change directory to <directory>
$ cd.. : Navigate to parent directory
$ ls: list directory contents
$ ls -la: List detailed directory contents, including hidden files
$ mkdir <directory>: Create new directory named <directory>

OUTPUT
$ cat <file>: Output the contents of <file>
$ less <file>: Output the contents of <file> using the less command (which supports pagination etc.)
$ head <file>: Output the first 10 lines of <file>
$ <cmd> > <file>: Direct the output of <cmd> into <file>
$ <cmd> >> <file>: Append the output of <cmd> to <file>
$ <cmd1> | <cmd2>: Direct the output of <cmd1> to <cmd2>
$ clear: Clear the command line window

FILES
$ rm <file>: Delete <file>
$ rm -r <directory>: Delete <directory>
$ rm -f <file>: Force-delete <file> (add -r to force-delete a directory)
$ mv <file-old> <file-new>: Rename <file-old> to <file-new>
$ mv <file> <directory>: Move <file> to <directory> (possibly overwriting an existing file)
$ cp <file> <directory>: Copy <file> to <directory> (possibly overwriting an existing file)
$ cp -r <directory1> <directory2>: Copy <directory1> and its contents to <directory2> (possibly overwriting files in an existing directory)
$ touch <file>: Update file access & modification time (and create <file> if it doesn’t exist)

PERMISSIONS
$ chmod 755 <file>: Change permissions of <file> to 755
$ chmod -R 600 <directory>: Change permissions of <directory> (and its contents) to 600
$ chown <user>:<group> <file>: Change ownership of <file> to <user> and <group> (add -R to include a directory’s contents)

SEARCH
$ find <dir> -name "<file>": Find all files named <file> inside <dir> (use wildcards [*] to search for parts of filenames, e.g. "file.*")
$ grep "<text>" <file>: Output all occurrences of <text> inside <file> (add -i for case-insensitivity)
$ grep -rl "<text>" <dir>: Search for all files containing <text> inside <dir>

NETWORK
$ ping <host>: Ping <host> and display status
$ whois <domain>: Output whois information for <domain>
$ curl -O <url/to/file>: Download <file> (via HTTP[S] or FTP)
$ ssh <username>@<host>: Establish an SSH connection to <host> with user <username>
$ scp <file>
<user>@<host>:/remote/path: Copy <file> to a remote <host>

PROCESSES
$ ps ax: Output currently running processes
$ top: Display live information about currently running processes
$ kill <pid>: Quit process with ID <pid>

man <command> OR <command> --help: receive detailed documentation about the command in question
