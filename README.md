# Car Dealership Application

## Description of the Project

This is a Java console application that simulates a car dealership management system. Sales managers can search for vehicles by price, make/model, year, color, mileage, or type, as well as view all inventory, add new vehicles, and remove sold ones. The inventory is stored in a pipe-delimited CSV file so data persists between sessions. The app follows an object-oriented architecture with separate classes handling data, file management, and the user interface.

## User Stories

As a customer I want to find vehicles within a price range so that I can see only the cars that fit my budget.

As a customer I want to find vehicles by make and model so that I can search for a specific brand or car I'm interested in.

As a customer I want to find vehicles by year range so that I can narrow down vehicles to a certain age or generation.

As a customer I want to find vehicles by color so that I can find a car in the color I want.

As a customer I want to find vehicles by mileage range so that I can find cars with low or high mileage based on my preference.

As a customer I want to find vehicles by type so that I can filter between cars, trucks, SUVs, and vans depending on what I need.

As a customer I want to list all vehicles so that I can browse everything the dealership has available.

As a dealer I want to add a vehicle to the inventory so that new arrivals show up when customers search.

As a dealer I want to remove a vehicle from the inventory so that sold or unavailable cars no longer show up in searches.

## Setup

Instructions on how to set up and run the project using IntelliJ IDEA.

### Prerequisites

- IntelliJ IDEA: Ensure you have IntelliJ IDEA installed, which you can download from [here](https://www.jetbrains.com/idea/download/).
- Java SDK: Make sure Java SDK is installed and configured in IntelliJ.

### Running the Application in IntelliJ

Follow these steps to get your application running within IntelliJ IDEA:

1. Open IntelliJ IDEA.
2. Select "Open" and navigate to the directory where you cloned or downloaded the project.
3. After the project opens, wait for IntelliJ to index the files and set up the project.
4. Make sure `inventory.csv` exists in the project root folder with the dealership info on the first line and vehicles on the remaining lines.
5. Find the `Program` class in `src/main/java/com/pluralsight/`.
6. Right-click on the file and select 'Run Program.main()' to start the application.

## Technologies Used

- Java 17
- **Git & GitHub** for version control
- `java.io` — FileReader, BufferedReader, FileWriter, BufferedWriter for reading/writing the CSV file
- `java.util` — ArrayList, Scanner for data storage and user input

## Demo

Include screenshots or GIFs that show your application in action. Use tools like [Giphy Capture](https://giphy.com/apps/giphycapture) to record a GIF of your application.

<img width="800" height="773" alt="ScreenRecording2026-05-14at4 04 22AM-ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/b92389c2-7906-4c74-9ba1-06aa6bc5397f" />


## Future Work

Outline potential future enhancements or functionalities you might consider adding:

- Add a sales contract feature so customers can finalize purchases through the app
- Add a lease option alongside the buy option
- Support multiple dealership locations loaded from the same file
- Add input validation with try-catch so bad input doesn't crash the app
- Add sorting options so vehicles can be displayed by price, year, or mileage
- Save a log of all sold vehicles to a separate file for sales history tracking

## Resources

List resources such as tutorials, articles, or documentation that helped you during the project.

- [Java 17 ArrayList Documentation](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/util/ArrayList.html)
- [Java 17 BufferedReader Documentation](https://docs.oracle.com/en/java/javase/17/docs/api/java.base/java/io/BufferedReader.html)
- [W3Schools Java File Handling](https://www.w3schools.com/java/java_files.asp)
- https://raymaroun.github.io/yearup-java-visuals/

## Team Members

- **David Amah** - Solo developer. Built all features including Vehicle, Dealership, DealershipFileManager, UserInterface, and Program classes with search, add, and remove functionality.

## Thanks

Express gratitude towards those who provided help, guidance, or resources:

- Thank you to Raymond for continuous support and guidance.
