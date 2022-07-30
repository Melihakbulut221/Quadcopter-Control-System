# Quadcopter-Control-System
In this repository I will design quad copter control system for mini drones.It's good to be reminded that this control system can be applied to Micro/Very small UAV s(most of the commercial drones belong to this category). Before deep dive into let's look at classification of Unmanned aerial vehicles.
  
  Category             |   Micro/Very small UAVs      |    Mini/Small UAVs      |       Medium UAVs         |    Large UAVs       |               
  ---------------------|------------------------------|-------------------------|---------------------------|---------------------|
  Length/Wingspan:     |         <50 cm               |    >50 cm & < 2 metre   |       5 - 10 metre        |     > 10metre       |
  ---------------------------------------------------------------------------------------------------------------------------------
  
  
                                      Commands ---->   |-----------------------|       ----> Motor Speeds
                                                       |Flight Control Software|
                                      Sensors  ---->   |-----------------------|       ----> Shut down flag
  
  
  
                               
                                      State Estimator  <----      |-----------------------|    ---->    Controller
                                                                  |Flight Control Software|    
                                      Data logging     <----      |-----------------------|    ---->    Fault protection
                                
                                
                                
                                
                                

