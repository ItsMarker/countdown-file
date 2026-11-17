# countdown-file
This is the file that I used to add the countdown for my BFDI:Branches 2nd Anniversary Countdown

Steps on how to use it in OBS:
1. Download the file
2. Go to OBS and click on Tools > Scripts
3. Click the plus icon to add the file to OBS
4. Set it for how long you want (e.g. 10 minutes)
5. Add a text source (Must be an already existing element in the current OBS scene)
6. You're all Set!

Customization:
At exactly Line 20 of the code, you can change the specific units that you want to capture, the file is set to show, day, hour, minute and second ("%d:%02d:%02d:%02d", days, display_hours, minutes, seconds) You can change this by changing the text to whatever you want, for example, if I want it to display hours, minutes and seconds only, I can remove the "%d%" from the code and remove the "days" from the code ("%02d:%02d:%02d", display_hours, minutes, seconds)
