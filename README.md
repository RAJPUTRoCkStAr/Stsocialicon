![GitHub license](https://img.shields.io/github/license/RAJPUTRoCkStAr/Streamlit-socialmedia) ![GitHub last commit](https://img.shields.io/github/last-commit/RAJPUTRoCkStAr/Streamlit-socialmedia)
# SocialMediaIcons

`SocialMediaIcons` is a Python class designed to dynamically generate SVG icons for various social media platforms. This class is customizable, allowing users to specify links, colors, and sizes for each social media icon.

## Features

- **Dynamic Icon Generation**: Generates SVG icons based on provided social media links.
- **Customizable Colors**: Default colors are provided for each platform, but users can specify their own.
- **Flexible Sizing**: Supports multiple predefined sizes and allows custom height and width.
               **Just Add links for your profile**


## Installation

You can install Stsocialicon using pip:

```bash
pip install Stsocialicon
```
## Code
```bash
from Stsocialicon import SocialMediaIcons

def main():
    links = [
    "https://www.facebook.com/example",
    "https://www.youtube.com/example",
    "https://www.instagram.com/example",
    "https://www.linkedin.com/example"
    ] #pass social media link here
    sizes = ['sm','lg'] #pass for every social media you are adding

    icon_generator = SocialMediaIcons(social_media_links=links, sizes=sizes).generate_icons()

if __name__ == '__main__':
    main()

```

## Contact
For any questions or feedback, feel free to reach out at [sumitsingh9441@gmail.com](mailto:sumitsingh9441@gmail.com).