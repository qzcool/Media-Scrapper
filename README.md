# Media-Scrapper
A media scrapper that values simplicity and performance. Download the best story under a certain tag automatically. Builded on top of BeautifulSoup4 and Requests.

## Functionality
1. Download all media of a story (url) in the folder under the story name.
2. Create a list of stories by tag (topic), download all media of stories (urls)

[![Sample Story Media](https://s13.postimg.org/f2o9amc8n/image.png)](https://postimg.org/image/9ehyjq7w3/)

## Supported Media Sources
1. [福利秀](http://www.bfpgf.com/)
2. [91自拍论坛](http://93.t9p.today/index.php)

## Deployment Instruction
1. Download the repository to the local path, where the media will be saved.
2. Install Packages Dependencies:
  * tqdm: `pip install tqdm`
  * fake-useragent: `pip install fake-useragent`
  * BeautifulSoup4: `pip install beautifulsoup4`
  * Requests: `pip install requests`
3. Open the `MediaScrapper.ipynb` file with Jupyter Notebook.
4. Select the media source (code block).
5. Alter the url or tag information for your need.
6. Run to start scrapping media.

## Issues
1. Due to the high volume of traffic at night for the media sources, we suggest you to run the MediaScrapper other time.

## Disclaimer
**Sharing allergic (adult) contents might be against the law.** This media scrapper is purely for personal academic purpose and therefore not obliged to any legal issues related with non-personal, non-academic purposes.
