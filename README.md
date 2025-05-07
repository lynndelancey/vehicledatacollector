# vehicledatacollector
VehicleDataCollector is a Java program that collects vehicle data from users, stores it in a linked list, sorts the data by miles per gallon (MPG) in ascending order, and writes the sorted results to a plain text file.

⚡ Features
User Input: Allows users to enter details for multiple vehicles (make, model, and MPG).

Linked List Storage: Utilizes LinkedList<Vehicle> for dynamic storage.

Sorting Mechanism: Sorts vehicle records by MPG in ascending order.

Data Validation: Ensures numeric validation for MPG values.

File Output: Saves sorted records in vehicles.txt for easy review.

🛠️ Technologies Used
Java (LinkedList, Collections.sort())

File Handling (BufferedWriter, FileWriter)

Exception Handling (try-catch)

Version Control (GitHub for repository management)

🚀 How to Run
Clone the repository:

sh
git clone https://github.com/lynndelancey/vehicledatacollector.git
Navigate to the project directory:

sh
cd vehicledatacollector
Compile the Java program:

sh
javac VehicleDataCollector.java
Run the program:

sh
java VehicleDataCollector
Enter vehicle data (make, model, MPG).

Check the output file:

The sorted vehicle list will be saved in vehicles.txt.

📂 File Structure
vehicledatacollector/
│── src/
│   ├── Vehicle.java
│   ├── VehicleDataCollector.java
│── README.md
│── vehicles.txt
│── .gitignore
🔍 Sample Output
Ford Focus - MPG: 30.5
Toyota Corolla - MPG: 35.0
Honda Civic - MPG: 37.8
