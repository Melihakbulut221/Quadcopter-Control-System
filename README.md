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
    
    #Sensors
    ##ultrasound##
    distance above a surface
    
    ##
                               
                            State Estimator  <----      |_______________________|    ---->    Controller
                                                        |Flight Control Software|    
                            Data logging     <----      |_______________________|    ---->    Fault protection
                                
                                
                                
                                
                                

