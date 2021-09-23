# ShellScripting
Shell script that accepts project directory name as first operand and searches for any violations in the name of it or its children when compared against a regex.

The poornames script will output a line containing each full file name if and only if the file name’s last component does not follow the guidelines. The full file name should start with D, followed by ‘/’ if D does not already end in ‘/’, followed by the file name component that does not follow the guidelines, and finally followed by a trailing ‘/’ if the named file is a directory. The poornames script should not output duplicate lines. The order of output lines does not matter.

When the script is given a '-r' parameter, it recursively searches all files under the directory name to see if it they follow the correct guidelines.
