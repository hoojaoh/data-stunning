# Stunning

Stunningly beautiful photos and images from around the web.

## Description

For over a decade I have been collecting beautiful pictures to use as my wallpaper on my computer. I decided to migrate the photos and images to this repository to make it easier to work with and share.

## How to Use

If you do not have a copy of [git](https://git-scm.com/), [download it and install it](https://git-scm.com/downloads).

Type the following command into a command prompt:

```bash

git clone https://github.com/grantcarthew/data-stunning stunning

```

__WARNING: This is a large repository. Expect it to take a while to clone.__

This will create a directory called `stunning` on your computer.

Once you have a copy of this repository, use it anyway you want. I point my screensaver or wallpaper configuration at the images directory using a `slideshow` mode.

## Image Sources

* [Wikipedia Featured pictures](https://en.wikipedia.org/wiki/Wikipedia:Featured_pictures)
* [Wiki Loves Earth](http://wikilovesearth.org/) ([Wikipedia](https://en.wikipedia.org/wiki/Wiki_Loves_Earth))
  * [2019 Winners](https://wikimediafoundation.org/news/2019/12/02/imagination-becomes-reality-in-the-winners-of-the-2019-wiki-loves-earth-photo-contest/)


Other image sources will be added as time goes by. The biggest restriction on adding images is the requirement on an open license. I see a lot of amazing pictures on [reddit](https://www.reddit.com/r/Pictures/) however they are not licensed or are small sizes.

Please open an [issue](https://github.com/grantcarthew/data-stunning/issues) if you know of another source of stunning images that have an open license.

## Image Details

The `Images` directory contains beautiful photos and images of locations from around the globe and beyond.

See the [Images.csv](Images.csv) file for image details.

The CSV attributes are as follows:

* Location - Typically the country however it may be a location in space or other planets.
* Name - The name of the image.
* Description - A brief description of the image. Place in quotation marks.
* FileName - The file name within this repository. This may not be the original file name.
* SourceName - Where the image came from such as Wikipedia etc.
* SourceUrl - The original URL the images was downloaded from. Use for license and other image details.

## Naming Standard

The image files follow a naming standard of `[Country or Location]-[Short]-[Name]-[of]-[image].jpg`. Use capitals as you would in a normal english name and replace spaces with hyphens.

Example:

If I have an image of the [Three Sisters in Australia](https://en.wikipedia.org/wiki/Three_Sisters_(Australia)) the file name would be `Australia-Three-Sisters.jpg`

## Contribute

If you find or create an image that you want to add to this repository make sure that it meets these requirements:

* Uses an open license permitting copying and use of the image.
* The image is stunning. Not just a good picture.
* The image is of high quality both in sharpness and size.

If you believe you have the right image to enhance this repository, follow these steps:

1. Fork this repository.
1. Check that the license is listed in the [LICENSE](LICENSE.md) file. Add it if it is not.
1. Add your image following the naming standard described above.
1. Edit the `Images.csv` file adding the image details.
1. Send a pull request.

_Note: If the source URL has one or more commas in it you will need to replace them with `%2C` when pasting into the `README.csv` file._
