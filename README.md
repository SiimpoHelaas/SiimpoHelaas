
----------------------------------------------------------------------------
--------------------------- M0use Ass1gnment -------------------------------
----------------------------------------------------------------------------

local M4 = nil          
local TAQ_56 = nil  		
local STB_556 =   nil             	
local KASTOV_545 = nil     	
local KASTOV_74U = nil   
local KASTOV_762 = nil 
local LACHMANN_556 =  nil    

     
local TAQ_V = nil     
local FTAC_RECON = nil    
local SO_14 = nil   


local MINIBAK = nil                     
local FENNEC45 = nil                       
local VEL46 = nil                       
local BAS_P = nil                      
local M13B = nil 	     
local MX9 =  nil 	  		 
local PDSW528 = nil 	             
local LACHMANN_SUB = nil 	  
local FSS_HURRICANE = nil	 
local VAZNEV_9K = nil	  


local RAAL_MG = nil
local SAKIN_MG38 = nil                      
local RPK = nil    
local RAPPH = nil 
local ICARUS = nil 
local HCR56 =  nil 

local X13_AUTO = nil 


local ALL_OFF = nil



----------------------------------------------------------------------------
--------------------------- Keyb0ard Ass1gnment -------------------------------
----------------------------------------------------------------------------

local M4_Keyboard = nil          
local TAQ_56_Keyboard = nil  		
local STB_556_Keyboard =   nil             	
local KASTOV_545_Keyboard = nil     	
local KASTOV_74U_Keyboard = nil   
local KASTOV_762_Keyboard = nil 
local LACHMANN_556_Keyboard =  nil    

     
local TAQ_V_Keyboard = nil     
local FTAC_RECON_Keyboard = nil    
local SO_14_Keyboard = nil   


local MINIBAK_Keyboard = nil                     
local FENNEC45_Keyboard = nil                       
local VEL46_Keyboard = nil 	     
local BAS_P_Keyboard = nil 	     
local M13B_Keyboard = nil 	     
local MX9_Keyboard =  nil 	  		 
local PDSW528_Keyboard = nil 	             
local LACHMANN_SUB_Keyboard = nil 	  
local FSS_HURRICANE_Keyboard = nil	 
local VAZNEV_9K_Keyboard = nil	  


local RAAL_MG_Keyboard = nil
local SAKIN_MG38_Keyboard = nil                      
local RPK_Keyboard = nil    
local RAPPH_Keyboard = nil 
local ICARUS_Keyboard = nil 
local HCR56_Keyboard =  nil 

local X13_AUTO_Keyboard = nil 


local ALL_OFF_Keyboard = nil


--=========================================================================================---

EnablePrimaryMouseButtonEvents(true);
local copy = falseB
local paste = 0
function OnEvent(event, arg)
 if (event == "MOUSE_BUTTON_PRESSED" and arg == FENNEC45) or
