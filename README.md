Download Link: https://assignmentchef.com/product/solved-en-605-788-assignment-3
<br>
In this week’s module, we learned how to set up our development environment for Hadoop, and also learned how to access HDFS using Java API. For this assignment, please do the following:




<ul>

 <li>Create a java command line class called</li>

</ul>

ParallelLocalToHdfsCopy.  This class should be part of bdpuh.hw2 package and should contain the main() method.

<ul>

 <li>The program should take 3 arguments. The first argument should be an absolute directory name on the local filesystem, the second argument should be an absolute directory name in the HDFS file system, and the third argument should be the number of threads to be used for coping.</li>

 <li>The program should ensure that the local directory exists, if it does not, and then print the error message “Source directory does not exist”. The program should then exit.</li>

 <li>The program should ensure that the HDFS destination directory does not exist, and if it does, print an error message. “Destination directory already exists.   Please delete before running the program”.  The program should then exit.  If the HDFS destination directory does not exist, then create the directory.</li>

 <li>The program should start copying files from the source local directory to the target HDFS directory in parallel.</li>

 <li>As the program copies files into HDFS, it should compress the files as .gz</li>

 <li>Assume that there are no subdirectories in the source directory. If you find them, you can ignore them.</li>

 <li>Create 10 files on the source directory and test out your code</li>

</ul>

What to turn in?

<ul>

 <li>Jar file that can be run at command line</li>

 <li>A zip of NetBeans or Eclipse project</li>

 <li>A sample run</li>

</ul>