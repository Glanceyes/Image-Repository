# Image Repository

<br/>

This repository provides a simple solution for saving images uploaded through [Typora](https://typora.io/), a popular markdown editor. This is also primarily used when writing a post with some images on my [blog](http://glanceyes.tistory.com). When I add an image on markdown file, it is automatically uploaded to this repository by [up2b](https://github.com/thep0y/up2b), one of the Typora uploader written by Python.

<br/>

## Overview

By default, Typora saves uploaded images to a temporary folder. This can be inconvenient if you want to keep your images for future use or to share them with others. This repository provides a simple solution for saving uploaded images to a specific folder in your repository.

<br/>

## Usage

To use this image saver, follow these steps:

1. Clone this repository to your local machine using the following command:

```
bashCopy code
git clone https://github.com/yourusername/typora-image-saver.git
```

1. In Typora, go to Preferences → Image, and then select the option "Copy Image to Custom Folder" under the "Upload" section.
2. Set the folder path to the `images` directory in the cloned repository.
3. Now, when you upload an image in Typora, it will be saved to the `images` directory in your cloned repository.
4. To use the saved image in your markdown file, use the relative path to the `images` folder.

<br/><br/>

## Example

Suppose you have a markdown file named `example.md` in your cloned repository, and you want to insert an image named `image.png` that you uploaded in Typora.

Here's how you can do it:

```
scssCopy code
![Image description](./images/image.png)
```

This will insert the image into your markdown file, and it will be displayed when you view it in Typora or on GitHub.

<br/><br/>

## Acknowledgments

<br/>

This project was inspired by the need to save images uploaded in Typora to a specific folder for future use or sharing.
