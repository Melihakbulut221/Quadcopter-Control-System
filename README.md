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
    
    ![image](https://user-images.githubusercontent.com/57303760/181920749-0b34cf99-b7cf-4a04-8e05-b4ae3215cd7f.png)

    
    #Sensors
    ##ultrasound##
    distance above a surface
    
    ##
                               
                            State Estimator  <----      |_______________________|    ---->    Controller
                                                        |Flight Control Software|    
                            Data logging     <----      |_______________________|    ---->    Fault protection
                                
                                
                                
                                
                                

