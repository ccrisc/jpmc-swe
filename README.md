<div align="center">
  <h1 align="center">JPMC Trading Dashboard</h1>

  <p align="left">
    This repo is initially forked from task 3 of JPMC's Forage program. It uses perspective to generate a live graph that displays the data feed in a clear and visually appealing way.
  </p>
</div>

## Built With
<p align="left"> 
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
</p>

Requires node version 18.10.0

### Project Purpose
This project is built to display data for traders. It uses <a href="https://perspective.finos.org">perspective</a> to generate a live graph that displays the data feed in a clear and visually appealing way for traders to monitor.

The purpose of the graph is to monitor and determine when a trading opportunity may arise as a result of the temporary weakening of a correlation between two stock prices. Given this graph, the trader should be able to quickly and easily notice when the ratio moves too far from the average historical correlation. In the first instance, we'll assume that threshold is +/-10% of the 12-month historical average ratio.

### Project Structure & Preview

The graph tracks the ratio between two stocks over time. Traders want to monitor the ratio of two stocks against a historical correlation with upper and lower bounds. This can help them determine a trading opportunity. Therefore the graph plots also the upper and lower bounds and show when they get crossed.

<img align="center" width="915" alt="Screenshot 2024-07-04 alle 08 57 51" src="https://github.com/cjgb/datanalytics/assets/78849337/2743a885-a783-4ecd-8837-c909eb344ec0">

### Getting Started/Installation

_Below the instruction to set up this project._

1. Install the necessary dependencies by running `npm install` from the project repo
2. Start the python server by running server3.py from the project repo like so:
   ```sh
   python datafeed/server3.py
   ```
3. Start the client by running `npm start` from the project repo
4. Start by clicking "Streaming Data" button

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/jpmc-swe`)
3. Commit your Changes (`git commit -m 'Add some jpmc-swe'`)
4. Push to the Branch (`git push origin feature/jpmc-swe`)
5. Open a Pull Request



<!-- LICENSE -->
## License
See the <a href="https://github.com/theforage/forage-jpmc-swe-task-3">initial repo</a> for more information.

