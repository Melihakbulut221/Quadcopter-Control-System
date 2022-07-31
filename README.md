# Quadcopter-Control-System

  ## Workflow of Control Project ##
  
  Requirements --> Understand the system  --> Modelling --> Controller Design --> Testing 

In this repository I will design quad copter control system for mini drones.It's good to be reminded that this control system can be applied to Micro/Very small UAV s(most of the commercial drones belong to this category). Before deep dive into let's look at classification of Unmanned aerial vehicles.
  
  Category             |   Micro/Very small UAVs      |    Mini/Small UAVs      |       Medium UAVs         |    Large UAVs       |               
  ---------------------|------------------------------|-------------------------|---------------------------|---------------------|
  Length/Wingspan:     |         <50 cm               |    >50 cm & < 2 metre   |       5 - 10 metre        |     > 10metre       |
  ---------------------------------------------------------------------------------------------------------------------------------
  
  
                        Commands ---->   |_______________________|       ----> Motor Speeds
                                         |Flight Control Software|
                        Sensors  ---->   |_______________________|       ----> Shut down flag
  
  ------------------------------------------------------------------------------------------------------------------------------------
    
   ![dönme_yönleri](https://user-images.githubusercontent.com/57303760/181937011-3b0ab743-af08-402b-a5af-9f015a8b6266.JPG)
    
   Sensors
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
   Ultrasound           
   
   distance above a surface 
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
   Camera                 
   
   horizontal motion and speed 
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
   Pressure Sensor
   
   altitude          
   
----------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
   IMU
   
   acceleration
   angular rate
    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------    
    Flight Control Software Parts
    -> State Estimator
    -> Controller
    -> Data Logging
    -> Fault Protection
    
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------                                
   YAW       
   Motor front right = +Yaw Cmd
   
   Motor front left = -Yaw Cmd
   
   Motor back right = -Yaw Cmd
   
   Motor back left = +Yaw Cmd
   
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
   PITCH
   
   Motor front right = +Pitch Cmd
   
   Motor front left = +Pitch Cmd
   
   Motor back right = -Pitch Cmd
   
   Motor back left = -Pitch Cmd
   
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
   ROLL
   
   Motor front right = +Roll Cmd
   
   Motor front left = -Roll Cmd
   
   Motor back right = +Roll Cmd
   
   Motor back left = -Roll Cmd
   
-----------------------------------------------------------------------------------
  Circuit Layout 

 From: BNO-055                To:Arduino UNO
 
 
            Vin---------------> 5V  (red)
            GND---------------> GND (black)
            SDA---------------> A4  (green)
            SCL---------------> A5  (blue)
            

  Required Hardware
  Arduino UNO
  BNO-055 9 Axis
   
  Required Software
  MATLAB
  MATLAB Support Package for Arduino Hardware Toolbox
  Sensor Fusion and Tracking Toolbox
  Instrument Control Toolbox
  
  
  Circuit Layout
  From:
  
  
  
   
   
