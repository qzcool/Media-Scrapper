# Image-Scrapper
An image scrapper that values simplicity and performance. Download the best story under a certain tag automatically. Builded on top of BeautifulSoup4 and Requests.

## Functionality
1. Download all images of a story (url) in the folder under the story name.
2. Create a list of stories by tag (topic), download all images of stories (urls)

[![Sample Story Images](https://s13.postimg.org/f2o9amc8n/image.png)](https://postimg.org/image/9ehyjq7w3/)

## Supported Image Sources
<a href="http://www.bfpgf.com/" target="_blank">福利秀</a>
<a href="http://93.t9p.today/index.php" target="_blank">91自拍论坛</a>

## Deployment Instruction
1. Download the repository to the local path, where the images will be saved.
2. Install Packages Dependencies:
  * tqdm: `pip install tqdm`
  * fake-useragent: `pip install fake-useragent`
  * BeautifulSoup4: `pip install beautifulsoup4`
  * Requests: `pip install requests`
3. Open the `ImageScrapper.ipynb` file with Jupyter Notebook.
4. Select the image source (code block).
5. Alter the url or tag information for your need.
6. Run to start scrapping images.

## Issues
Feel free to report any issues and improvements.

## Disclaimer
**Sharing allergic (adult) contents might be against the law.** This image scrapper is purely for personal academic purpose and therefore not obliged to any legal issues related with non-personal, non-academic purposes.
