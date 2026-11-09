BLACK BHUNU INVENTORY MANAGEMENT SYSTEM - C++
=================================

FILES
-----
InventoryManagementSystem.cpp : Complete C++ source code.
DESIGN_AND_TESTING.md          : Algorithm, pseudocode, flowchart and test plan.

REQUIREMENTS
------------
- Windows computer
- Code::Blocks with the MinGW/GCC compiler (or another C++11-compatible compiler)

OPEN AND RUN IN CODE::BLOCKS
----------------------------
1. Extract the ZIP file to a folder you can find easily, such as Documents.
2. Open Code::Blocks.
3. Select File > New > Project.
4. Select Console application, then click Go.
5. Choose C++ and give the project a name, for example InventoryManagementSystem.
6. Choose a project folder and finish the wizard.
7. In the project, open the automatically created main.cpp.
8. Replace its contents with the contents of InventoryManagementSystem.cpp.
   Alternatively, add InventoryManagementSystem.cpp to the project and remove
   the automatically generated main.cpp so there is only one main() function.
9. Select Build > Build and Run (or press F9).
10. Use the numbered menu in the console window.

IMPORTANT
---------
- The program stores up to 100 different items in an array of structures.
- Data is held in memory only. When the program closes, the inventory is lost.
  Permanent file storage was not specified in the assignment requirements.
- Item IDs must be positive and unique. Quantity and price cannot be negative.
- Quantity zero and price zero are accepted.
- The program uses standard C++11 features.

SUGGESTED DEMONSTRATION DATA
----------------------------
ID: 101 | Name: Exercise Book | Quantity: 20 | Price: 12.50
ID: 102 | Name: Blue Pen      | Quantity: 50 | Price: 3.00
ID: 103 | Name: School Bag    | Quantity: 5  | Price: 180.00

Expected total value for these three items:
(20 x 12.50) + (50 x 3.00) + (5 x 180.00) = 1,300.00
