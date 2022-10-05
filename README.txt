The purpose of this document is to explain the functions of the files included in the zip, as well as underline how you can independently verify-, and run the vsniffer.

As there are some known issues with the app I want to make it very clear that you should NOT contact xcom about troubleshooting as he had no part in creating this.

-----------------------
FILES PROVIDED


DpsLogger.class // an altered version of the original class file that allows the capability of vsniffing

Tomato-v1.5+vsniffer.jar // base Tomato app with the following edited classes; "DpsLogger.class"

README.txt // documentation

-----------------------
INSTALLATION (made for Tomato-v1.5 source: https://github.com/X-com/RealmShark/)
** If you do not want to verify the code then simply run the provided jar file after making sure an official copy of Tomato works 


1. Decompile the provided file "DpsLogger.class" using an IDE or any independent decompiling software

2. Verify the contents of the code and make sure there is nothing of malicious intent

3. Download tomato from the official repo: https://github.com/X-com/RealmShark/

4. Use a zipping software like 7-Zip to open the Tomato-v*.jar archive you downloaded from the official repository

5. Replace the existing DpsLogger.class (found in \Tomato-v*.jar\example\damagecalc\<HERE>) from the fresh install of Tomato with the one provided in the zip

-----------------------
USAGE (how to vsniff)


1. Launch the provided,- or the manually edited .jar 

2. Make sure that the software is working, eg chat and DPS is being logged

3. Enter the Shatters and wait a few seconds

4. Switch to the tab "Daily Quests" in the app
      --> if nothing shows up then there's no v, keep the app running and return to Step 3

      --> if there's a v, when going back to nexus close the app and return to Step 1
