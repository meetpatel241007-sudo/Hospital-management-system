# Hospital management system 
 
1. Introduction: 
The Hospital Patient Management System is a simple software designed to manage 
patient records and the waiting list in a hospital. With the help of this system, patients 
can be added, searched, displayed, and arranged based on priority. Additionally, a 
queue is used to manage the waiting list efficiently.

2. Objective: 
• To manage patient records efficiently 
• To search for patients using their ID 
• To sort patients based on priority 
• To manage the waiting list using a queue 
• To make the system simple and user-friendly
 
3. System Design / Algorithm: 
Add Patient: 
• Create a new patient node 
• Take input data (ID, Name, Priority) 
• Add the node at the end of the list 
Display Patients: 
• Start from the head 
• Traverse and print each node 
Search Patient: 
• Take ID as input 
• Traverse the list 
• If a match is found, display the patient details 
Sort Patients: 
• Use nested loops 
• Compare priorities 
• Swap data accordingly 
Queue Operations: 
• Enqueue: Add a new patient at the rear 
• Dequeue: Remove a patient from the front 
• Display: Print all elements of the queue

4. Implementation: 
• The system is implemented using the C++ programming language 
• A Patient structure is used to store data 
• Linked List and Queue are implemented manually using pointers 
• A menu-driven program is created where the user can select options 
• Functions used include: 
o addPatient() 
o displayPatients() 
o searchPatient() 
o sortPatients() 
o enqueue(), dequeue(), displayQueue()

5. Conclusion: 
This system efficiently handles basic hospital operations. By using Linked List and 
Queue, data is managed dynamically and in an organized manner. This project is helpful 
in understanding the practical use of data structures and can also be applied in real-life 
scenarios. 
