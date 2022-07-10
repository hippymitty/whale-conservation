<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** github_username, repo_name, twitter_handle, email, project_title, project_description
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- ABOUT THE PROJECT -->
## About The Project

This purpose of this project is to process large amounts of Physical Oceanography data to be consumed and joined in an easy way. This project in particular focuses on Chlorophyll-a levels to display on a map to help identify concentration levels. For now, individual notebooks are used however there is the aim to create one file/script in future.

If you're wishing to test this with Chlorophyll, dowload data from here:
https://oceancolor.gsfc.nasa.gov/l3/


## Getting Started

To get a local copy up and running follow these simple steps.

### Packages

The below are packages required for this project 
* netCDF4                        
* xarray                                    
* os
* numpy
* matplotlib

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/hippymitty/Chlorophyll.git
   ```
2. Install packages as mentioned above
   ```sh
   pip3 install <package>
   ```

### Data
The below link will take you to EarthData which is a NASA initiative for Ocean Colour. You will need to create an account to download the data. Add this to the Earthdata folder.

https://oceancolor.gsfc.nasa.gov/l3/

## Usage

This can be used to display satellite imagery data and .nc files in a meaninful way to dispaly Physical Oceanography data.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## License

Distributed under the MIT License. See `LICENSE` for more information.


## To do

* Global View and notebook
* Combined notebook/script to run all at once