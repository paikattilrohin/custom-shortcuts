# custom-shortcuts
Create shortcuts to automate tasks on a mac


Steps: 
1) Press command + space button and search to open up spotlight and search for `Automator`. 

2) Select Quick Action and click on choose
 ![Screen Shot 2022-06-03 at 1 15 18 PM](https://user-images.githubusercontent.com/39897345/171913719-767a33e2-0e12-4420-b88e-dc417e628e97.png)



3) Select Run AppleScript
<img width="1004" alt="Screen Shot 2022-06-03 at 1 44 07 PM" src="https://user-images.githubusercontent.com/39897345/171918244-61c0495d-385a-4359-a7c7-6d7130408b6f.png">


4) Change your script {* Your script goes here *} to for example 
To create a shortcut to Open Chrome 
```
on run {input, parameters}
	
	tell application "System Events"
	  tell application "Google Chrome"
	    make new window
    	activate
	  end tell
	end tell
	
	return input
end run
  ```
Or use one of the other examples 

5) Save your script to something unique which you can remember.

6) Open `System Preferences` <br />
>Navigate to `Keyboard`<br />
>Click on the `Shortcuts` tab and then select `Services` and scroll down to the `General` <br />
>You should see your new shortcut that you have created. <br />
>Assign your new shortcut a keyboard shortcuts and ensure that it is selected. <br />
![Screen Shot 2022-06-03 at 3 21 00 PM](https://user-images.githubusercontent.com/39897345/171934602-9dcbe3bb-0133-47a7-be13-d1e868c56ccc.png)

7) Now test your shortcut by pressing the keyboardshortcut and grant any permissions requested. 
        
       
        
   
        
        

