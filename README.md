# Gold Miner
A Java Program that showcases AI capabilities using Breath-first Search as an algorithm for a Miner looking for a hidden gold in a grid. This Machine Project was submitted to Dr. Judith Azcarraga as partial completion for the course CSINTSY at De La Salle University. My co-worker for this project is Jordan Sibug.

You may opt to download the JAR file or download the source code, to run the program. I personally suggest downloading the JAR file instead. A JAR File is like a ZIP file for Java classes but acts like an EXE file (So when you download it, then run it, it opens the application easily without necessary extra setup).

## Preview
<p align="center">
  <img src="https://media.giphy.com/media/qetkHgdeZrIhVpdtb4/giphy.gif"/>
</p>

## Downloading the JAR File
- Make sure that Java is installed already (Must be Version 11 or up). You may download Java 11 [here](https://www.oracle.com/ph/java/technologies/javase-jdk11-downloads.html). No need to download JavaFX for running the JAR File.
1. Download the JAR file at http://bit.ly/CSINTSY-GoldMiner
2. After download is finished, you may run it by double-clicking the application. Treat it as an exe file.

## Running the Source Code
- This project was built using the IntelliJ IDEA. Instructions will be clearer if executed using that IDE. Nonetheless, It should be opened by any IDEs.
- Make sure both Java and JavaFX are installed. Download Java 11 [here](https://www.oracle.com/ph/java/technologies/javase-jdk11-downloads.html) and JavaFX 11 [here](https://gluonhq.com/products/javafx/).
1. Clone this repository by running the following in your terminal `git clone https://github.com/cifelse/gold-miner.git`
2. Once done downloading, open the folder as project. Add JavaFX libraries to the Global Libraries of your IDE. Learn how to do it [here](https://youtu.be/WtOgoomDewo).
3. Run the main function located at **Driver.java** (src/Driver.java)

## Disclaimers
* The Default position of the gold is on coordinates (n - 1, n - 1) where n is the size of the n x n grid. So if the grid is 8x8, the default Gold coordinate is at (7, 7).
* There are no beacons and pits in the grid as a default setup, one must add them in order for them to appear.
* The Miner's default location is at (0, 0) which is at the upper left corner of the grid.
* **This application has been designed specifically for monitors having at least 24 inches.** The developers apologize for this. It's still runnable to every computer having Java 11 and up; but the window might be too large for smaller screens. It will still function - It might just be a nuisance for those users with smaller screens.

## License
This repository uses an MIT License. View the [LICENSE](https://github.com/cifelse/gold-miner/blob/main/LICENSE) for full license text.