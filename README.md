
# Lab 2
### ερωτημα 1

#### **401.bzip**

cache_line_size=64                                                                                      

**Time:**                                                                                                         
sim_seconds                              	0.083982                   	# Number of seconds simulated                              
host_seconds                              	1309.57                   	# Real time elapsed on the host

**CPI:**                                                                                               
system.cpu.cpi                           	1.679650                   	# CPI: cycles per instruction

**L2:**                                                                                                          
system.l2.tags.occ_percent::.cpu.inst    	0.002547                   	# Average percentage of cache occupancy          
system.l2.tags.occ_percent::.cpu.data    	0.969911                   	# Average percentage of cache occupancy           
system.l2.tags.occ_percent::total        	0.973719                   	# Average percentage of cache occupancy                     

**L1/i:**                                                                                                                    
system.cpu.icache.tags.occ_percent::total     0.705044                      # Average percentage of cache occupancy

**L1/d:**
system.cpu.dcache.tags.occ_percent::total 	0.984600                   	# Average percentage of cache occupancy

**L1/i/miss**
system.cpu.icache.overall_miss_rate::total 	0.000077                   	# miss rate for overall accesses

**L1/d/miss**
system.cpu.dcache.overall_miss_rate::total 	0.014798                   	# miss rate for overall accesses

**L2/miss**
system.l2.overall_miss_rate::total       	0.282163                   	# miss rate for overall accesses


------------------------------------------------------------------------------------------------------

#### **429hmmer**
**Time:**
sim_seconds                              	0.064955                   	# Number of seconds simulated
host_seconds                              	1618.30                   	# Real time elapsed on the host

**CPI:**
system.cpu.cpi                           	1.299095                   	# CPI: cycles per instruction

cache_line_size=64

**L2:**
system.l2.tags.occ_percent::.cpu.inst    	0.009525                   	# Average percentage of cache occupancy
system.l2.tags.occ_percent::.cpu.data    	0.784390                   	# Average percentage of cache occupancy
system.l2.tags.occ_percent::total        	0.793954                   	# Average percentage of cache occupancy

**L1/i:**
system.cpu.icache.tags.occ_percent::total 	0.776715                   	# Average percentage of cache occupancy

**L1/d:**
system.cpu.dcache.tags.occ_percent::total 	0.996534                   	# Average percentage of cache occupancy

**L1/i/miss:**
system.cpu.icache.overall_miss_rate::total 	0.023612                   	# miss rate for overall accesses

**L1/d/miss:**
system.cpu.dcache.overall_miss_rate::total 	0.002108                   	# miss rate for overall accesses

**L2/miss:**
system.l2.overall_miss_rate::total       	0.055046                   	# miss rate for overall accesses

--------------------------------------------------------------------------------------------------------

#### **456.hmmer**

cache_line_size=64

**Time:**                                                                                                                      
sim_seconds                              	0.059396                   	# Number of seconds simulated                                   
host_seconds                              	1606.29                   	# Real time elapsed on the host                                  

**CPI:**                                                                                                           
system.cpu.cpi                           	1.187917                   	# CPI: cycles per instruction                   

**L2:**                                                                                                               
system.l2.tags.occ_percent::.cpu.inst    	0.039329                   	# Average percentage of cache occupancy
system.l2.tags.occ_percent::.cpu.data    	0.121653                   	# Average percentage of                     
 
**cache occupancy**                                                                                                     
system.l2.tags.occ_percent::total        	0.160981                   	# Average percentage of cache occupancy

**L1/i:**                                                                                                           
system.cpu.icache.tags.occ_percent::total 	0.991227                   	# Average percentage of cache occupancy                  

**L1/d:**                                                                                                       
system.cpu.dcache.tags.occ_percent::total 	0.990023                   	# Average percentage of cache occupancy                  

**L1/i/miss:**                                                                                                  
system.cpu.icache.overall_miss_rate::total 	0.000221                   	# miss rate for overall accesses              

**L1/d/miss:**                                                                                                
system.cpu.dcache.overall_miss_rate::total 	0.001637                   	# miss rate for overall accesses                        

**L2/miss:**                                                                                                            
system.l2.overall_miss_rate::total       	0.077760                   	# miss rate for overall accesses                       


-------------------------------------------------------------------------
 #### **458.sjeng**

cache_line_size=64                                                               

**Time:**                                                                                                                      
host_seconds                              	3116.30                   	# Real time elapsed on the host                          
sim_seconds                              	0.513528                   	# Number of seconds simulated                           

**CPI:**                                                                                                                   
system.cpu.cpi                          	10.270554                   	# CPI: cycles per instruction                                        

