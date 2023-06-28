# Hotel-management

This system offers a number of choices, like reserving a room, reviewing customer information, changing or removing any client
and seeing all rooms that have been assigned. Two key C++ concepts-classes and file handling-are used in the project's development.

# Features of Hotel Management System in C++
*Manage Rooms
*Check-In
*Get available rooms
*Search customer
*Check-out room
*Get guest summary report

1.class()
We have created a class for customer having variables like name of size 100, address of size 100, phone of character up to 12
from date of size 20, to_date of size 20, a float payment_advance variable and a booking_id of type int.
We have declared a class room having the variables like type, stype, ac, roomNumber of type int, rent of type int and
status of type int. We have created a object of the customer class cust.
2.class Room rooms[max];  
int count = 0;  
We have declared rooms[max] of room class as global and count as 0;
void Room::searchRoom(int rno)  
In the function addroom, an object of class room is created which will be responsible to add the rooms according to customer need and will ask 
for type AC or NOT then ask for comfort and size of room S or B and daily rent which we will going to set as per need. Rooms added successfully.
3.void Room::displayRoom(Room tempRoom)  
This function search room will help in finding existed room if available. The customer will enter the room number
if the room is found it will show the details of the room.
4.class HotelMgnt : protected Room 
This function will display the rooms only when the customer will enter the room number and chose the type AC or not and comfort and type size etc..
void HotelMgnt::getAvailRoom()  
If a customer wants to make a reservation then this code will come in action. The customer will enter the room number; if that room is booked then
system will flag a text showing room is already booked. If the room was not booked the system will ask for booking id, customer name, ask for enter 
the address, enter the phone number, enter the date you want to take the room and for enter the advance payment. Then the system will flag a text showing Customer checked in successfully.
Hence the output of the system.....
######## Hotel Management #########
1. Manage Rooms
2. Check-In Room
3. Available Rooms
4. Search Customer
5. Check-Out Room
6. Guest Summary Report
7. Exit
#######################################
Enter Option:
