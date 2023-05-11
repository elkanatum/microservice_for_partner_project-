Microservice
Microservice Implementation Communication Contract
A.	Clear instructions for how to REQUEST data from the microservice you implemented. Include an example call. 
This example uses Python3: Must use ZeroMQ for socket. Step1) (add code) import zmq Step2) Socket to talk to server - (add code) socket = context.socket(zmq.REQ) Step3) This is a local connection - socket cont. (add code) socket = context.socket(zmq.REQ) Step4) Request data - (add code) socket.send() Example call) 1 | enter_a_digit = input("enter a digit") 2 | socket.send(enter_a_digit.encode())
B.	Clear instructions for how to RECEIVE data from the microservice you implemented.
-Assign receive code to your variable (add code) = socket.recv()
C.	UML sequence diagram showing how requesting and receiving data work. Make it detailed enough that your partner (and your grader) will understand!

