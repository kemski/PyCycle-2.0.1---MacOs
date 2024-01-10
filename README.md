# PyCycle-2.0.1---MacOs

Dokumentacja PyCycle:

What you need:
https://www.dobreprogramy.pl/android-file-transfer,program,macos,6628556630271617

Instalation:
1. Open Terminal -> Command + space => Type in „Terminal”
2. Install Install Homebrew (packets install manager) by pasting this to terminal: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
3. Install python on your Mac by typing „brew install python” in terminal
4. After you install python on your Mac, you need to restart terminal -> close terminal and open it again (command + space => type in „terminal” and press enter)
5. To check if python was installed successfully type in „python3 --version”, you should receive result:
￼
6. Now we need to install JAVA on your Mac, you can do it by typing „brew install openjdk” in terminal
7. Check if java was installed successfully by typing „java -version” in terminal.  You should receive such result:  If you received error, you have to add JAVA PATH to your environment  echo 'export PATH="/opt/homebrew/opt/openjdk/bin:$PATH"' >> /Users/your_user/.bash_profile Please pay attention to change „your_user” to user name which is displayed in terminal before each execution.
8.  restart your terminal. 
9. After you restart your terminal, check if java was installed successfully by typing „java -version”
10. If everything was installed successfully you should received such result:
11. ￼
12. Go to folder where you have unzipped your PyCycle, right click on PyCycle unzipped folder, chose last option „services”, then run new terminal in folder. 
13. Type in in terminal „sh start.sh”
14. You Should see Graphic interface of app.  You need to paste your API Key and Athlete ID from Intervals.  After that you chose where files should be saved.  Then click generate files. 
￼
23. Generated files will appear in chosen folder, now you need to transfer them to your wahoo via USB. 
24. I highly recommend to use „Android File Transfer App” -> It’s Free, no adds, opens automatically after turn on your Wahoo (while connected via usb)  https://www.dobreprogramy.pl/android-file-transfer,program,macos,6628556630271617, you might search „Android File Transfer” app in google by yourself - if you prefer.
25. Connect Wahoo via usb. 
26. Drag and drop files to plans folder inside your wahoo 