**L2:**                     
system.l2.tags.occ_percent::.cpu.inst    	0.000156                   	# Average percentage of cache occupancy    
system.l2.tags.occ_percent::.cpu.data    	0.992025                   	# Average percentage of cache occupancy     
system.l2.tags.occ_percent::total        	0.992198                   	# Average percentage of cache occupancy     

**L1/i:**                                                                                                       
system.cpu.icache.tags.occ_percent::total 	0.751317                   	# Average percentage of cache occupancy    

**L1/d:**                                                                                                             
system.cpu.dcache.tags.occ_percent::total 	0.999594                   	# Average percentage of cache occupancy                  

**L1/i/miss:**                                                                                                           
system.cpu.icache.overall_miss_rate::total 	0.000020                   	# miss rate for overall accesses                               

**L1/d/miss:**                                                                                                                 
system.cpu.dcache.overall_miss_rate::total 	0.121831                   	# miss rate for overall accesses                                

**L2/miss:**                                                                                                            
system.l2.overall_miss_rate::total       	0.999972                   	# miss rate for overall accesses                   


-------------------------------------------------------------------------------------------------------------

#### **470.lbm**

cache_line_size=64                                                                                             

**Time:**                                                                                                      
host_seconds                              	1593.61                   	# Real time elapsed on the host                     
sim_seconds                              	0.174671                   	# Number of seconds simulated                                

**CPI:**                                                                                                                           
system.cpu.cpi                           	3.493415                   	# CPI: cycles per instruction

**L2:**                                                                                                                         
system.l2.tags.occ_percent::.cpu.inst    	0.000293                   	# Average percentage of cache occupancy                 
system.l2.tags.occ_percent::.cpu.data    	0.989336                   	# Average percentage of cache occupancy           
system.l2.tags.occ_percent::total        	0.989629                   	# Average percentage of cache occupancy              

**L1/i:**                                                                                                               
system.cpu.icache.tags.occ_percent::total 	0.681547                   	# Average percentage of cache occupancy     

**L1/d:**                                                                                                         
system.cpu.dcache.tags.occ_percent::total 	0.999455                   	# Average percentage of cache occupancy          

**L1/i/miss:**                                                                                                  
system.cpu.icache.overall_miss_rate::total 	0.000094                   	# miss rate for overall accesses            

**L1/d/miss:**                                                                                                  
system.cpu.dcache.overall_miss_rate::total 	0.060972                   	# miss rate for overall accesses          

**L2/miss:**                                                                                                           
system.l2.overall_miss_rate::total       	0.999944                   	# miss rate for overall accesses                   

##### Τα γραφήματα που απεικονίζουν τις παραπάνω πληροφορίες για το σύνολο των benchmarks:

![What is this](cpi.png)
![What is this](simulation_time.png)
![What is this](l1_instruction_miss.png)
![What is this](l1_data_miss.png)
![What is this](l2_miss.png)

Αυτό που παρατηρήσαμε είναι οτι όσο καλύτερο cpi έχει ενα benchmark τοσο καλύτερο simulation time παρουσιαζεί και τόσα λιγότερα miss εμφανίζει.Συνεπώς στην περίπτωση αυτή έχουμε λιγότερο χρόνο και λιγότερα errors.Επίσής απο τα γραφήματα παρατηρούμε οτι η τιμή των l1_dcache_miss και των l2_cache_miss εμφανίζει αρκέτα όμοια συμπεριφόρα σε αντίθεση με την τιμή των l1_icache_miss που δεν δείχνει σημαντική εξάρτηση απο το cpi ούτε απο κάποια άλλη παράμετρο.

------------------------------------------------------------------------------------------------------------------------------

Επείτα μας ζητήθηκε να εκτελέσουμε ξάνα τα benchmarks με μία επιπλέον παράμετρο,την **--cpu-clock=2GHz** αλλά δεν παράτηρήσαμε κάμια διαφορά στην παραμέτρους που αφορούν το ρολόι.


    

2GHz                                                                                                                                
system.clk_domain.clock                      	1000                   	# Clock period in ticks                          
system.cpu_clk_domain.clock                   	500                   	# Clock period in ticks                              

1GHz                                                                                       
system.clk_domain.clock                      	1000                   	# Clock period in               
system.cpu_clk_domain.clock                   	500                   	# Clock period in ticks                


### ερωτημα 2
Οι τίμές που επιλέξαμε να δώσουμε στις παραμέτρους των benchmarks ώστε να προκύψουν αντίστοιχοι συνδιασμοί είναι:              

cacheline_size=16                                                                                   
cacheline_size=64                                                                                               
l1_data_assoc=1                                                                   
l1_data_assoc=1                                                                   
l1_data_assoc=8                                                                     
l1_data_size=128kB                                                                                           
l1_data_size=32kB







































