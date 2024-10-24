Setup Instructions 

 

Step 1: Clone the Repository 

 

Step 2: Install Dependencies 

 

Step 3: Set Up MySQL Database: 

CREATE DATABASE LectureClaimDB; 

 

"ConnectionStrings": { 

  "DefaultConnection": "Server=localhost;Database=LectureClaimDB;User=root;Password=your_password;" 

} 

 

Step 4: Run Migrations: 

Add-Migration InitialCreate 

Update-Database 

 

Step 5: Run the Application: 

 

 

Step 6: Access the Application: 

Open your browser and go to http://localhost:5000 (or the port displayed in Visual Studio). 

 
