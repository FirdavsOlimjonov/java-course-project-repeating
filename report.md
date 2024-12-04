# Code Reports

---

**Author:** _Firdavs_ | _[email](Firdavs_Olimjonov@student.itpu.uz "Firdavs's email")_ |
**Last Pulish:** 04.12.2024

> - Folder structure has been changed and been made better.
> - [Toy.java](src/main/java/com/itpu/warehouse/Main.java) abstract class has been created and other subclasses which extend [Toy.java](src/main/java/com/itpu/warehouse/Main.java "Path to Toy.java file") in _src/main/java/com/itpu/warehouse/entity_ have been created
> - toString, hashCode, equals methods have been overriden as abstract in [Toy.java](src/main/java/com/itpu/warehouse/Main.java "Path to Toy.java file") file, and they have been overriden in each subclasses
> - [report.md](./report.md "Path to the report.md file") file has been modified and some reports have been written

>
> - DAO implementation has been done
> - [report.md](./report.md "Path to the report.md file") file has been modified and some reports have been written
> - README.me has been added to show some basic information about the warehouse project.

>
> - All builder classes has been refactored,
> - Full javadoc has been written.

>
> 1. Refactoring of the parent class Toy and its subclasses (SoftToy, VehicleToy, PuzzleToy, DollToy, ConstructiveToy).
> 2. Addition of new properties to each subclass (mass for SoftToy, numberOfWheels for VehicleToy, difficulty for PuzzleToy, gender for DollToy, material for ConstructiveToy).
> 3. Implementation of appropriate constructors, builder patterns, and overridden methods (equals, toString, hashCode) in each subclass.

>
> 1. Refactored DAO implementations to improve readability and maintainability.
> 2. Added functionality to DAOImpl classes for retrieving data from CSV files.
> 3. Updated CSV files to include additional fields and corrected formatting.
> 4. Tested all DAOImpl classes to ensure they are working correctly.

>
> 1. Implemented service layer interfaces and corresponding service classes for each type of toy.
> 2. Added mock methods findByCategory and findByPriceRange to DAO and implemented them in respective DAOImpl classes.

>
> 1. Refactored service layer 
> 2. Implemented Controller layer
> 3. Implemented "list" command to test first steps