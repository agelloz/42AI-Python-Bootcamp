#Minipack
You have to create a package called ai42. It will have 2 functionalities:
• the progress bar (day00 ex10), that can be imported via import ai42.progressbar
• the logger (day02 ex02) import ai42.logging.log
The package will be installed via pip using the following command:
bash build.sh && pip install ./dist/ai42-1.0.0.tar.gz 
The build.sh script has to create the ai42-1.0.0.tar.gz file.
To ensure the package was properly installed you can run the command pip list. You should be able to see if this is the case as pip list displays the list of installed packages.
