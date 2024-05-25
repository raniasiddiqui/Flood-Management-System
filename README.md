# Flood-Management-System
A flood management system by an NGO is built to track the disastorous effects of floods and allocate aid to areas based on the extent of damage in that particular region. Following are the functional requirements of this system:
* Login: The system lets users to login as district manager or as province manager.
* Function 1a: Login as a district manager. The login form prompts the manager to enter their
details i.e Name, Email, Password. The district manager then can update the inventory and will
record the personalized data of flood victims.
* Function 1b: Login as a province manager. The login form prompts the manager to enter their
details i.e Name, Email, Password. Based on the data updated by the district manager, the
province manager will allocate aid to each area
* Aid Decision making
* Function 2a: The district manager will enter data including loss of human life, damage to
property, destruction of crops, loss of livestock, and deterioration of health conditions owing to
waterborne diseases in each particular area.
* Function 2b: The damage occurred in each district will be converted to its approximate
monetary value. This attribute will be stored in “District” entity. Based on this data collected, the
province manager will then allocate aid to each area.
* Function 2c: Based on the types of diseases spread in each district, the province manager will
assign medical specialists and the type of medications in the inventory.
* Queries
* Function 3a: Province Manager can retrieve information and update information in inventory
assign new shelter camps, add more medical camps etc
* Function 3b: Donors/ Visitors can run queries and retrieve information but can not update
anything. The amount they donate will be added in the total budget.

