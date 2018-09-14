# vnu-in-batch
Using vnu.jar, validating and producing a result text file on all HTML pages and CSS files within a single zip folder, skipping irrelevant folders.

## instructions
1. download vnu.jar and put it in the same root folder as mark bash script
2. download the zip file and put it in the same root folder
3. type ``` ./mark``` to see usage information
4. result will be stored in ```output.txt``` inside ```dst``` folder

## limitations
1. this bash script is very limited because when I developed it, I had a specific file structure in mind. So the ```parse_folder_name()``` function really is looking for specific string. For example,  "xxx-x x x x-xxx" will produce "x_x_x_x", the string between first "-" and second "-"

## assumptions
- ```unzip``` command is installed