(event == "G_PRESSED" and arg == FENNEC45_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-FENNEC45\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-FENNEC45\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == ALL_OFF) or
(event == "G_PRESSED" and arg == ALL_OFF_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("OFF\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == RAPPH) or
(event == "G_PRESSED" and arg == RAPPH_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-RAPPH\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-RAPPH\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end 
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == X13_AUTO) or
(event == "G_PRESSED" and arg == X13_AUTO_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-X13_AUTO\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-X13_AUTO\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end  
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == VAZNEV_9K) or
(event == "G_PRESSED" and arg == VAZNEV_9K_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-VAZNEV_9K\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-VAZNEV_9K\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == FSS_HURRICANE) or
(event == "G_PRESSED" and arg == FSS_HURRICANE_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-FSS_HURRICANE\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-FSS_HURRICANE\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == TAQ_V) or
(event == "G_PRESSED" and arg == TAQ_V_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-TAQ_V\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-TAQ_V\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == MINIBAK) or
(event == "G_PRESSED" and arg == MINIBAK_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-MINIBAK\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-MINIBAK\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == LACHMANN_SUB) or
(event == "G_PRESSED" and arg == LACHMANN_SUB_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-LACHMANN_SUB\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-LACHMANN_SUB\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == LACHMANN_556) or
(event == "G_PRESSED" and arg == LACHMANN_556_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-LACHMANN_556\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-LACHMANN_556\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == RAAL_MG) or
(event == "G_PRESSED" and arg == RAAL_MG_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-RAAL_MG\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-RAAL_MG\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == KASTOV_74U) or
(event == "G_PRESSED" and arg == KASTOV_74U_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-KASTOV_74U\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-KASTOV_74U\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == KASTOV_762) or
(event == "G_PRESSED" and arg == KASTOV_762_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-KASTOV_762\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-KASTOV_762\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == MX9) or
(event == "G_PRESSED" and arg == MX9_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-MX9\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-MX9\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == FTAC_RECON) or
(event == "G_PRESSED" and arg == FTAC_RECON_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-FTAC_RECON\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-FTAC_RECON\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end 
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == SAKIN_MG38) or
(event == "G_PRESSED" and arg == SAKIN_MG38_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-SAKIN_MG38\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-SAKIN_MG38\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == SO_14) or
(event == "G_PRESSED" and arg == SO_14_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-SO_14\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-SO_14\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end


elseif (event == "MOUSE_BUTTON_PRESSED" and arg == RPK) or
(event == "G_PRESSED" and arg == RPK_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-RPK\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-RPK\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == PDSW528) or
(event == "G_PRESSED" and arg == PDSW528_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-PDSW528\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-PDSW528\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == M13B) or
(event == "G_PRESSED" and arg == M13B_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-M13B\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-M13B\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == BAS_P) or
(event == "G_PRESSED" and arg == BAS_P_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-BAS_P\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-BAS_P\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == VEL46) or
(event == "G_PRESSED" and arg == VEL46_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-VEL46\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-VEL46\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == M4) or
(event == "G_PRESSED" and arg == M4_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-M4\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-M4\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == TAQ_56) or
(event == "G_PRESSED" and arg == TAQ_56_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-TAQ_56\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-TAQ_56\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == STB_556) or
(event == "G_PRESSED" and arg == STB_556_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-STB_556\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-STB_556\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == KASTOV_545) or
(event == "G_PRESSED" and arg == KASTOV_545_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-KASTOV_545\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-KASTOV_545\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
 elseif (event == "MOUSE_BUTTON_PRESSED" and arg == ICARUS) or
(event == "G_PRESSED" and arg == ICARUS_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-ICARUS\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-ICARUS\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
elseif (event == "MOUSE_BUTTON_PRESSED" and arg == HCR56) or
(event == "G_PRESSED" and arg == HCR56_Keyboard) then
    copy = not copy
    paste = arg
    if (copy == false) then
      OutputLogMessage("OFF-HCR56\n")
      if IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
      end
    else
      OutputLogMessage("ON-HCR56\n")
      if not IsKeyLockOn("scrolllock") then
        PressAndReleaseKey("scrolllock")
end
end
end

-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------
   if paste == ALL_OFF or paste == ALL_OFF_Keyboard then
    if copy then
		end
	end	
	
 if paste == M4 or paste == M4_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(5, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(320)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end

 
  if paste == ICARUS or paste == ICARUS_Keyboard then
    if copy then
        repeat
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-4, 0)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end


if paste == TAQ_56 or paste == TAQ_56_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
Sleep(419) 
if not IsMouseButtonPressed(1) then break end MoveMouseRelative(0, 1) 
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end



if paste == HCR56 or paste == HCR56_Keyboard then
    if copy then
        repeat
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17) if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2) Sleep(322)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end end


--------------------------------------------------------------------------------------------
 if paste == STB_556 or paste == STB_556_Keyboard then
    if copy then
        repeat
if not IsMouseButtonPressed(1) then break end
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(323)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end




if paste == KASTOV_545 or paste == KASTOV_545_Keyboard then
    if copy then
        repeat 
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0) Sleep(400)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end 






 if paste == KASTOV_74U or paste == KASTOV_74U_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(332)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end




if paste == KASTOV_762 or paste == KASTOV_762_Keyboard then
    if copy then
	local mult = 1
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
            Sleep(100)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end



if paste == TAQ_V or paste == TAQ_V_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end





if paste == FTAC_RECON or paste == FTAC_RECON_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 14)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(325)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end





 if paste == SO_14 or paste == SO_14_Keyboard then    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 14)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 12)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-2, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0) Sleep(232)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end






