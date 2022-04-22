# MorseCodeProject

Fundamentals of Programming II Mini Project: Java application that that reads an English-language phrase and encodes it into Morse code and also that reads a phrase in Morse code and converts it into the English-language equivalent.

What is Morse Code and why we chose it to incorporate it at this project.
- Morse code named after Samuel Morse,  is a method used in telecommunication to encode text characters as standardized sequences of two different signal durations, called dots and dashes, or dits and dahs.To increase the efficiency of encoding, Morse code was designed so that the length of each symbol is approximately inverse to the frequency of occurrence of the character that it represents in text of the English language. Thus the most common letter in English, the letter e, has the shortest code: a single dit. Because the Morse code elements are specified by proportion rather than specific time durations, the code is usually transmitted at the highest rate that the receiver is capable of decoding. Morse code transmission rate (speed) is specified in groups per minute, commonly referred to as words per minute.
We decided to incorporate Morse Code to this project because we thought that it would be  very interesting to combine Morse Code which is an old form of communication,  with a contemporary  programming language as Java is. This project gives us proof that the past era and the present one can be combined perfectly together.

Project Description:
- In our project we have used some codes which are related to the topics we have discussed during Lecture hours. 
Our Project has included: Regular expressions where we have used the split method to add a space between the characters in Morse code. We used String and Char elements for English letters and Morse code. In the end, we have also used the while loop to iterate through the number of cases the user chooses, until program is terminated. 
From Generic Collections we have used some collections framework classes of the package java.util. For example, java.util.Scanner and java.util.Random.:
EclipseIDE is the Integrated Development environment which is used  in order to create this Java application project . This project is sent by  GitHub(collaborative tool for software developers),  where the source code is commented accordingly attached with a ReadMe file.  
Related to this project we hope to learn on how to add more features to the project to add more value and to be more adapted to the programming field.

How to get the development environment set and running:
- The classes that we have imported are: 
// Scanner// which takes inputs  from the user in order to now if user will choose option 1,2,3,4; and what user wants to generate when the code will be executed.
//Random//  is an import which chooses randomly characters whenever we tell the user to generate 
//BufferReader// is a class that simplifies text from user and generally is used  together with //InputStreamReader //
/IOException// catches the mistakes that might happen.
Then we opened  //the Main Class// which is MorseCodeProject
We have used  constructor //Random// which  declares the object  that will take randomly the characters
Then we have an //array// which contains  string type and char (alphabet in  Morse and English)
We use //char randomized Character // to generate random characters from alphabet
Then we have declared string to get the first or second input from user. 
We declare //scanner// which makes easier the reading of the input
Use// do while loop// in order for the method to repeat itself until we take a value between 1-4. Then we have used hasNextInt() method which  repets itself until we have true int value. If the input is not a number from 1 to 4 the code will print ''Error'' or ''PLEASE TRY AGAIN''.
//Choice// is a variable initiated with 0 and will take a value from 1-4
Then, we use switch case which takes the value that the user types and depending on the number we print one of the cases below.  Buffer class simplifies text and together with inputstreamreader use read method. After they read the text, they transform the words in lower case. By using Array we transform this text into a character Array. 
If the user is choosing number one, we have the first case. The code that we wrote: We used a Nested Loop, where first we iterate through this array and we get the length of the words in Morse code and then we want to get the length of English phrase as well. Then, we use an if statement to see if both of the word length are equal. If they are equal, the code should be able to translate the English phrase to Morse code. In the end after the loop is finished we print ‘’Translation’’.
If the user chooses number 2, we have written the code which translates Morse code into English. We use read line method to read the line that the user is typing. Split method is to split the words with a space. We do a string comparison between the lengths of Morse code and English text just like above. Since we have a string comparison we use the .equals method. We read the input of Morse code and then translate it into English words. In the end we print ‘’Translation’’. The second input iterates the letters of English to find the proper translation of Morse code. 
If the user chooses number 3, the code will print a random Character from English letters. 
If the user chooses number 4, the program will be terminated. By using break we terminate the loop.
At the end of the code, we use while loop to iterate the part of choosing a number repeatedly, until they have typed a number from 1 to 4.

How to use this project:
- This project can be used by students that want to explore in programming by adding features that intriguers them more which in this case is the translation of such an ancient code such as Morse is. This way they can practice more on how they incorporate things that they find interesting in java programming. By combining these two programming could be even more fun to learn and use.
