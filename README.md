# project-rdm

## TEXT INDEXING (Verbose the indexer)

1. Make a folder

![Image of image-search-engine](./Screenshoot/textindexing/1.png)

2. Clone the git
![Image of image-search-engine](./Screenshoot/textindexing/2.png)

3. Setting up
- ```sudo apt-get install libgtk-3-dev```
![Image of image-search-engine](./Screenshoot/textindexing/3.png)
- install pip ```sudo apt-get install python3-pip```
![Image of image-search-engine](./Screenshoot/textindexing/4.png)
- ```pip3 install -r requirements.txt```
- if error ```sudo apt-get install build-essential libpoppler-cpp-dev pkg-config python-dev```
![Image of image-search-engine](./Screenshoot/textindexing/5.png)
4. Run the program
- ```python main.py```
![Image of image-search-engine](./Screenshoot/textindexing/6.png)
![Image of image-search-engine](./Screenshoot/textindexing/7.png)


## IMAGE INDEXING (Image Search Engine)

1. Clone the git
![Image of image-search-engine](./Screenshoot/imageindexing/1.png)
2. Setting up
- ```sudo pip3 install -r requirements.txt ```
![Image of image-search-engine](./Screenshoot/imageindexing/2.png)
3. Run the program
- ```cd app```
![Image of image-search-engine](./Screenshoot/imageindexing/3.png)
- ```python3 index.py --dataset static/images --index index.csv```
![Image of image-search-engine](./Screenshoot/imageindexing/4.png)

4. done
![Image of image-search-engine](./Screenshoot/imageindexing/5.png)

## Source

Image indexing : https://github.com/kudeh/image-search-engine
Text indexing  : https://github.com/apurva91/Verbose-The-Indexer
