# Traffic_Light_Simulation_using_loop
This project simulates a traffic light system using Python. It cycles through Red, Green, and Yellow lights with time delays, demonstrating how loops and conditional statements can model real-world processes. The menu-driven program allows users to start or stop the simulation, making it interactive and practical for learning basic programming concepts.
import time
while True:
 print("Traffic Light Simulation")
 print("1. Start Simulation")
 print("2. Exit")
 choice = int(input("Enter your choice: "))
 if choice == 1:
 while True:
 print("RED Light - STOP")
 time.sleep(3)
 print("GREEN Light - GO")
 time.sleep(3)
 print("YELLOW Light - WAIT")
 time.sleep(2)
 # Ask if user wants to stop after one cycle
 stop = input("Do you want to stop simulation? (yes/no): ")
 if stop.lower() == "yes":
 break
 elif choice == 2:
 print("Exiting Traffic Light Simulation. Goodbye!")
 break
 else:
 print("Invalid choice. Try again.")






 
