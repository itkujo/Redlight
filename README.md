
# Currently working on
I am working on different resolutions for these files. 
Once done there will be multiple packages in the downloads each with different resolutions.


# Redlight
Log Bot For "ARK: Survival Evolved"  
  
  An application written in Python to monitor the status of "Tribe Logs"  
  as well provide you with a general overview of the activity  
  in game while not requiring the game window to actually be active.
    
# Example
With "ARK: Survival Evolved" running in the background, you are able to play other games/browse  
while keeping logs completely covered.
      
# Installation/Setup
  ### Either Compile from source or use the pre-compiled Redlight.exe  
  ### *Install the 64bit version of Tesseract.* https://github.com/UB-Mannheim/tesseract/wiki
    
  After Tesseract installs, you will have to set up your Discord Webhooks (2-3)  
  
  ### *A Guide on how to set those up.* https://support.discord.com/hc/en-us/articles/228383668-Intro-to-Webhooks
      
  Once those are out of the way, you will have to get the "roleid" of the Roles that you want to ping in Discord  
    as well as the webhooks for the Redlight.ini  
      
  ### *A Guide on how to do that.* https://discordhelp.net/role-id
    
  Download Redlight and unpack it to one folder then open Redlight.ini.
    
  Redlight.ini
   
    "Log_Alert"
      "alert_urls" = Live Updates
      "log_urls" = General Update
      "ocr_urls" = Image-Text (Works best to pair up with "log_urls"
      
     "Roles"
      "roles" = Main Role ID to Ping
      "svroles" = Server Specific Role (For Multiple Server Support) 
      
  ![image](https://user-images.githubusercontent.com/82180782/155238474-d41629b5-e0a9-4527-8f41-6c58019692bf.png)

  ### In Game Settings
  #### *Set Game Window to* "WindowedFullScreen"  
  ![image](https://user-images.githubusercontent.com/82180782/155028680-aab1fd7f-047f-4b0e-8142-b4fb02633d88.png)  
   
   ### *UI General Scale* (Right Of Screen)  
   ![image](https://user-images.githubusercontent.com/82180782/155028713-5152aafc-9edd-4b9d-bf27-68602134f7d6.png)  
  
  ### *Navigate here*  
  ![image](https://user-images.githubusercontent.com/82180782/155024246-4bb0e11a-4c31-49ac-91e7-06e64c0a674c.png)
    
  ### *From there*
  #### "TOGGLE EXTENDED HUD INFO:" ON  
  ![image](https://user-images.githubusercontent.com/82180782/155024896-a511d9d4-7532-4f5a-b508-0295c2dfa563.png)
  
  #### This should be the end result  
  ![image](https://user-images.githubusercontent.com/82180782/155198274-b654cf8c-4477-4ad3-8dda-d17a5e24f161.png)


  ### *Apply/Save the settings*  
  #### Once back in game
  #### Press (Default) = "H"
  #### Top left of the screen should have this and it should stay there (Actual Day/Time will vary)
  ![image](https://user-images.githubusercontent.com/82180782/155025826-83899ab8-2c3d-45ec-a58c-9543907d4796.png)  

  ### *Global Chat*
  #### Turn Auto-Hide Off  
  ![image](https://user-images.githubusercontent.com/82180782/155028514-013ace64-e3d5-4b51-868c-82e8c99a665f.png)
    
  With Extended Hud and Global open, Open Tribe Logs.  
  Make sure you are using base gamma (Gamma) in the Ark Cosole  
  You are now ready to open Redlight.  
  
  # Running Redlight
  ## Open Redlight  
  ![image](https://user-images.githubusercontent.com/82180782/155197528-ebd314c3-1bc3-4e55-b462-4649f8984a39.png)

  ## Once running you should see this if everything was set up correctly  
  ![image](https://user-images.githubusercontent.com/82180782/155196748-5f828c7c-91d7-4f0f-a25e-0b0714f0f16f.png)

  ## If the logs are NOT open you will see this  
  ![image](https://user-images.githubusercontent.com/82180782/155196916-2ff3eae8-2906-4f7a-98f0-d91ed5072087.png)

  This will happen periodically as the conditions behind the wording "TRIBE LOG" change.  
  The cooldown is 60 seconds and will resume normal scanning operations after the cooldown.  
  Scan interval is currently set to 2 seconds.  
  Scanning will continue while you are doing other things on your computer.  
  
  **You are now protected.**

*-V.*

Donation Link if you feel like it.

https://www.paypal.com/donate/?business=2J7M5MPF79WAE&no_recurring=0&item_name=Redlight+is+a+free+to+use+Log+Bot%2C+if+you+feel+like+donating+then+I+would+like+to+thank+you+in+advance%21+Stay+safe.%0A-V.&currency_code=USD