if paste == MX9 or paste == MX9_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(400) if not IsMouseButtonPressed(1) then break end MoveMouseRelative(0, 0)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end



 if paste == FSS_HURRICANE or paste == FSS_HURRICANE_Keyboard then    
 if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(232)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end


 if paste == VAZNEV_9K or paste == VAZNEV_9K_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
            Sleep(100)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end




 if paste == RAAL_MG or paste == RAAL_MG_Keyboard then
    if copy then
          repeat
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(1400)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
       
end




 if paste == LACHMANN_556 or paste == LACHMANN_556_Keyboard then    
 if copy then
local mult=1
if IsMouseButtonPressed(1) then
repeat
if IsMouseButtonPressed(1) then
repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1) Sleep(322)
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
until not IsMouseButtonPressed(1)
end
end
end




 if paste == FENNEC45 or paste == FENNEC45_Keyboard then
    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
if not IsMouseButtonPressed(1) then break end
            Sleep(100)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end




--------------------------------------------------------------------------------------------
 if paste == BAS_P or paste == BAS_P_Keyboard then    
 if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end


--------------------------------------------------------------------------------------------
 if paste == VEL46 or paste == VEL46_Keyboard then    
 if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end

--------------------------------------------------------------------------------------------
 if paste == M13B or paste == M13B_Keyboard then    
 if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end


------------------------------------------------------------------------------------------------
 if paste == LACHMANN_SUB or paste == LACHMANN_SUB_Keyboard then    if copy then
        repeat
if not IsMouseButtonPressed(1) then break end
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 10)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 8)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(323)
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end




 


 if paste == MINIBAK or paste == MINIBAK_Keyboard then    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
if not IsMouseButtonPressed(1) then break end
PressAndReleaseMouseButton (1)
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end




 if paste == PDSW528 or paste == PDSW528_Keyboard then    if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0) Sleep(318)
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end



 if paste == SAKIN_MG38 or paste == SAKIN_MG38_Keyboard then
    if copy then
        repeat
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(278) if not IsMouseButtonPressed(1) then break end MoveMouseRelative(1, 0)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end



----------------------------------------------------------------------------------------------
 if paste == RPK or paste == RPK_Keyboard then
    if copy then
        repeat
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(400) if not IsMouseButtonPressed(1) then break end MoveMouseRelative(0, 1)
if not IsMouseButtonPressed(1) then break end
until not IsMouseButtonPressed(1)
end
end



----------------------------------------------------------------------------------------------
if paste == RAPPH or paste == RAPPH_Keyboard then
    if copy then
        repeat
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 7)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 6)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(100)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(-1, 1) Sleep(400)
if not IsMouseButtonPressed(1) then break end MoveMouseRelative(0, 3)
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end





 if paste == X13_AUTO or paste == X13_AUTO_Keyboard then
      if copy then
        repeat
Sleep(5)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 5)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 4)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 2)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(1, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 3)
Sleep(17)if not IsMouseButtonPressed(1)then break end
MoveMouseRelative(5, 3)
Sleep(100)if IsMouseButtonPressed(1)then break end
MoveMouseRelative(0, 0)
Sleep(20) 
if not IsMouseButtonPressed(1) then break end
MoveMouseRelative(0, 7) 
if not IsMouseButtonPressed(1) then break end
if not IsMouseButtonPressed(1) then break end
            if not IsMouseButtonPressed(1) then
                break
            end
        until not IsMouseButtonPressed(1)
    end
end
end
data = dofile[[D:\world.lua]] 
