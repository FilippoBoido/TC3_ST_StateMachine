# TC3_ST_StateMachine
StateMachine Function Block for Twincat 3 projects



				                   					V  Boot()						
								   									|  									 
                                  	|
																	<Init>
								   									|
								   									|	
                                   	|  Start()
                                   	|
                                   	|
																	<Ready> -----------<--------------+-------------<-----------+
								   									|                              	|                         |
                                   	|                             	|                         |
                                   	|                     					|                         |
 								   									|  Execute()					  				|													|
                                   	|                              	|                         |
                                   	|                              	|   Reset()               |
 							  								 <Prepare>                          |                         |
 								   									|                              	|                         |
                                   	|                              	|                         |
                                   	|                              	|                         |
                    	Wait()        |            Fault()           	|                         |
	 		<Waiting> ---<-------->--- <Busy> ----------->----------- <Error>                      	|
				   					EndWait() 	   	|                                                        	|
								   									|	                                                    		|
                                   	|                                                 				|
                                   	|                                                        	|
								   									|  Done()																									|
								   									|                                                        	|
								   									|                                                        	|
								   									|                                                        	|
																	<Idle> ------------------------->---------------------------+
 
