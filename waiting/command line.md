### command line
<code><pre>
cp * satire/ 
//The * selects all files in the working directory.	 
mv batman.txt spiderman.txt
// By moving 1 into 2, we rename the file as spiderman.txt		
rm waterboy.txt
rm -r comedy
//the -r stands for "recursive", to delete a directory and all of its child diretories.		
echo "Hello"
Hello
//The echo command accepts the string "Hello" as standard input, and echos the string "Hello" back to the terminal as standard output.		
echo "Hello" > hello.txt
//The > command redirects the standard output to a file. Here, "hello" is entered as the standard input. The standard output "Hello" is redirected by > to the file hello.txt.		
cat hello.txt
//The cat command outputs the contents of a file  to the terminal.		
cat glaciers.txt >> rivers.txt
// >> takes the standard output of the command on the left and appends it to the file on the right.		
cat < lakes.txt
// < takes the standard input from the file on the right and inputs it into the program on the left.		
cat volcanoes.txt | wc
// | is a "pipe". The | takes the standard output of the command on the left, and pipes it as standard input to the command on the right.		
sort lakes.txt
//sort takes standard input and orders it alphabetically for the std output.		
uniq deserts.txt
//uniq stands for "unique" and filters out adjacent, duplicate lines in a file.		
grep Mount mountains.txt
//grep stands for "global regular expression print". It searches files for lines that match a pattern and returns the results. It is also case sensitive. grep -i enables the command to be case insensitive.		
grep -R Arctic /home/ccuser/workspace/geography
//grep -R searches all files in a directory and outputs filenames and lines containing matched results. -R stands for "recursive".		
grep -Rl Arctic /home../../..
// l stands for "files with matches". grep -Rl searches the directory for the string and outputs filenames with matched results.		
sed 's/snow/rain/' forests.txt
//sed stands for "stream editor". It accepts standard input and modifies it based on an expression, before displaying it as output data. It is similar to "find and replace". s stands for "substitution", snow is the search string, rain is the replacement string. This command will only replace the first instance of 'snow' on a line.		
sed 's/snow/rain/g' forests.txt
// g expression, meaning "global".
</pre></code>
