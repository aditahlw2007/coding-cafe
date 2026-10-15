Q1) What did pwd print?
A) The command pwd or present working directory printed the current path of my system. For example if my laptop was a building PWD told me which floor or wing of the building I am in currently.

Q2) What did ls -a show that plain ls did not?
A) ls -a command showed the hidden directories that the plain ls showed. These hidden directories are very complex and delicate and the computer doesnt like the user to meddle with them. This is why an extra command is needed to view and access them. The full-stops before the names of the directories show which files are the hidden ones and helps in seperating.

Q3) Pick one line from ls -l. What do you think the first column means?
A) I think the first column is the coded format for the directory and the types of files in it type. For example if it is apps, photos or vidoes(mp3/mp4, etc)

Q4) Why does that work from where you are standing? Which kind of path is coding-cafe/week02? Absolute or Relative?
A) The command works from where I am standing as I am already within the Coding-cafe folder(directory in this case) and the path is relative as we are using the slash to direct the computer from the Coding-cafe folder to the Week02 folder within it.

Q5) mv did two different jobs above. What were they?
A) When mv was used first it moved the readme.md from week01 folder to week02 folder but when it was used again it renamed the file from readme.md to old readme.mv. I believe that mv command can be used to both move and rename files.

Q6) How many folders are on your PATH?
A) There are 11 different folders in my PATH. 
apple@Adits-MacBook-Pro-2 ~ %  echo $PATH                                       
/opt/homebrew/bin:/opt/homebrew/sbin:/usr/local/bin:/System/Cryptexes/App/usr/bin:/usr/bin:/bin:/usr/sbin:/sbin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin:/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin

Q7) Write down exactly where your python3 lives.
A) apple@Adits-MacBook-Pro-2 ~ % which python3
/usr/bin/python3

Q8) Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
A) My friends output was: /opt/homebrew/bin/python3
It is different compared to mine as the operating system, installation method and PATH was completely different from mine which caused it to be downloaded in a completely different location compared to mine.

Q9) What exactly did the shell say? Explain the error in your own words, using the word PATH
A) My computer printed pyton3 not found. This means that the computer looks through each folder listed in the PATH to find a program called pyton3. Since there is no pyton3 file, the computer cannot    find it and returns not found.

Q10) .venv did not appear with plain ls. Why not?
A) .venv is a hidden file/directory therefor when used plain ls there was not visible output of .venv, however, when we use ls -a the hidden files are shown and hence we see the .venv file/directory

Q11) What changed about your prompt?
A) A (.venv) tag stuck on the front of the prompt. Example: (.venv) apple@Adits-MacBook-Pro-2 Coding-cafe % instead of apple@Adits-MacBook-Pro-2 Coding-cafe %

Q12) Compare this with what you wrote down for question 7. Is it the same path? If not, what does that tell you about what activate actually did to your PATH?
A) The output is Users/apple/Desktop/Coding-cafe/.venv/bin/python3.
compared to the output in Q7 it shows that the virtual enviiornment has changed the PATH to search for .venv before python3.

Q13) What is in the second list that was not in the first?
A) The first list just shows the version installed of pip and setuptools. The second list contains pip, setuptools, certifi, charset-normalizer, idna, requests, and urllib3. The new additions to the list are from the installation of requests.

Q14) Where does python3 point now?
A) python3 points back to the original PATH from question 7 removing .venv from the PATH.

Q15) Find what ls -h does. Write it in your own words.
A) I think there has been a typo in this question as ls -h works the same as plain ls. ls -lh displays file/directories sizes in a measurable unit system, such as KB, MB, and GB, instead of only showing the exact number of bytes.

Q16) What is the difference between what Ctrl + C and Ctrl + D did?
A) CTRL-C paused the program and then using CTRL-D after that exited the program which is basically using the exit() function without actually typing anything. 