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
</pre></code>
