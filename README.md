# Key Logger
Simple keylogger made in java.
Registers all pressed keys and sends email with log raport every 6 minutes.
<br>
Works on Windows, MacOS, Linux etc.

## How to use it?
- Pull the Project form GitHub or download .jar file and open
- go to ``` demo/src/main/java/com/example/demo/service/KeyLoggerService.java ``` and change <YOUR_EMAIL> to your email ep. abcd@gmail.com (it's in method notifyHost())
- go to command line and use the folowing commands (remember, you have to have Java and Maven installed):
  <br>
  ``` mvn clean package ```
  <br>
  now your .jar file with the program will appear in "target" folder. now you can just take it and run when you will need to
  <br>
  ``` java -jar <path_to_jar_file> ```
  <br>
  you can also checkout some Launch4J tutorial on youtube and create an .exe file
