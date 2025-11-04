# Formula 1 predictor
In line with this modernization and the growing enthusiasm for the sport, we decided to create an application that further stimulates interest in Formula 1 by allowing users to simulate real F1 races. The goal is to develop an app capable of simulating a full F1 race by predicting the final standings of the drivers based on parameters chosen by the user. The customizable parameters include:
- **Drivers:** select up to 20 different drivers (the maximum allowed in a real F1 race) and run the simulation;
- **Circuit:** choose the track where the race will take place;
- **Weather conditions:** select your preferred weather scenario;
- **Number of laps:** set the number of laps (minimum 1, realistically up to 100).

<p align="center"> 
    <img src="Media/Logo.png" alt="Logo" width="15%"">
</p>

## Installation
1. Install the latest version of [Python](https://www.python.org/) on your computer;
2. [Download](https://github.com/John-64/Formula-1-Predictor/archive/refs/heads/main.zip) the project in ZIP format from this repository;
3. Extract it into a new directory named "Formula1Predictor";
4. Open your computer’s terminal and navigate to the project folder by typing:
    ```bash
    cd ./path-fino-alla-cartella/Formula1Predictor
5. Install all required libraries (listed in ```requirements.txt```) in a single step by running:
    ```bash
    pip install -r requirements.txt

6. If everything was installed correctly, run the following command:
   ```bash
   python app.py
   
8. Then click on the following link [link](http://127.0.0.1:5000/) to start using the application!

Have fun!
 
## User Guide
Once the application starts, you’ll see the following webpage:

<p align="center"> 
    <img src="Media/Home.png" alt="Home" width="50%">
</p>

Set your desired parameters, for example:

<p align="center"> 
    <img src="Media/DriverSelected.png" alt="DriverSelected" width="50%">
</p>

Then click the "Predict" button to simulate the race!

<p align="center"> 
    <img src="Media/Output.png" alt="Output" width="50%">
</p>

## Demo
Here’s a short demo of our application:

<p align="center" width="40%">
  <img src="Media/Demo.gif" alt="F1predictor" width="80%">
</p>

## Credits
- [F1](https://www.formula1.com/)
- [Font](https://imjustcreative.com/download-f1-fonts-formula-1-fonts/2021/09/16)
- [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020)
- [Wikipedia](https://it.wikipedia.org/wiki/Formula_1)

## Info
This project was created for the course "Fondamenti Di Intelligenza Artificiale" at the Università degli Studi di Salerno.

## Contribution
If you'd like to contribute to Bloky, please follow these steps:
- Fork the repository;
- Create a new branch (```git checkout -b feature/YourFeatureName```);
- Commit your changes (```git commit -m 'Add some feature'```);
- Push to the branch (```git push origin feature/YourFeatureName```);
- Open a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
