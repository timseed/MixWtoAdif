# MixWtoAdif
Convert a MIXW Log file into ADIF format



#Steps

  - Get A MixW Log File
  - Install Python
  - pip install ipython[all]
  - jupyter notebook
  
 #Part 1 
 
 Open the MixW file and then look at the output
 
   - in Your Web Browser 
     - open untitled.ipynb
   
   
  Assuming your file is called **MixW2.log**, you should be able to step through the iPYNB code.
  
  If the checks at the bottom - produce some stations > 30 Mhz or below 0 Mhz, you will need to edit the source log file and start from the top.
  
  
  
#Output
 
On runniing the ipynb file to the bottom, you should be left with a file called


**to_load.adif**

Guess what ? you import this file into your logger, I **Stringly** suggest that you backup your logfile prior to doing this.

#Next

Assuming that the ADIF file loaded, you can upload to 

  - eqsl
  - lotw
  
But this now depends on your logging software's capability.
 
 
