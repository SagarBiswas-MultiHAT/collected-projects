
### README.md

# Collected Projects

Welcome to the **Collected Projects** repository! This is a curated collection of diverse projects ranging from small scripts to more complex applications, covering various programming languages and domains. Whether you're a seasoned developer or a curious learner, you'll find something interesting here.

## Projects Included

- **Project 1:** ASCII Art Generator.
- **Project 2:** Coming Soon.

# **Project 1:** ASCII Art Generator.

![Project 1](https://scontent.fdac138-2.fna.fbcdn.net/v/t39.30808-6/474520305_122137252070552158_5865321978973009289_n.jpg?stp=dst-jpg_s600x600_tt6&_nc_cat=103&ccb=1-7&_nc_sid=127cfc&_nc_ohc=82GRjgtrEr4Q7kNvgGEYRXz&_nc_zt=23&_nc_ht=scontent.fdac138-2.fna&_nc_gid=AuxysnRZKelJAY2Xch1vosZ&oh=00_AYAbjM_HZG8oFvMwQYyXOICdmt9tDjbpurDanu_kpbfeuA&oe=6796A815)

This project is an ASCII Art Generator that converts images into ASCII art. The program processes an image and maps its pixel brightness to corresponding ASCII characters to create a visual representation of the image using text.

## Features

- Converts images to ASCII art.
- Supports different levels of detail and character sets.
- Adjustable settings for gamma correction, filtering, and influence.
- Multi-threaded processing for faster conversion.

## Settings

- `setting_url`: URL of the image to be converted.
- `setting_gamma`: Enable or disable gamma correction.
- `setting_filter`: Enable or disable pixel filtering.
- `setting_multi`: Enable or disable multi-threaded processing.
- `setting_influence`: Enable or disable influence-based scoring.
- `setting_simple`: Use a simple character set.
- `setting_random`: Use a full character set with random selection.
- `setting_width`: Width of the output ASCII art.

## Usage

To run the program, use the following command: **(run with VISUAL STUDIO)**

```sh
./amg-master [options] [image_url] `or`
      set url in the main.cpp file. (at line 16)
            std::string setting_url = "https://scontent.fdac138-2.fna.fbcdn.net/v/t39.30808-6/468189987_562113459758072_5750289707861958507_n.jpg?_nc_cat=101&ccb=1-7&_nc_sid=a5f93a&_nc_eui2=AeHefKBj7Wty44Nzq6Ru5WaRuUp1IScm_DO5SnUhJyb8M6tI5wO459tE1MPbGPC7h7qGaLnICg45eW87wM6nhCOh&_nc_ohc=ldnYZL2HSgUQ7kNvgHM_RDh&_nc_zt=23&_nc_ht=scontent.fdac138-2.fna&_nc_gid=AT0z2ly-ESjNTNy18PxIN7p&oh=00_AYDSSFcgLRAoQ6ZEu4JTqlraf_KBBBskERq8FJmQGQEIEA&oe=6795131E";

```

### Options

- `-g`: Disable gamma correction.
- `-f`: Disable pixel filtering.
- `-m`: Disable multi-threaded processing.
- `-i`: Disable influence-based scoring.
- `-s`: Use a simple character set.
- `-r`: Use a full character set with random selection.
- `-w [width]`: Set the width of the output ASCII art.

## Dependencies

- ATL
- MSXML6
- COM
- ATLImage


# **Project 2:** Turtle-Art-Shinchan-Drawing.

![](https://scontent.fdac138-1.fna.fbcdn.net/v/t39.30808-6/474627949_122137252844552158_4536279369495664682_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=127cfc&_nc_ohc=cZgDnINmiA8Q7kNvgGKfkFJ&_nc_zt=23&_nc_ht=scontent.fdac138-1.fna&_nc_gid=AXT67ffgEwpmeLKz2oubg3a&oh=00_AYBeEGpUq4UJ0mTna5DQs984W6Xvy2v2DZDNDh-Pgl2DGw&oe=6796A8B2)

This project uses Python's Turtle graphics library to draw and animate a character inspired by the popular cartoon figure Shinchan. The program breaks down the character's body parts and accessories, creating a fun and interactive way to explore programming and graphic design with Turtle.

## Features:
- **Shinchan-inspired character:** The figure includes detailed parts like the head, arms, legs, eyes, mouth, and clothing.
- **Interactive graphics:** The program visualizes the drawing process step-by-step, making it engaging for users to follow along.
- **Customizable code:** Modify the drawing functions to tweak Shinchan's features or create your own custom designs.

## Requirements:
- Python 3.x
- Turtle graphics library (usually included with Python installations)

## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/SagarBiswas-MultiHAT/Turtle-Art-Shinchan-Drawing.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Turtle-Art-Shinchan-Drawing
   ```
3. Run the Python script:
   ```bash
   python shinchan_drawing.py
   ```
   
Enjoy watching Shinchan come to life with Turtle graphics!


# Getting Started

To get started with any project in this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/SagarBiswas-MultiHAT/collected-projects.git
   ```
2. Navigate to the project directory of your choice.
3. Follow the individual project instructions provided in their respective folders.

## Contributing

Contributions are welcome! If you have an idea or improvement for any project, feel free to fork the repo and submit a pull request. Please ensure that your contributions are well-documented and tested.



## Contact

For any questions or suggestions, feel free to open an issue or reach out to me on GitHub.

Happy coding!

