# FoundationDB java test application

This is my first attempt at talking to FoundationDB via Java.

It uses gradle as the build system and creates an uber jar by calling the gradle assemble task.

After you have built the project then type
> java -jar fdbtest-1.0-SNAPSHOT-all

to run the program. Of course this does assume that an instance of FoundationDB is running on the host.

If you know Python then you can't go wrong by using Python and interacting with the Python REPL. I don't know Python, hence this project.

The source code has been lifted from the javadocs for the java client for FoundationDB 5.1.7.

This was tested on Windows 10, with JDK 1.8.0_171.