<div align="center">
  <h1 align="center">JPMC Trading Dashboard</h1>

  <p align="center">
    This repo is initially forked from task 3 of JPMC's Forage program. It uses perspective to generate a live graph that displays the data feed in a clear and visually appealing way.
  </p>
</div>

<br>


## Built With
<p align="left"> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> </p>

### Project structure
* `read_data.R`: reads the csv and the json files 
* `generator.R`: source the file, define how many pages and how many products per page to generate. Lastly running the loop, the template file will be read, and the relevant web pages will be generated.
* `Project_template.Rhtml`: template that define the webpages style.
* `product_pages` folder: folder populated with the previously generated webpages 


### Getting Started/Installation

_Below the instruction to set up this project._

1. Install the necessary dependencies by running `npm install` from the project repo
2. Start the python server by running server3.py from the project repo like so:
   ```sh
   python datafeed/server3.py
   ```
   
3. Start the client by running `npm start` from the project repo


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/Rhtml-iterator`)
3. Commit your Changes (`git commit -m 'Add some Rhtml-iterator'`)
4. Push to the Branch (`git push origin feature/Rhtml-iterator`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0). See `LICENSE.txt` for more information.

