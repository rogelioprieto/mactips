# Problem:
How to install gnuplot in mac because isn't an "automatic" installer (dmg file).

# Solution:
Install gnuplot using the terminal (command line).

# About the App:
*App name:* gnuplot  
*App description:* Command-driven interactive function plotting  
*App website:* http://www.gnuplot.info  

# Steps to install the App

1. Press ```Command+Space``` and type ```Terminal``` and press ```enter/return``` key.
2. Run in ```Terminal``` app:
```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" < /dev/null 2> /dev/null
``` 
and press ```enter/return``` key.

If the screen prompts you to enter a password, please enter your Mac's user password to continue. When you type the password, it won't be displayed on screen, but the system would accept it. So just type your _password_ and press ```ENTER/RETURN key```. Then wait for the command to finish.

3. Install gnuplot, run:
```bash
brew install gnuplot
```
Done! You can now use gnuplot.


4. Execute and make an example graphic. Execute in Terminal:
```bash
gnuplot
```
It will appears gnuplot prompt: ```gnuplot>```. 

5. Now you can make a graphic:
```bash
plot sin(x)
```

Source:
<http://macappstore.org/gnuplot/>
