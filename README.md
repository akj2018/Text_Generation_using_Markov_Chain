# Text Generation

Text Generation using Markov Chain in Python

![alt text](https://media.giphy.com/media/dQpUkK59l5Imxsh8jN/giphy.gif)

## Description

    1. Client type the shortened URL in the address bar of the browser (bit.ly/short_url)
    2. Browser forwards the request to the bit.ly server
    3. bit.ly server checks the database for short_url and fetches the associated long_url
    4. bit.ly do not returns long_url but redirects to the orginal long_url

### Usage: 

Don't have to remember long URLs


### Installing

* Download Anaconda Installer for Mac/Windows/Linux and install with Path Environment Variable

### Executing program

   1. Download the Mini URL Shortner.ipynb on your system
   2. Run the following command in the download location on cmd
          ```
               jupyter-notebook "Mini URL Shortner.ipynb"
          ``` 
   3. Run the cells in Jupyter notebook
      

## Authors

[Akshay Jain](https://www.linkedin.com/in/akshay-jain-2022)

## Version History

* Version 01
    * Random length (4-6) short url for any given long url
    * Character set for short url includes (a-z)
    * Utilized Python dictionary as a database to replicate backend (key = short URL and value = Long URL)
    * Unique Shortend urls
      
* Version 02
    * Character set expanded to include digits (0-9)

* Version 03
    * Added functionality to use generate custom short URLs using user-input keywords (optional) 
 
* Version 04
    * Also update the long_url mapped to short url after added to the database
 
## Future Updates

- [ ] Add a more advance character set
- [ ] Add GUI
- [ ] Add Documentations
- [ ] Add More Randomization 

   
## References
* Youtube
* Google

This project is licensed under the [Akshay Jain License - see the LICENSE.md file for details
