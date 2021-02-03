# How to analyse some of my personal data owned/hosted by Sony
This is a tiny script (notebook) to analyse some of your personal data : time played per game, time played per week, etc.

You will need to use [R](https://cran.r-project.org/mirrors.html), along with [Rstudio](https://rstudio.com/products/rstudio/download/), which is an awesome app.

1. Ask Sony for your data. First, [write to the email address here](https://www.playstation.com/en-gb/legal/careers-privacy-notice/). You can use [this template](https://github.com/yrochat/sony_personal_data/blob/main/letter_to_sony_template) adapted from the [PersonalData.IO](personaldata.io) website. Big thank you to them! Now you just need to add your name at the bottom. 
2. You will need to prove your identity. Here is what they asked from me<sup>[1](#myfootnote1)</sup>:

    1. The Online ID of the account
    2. The email address associated with the account
    3. The first four and last four digits of the bank card associated with the account
    4. The serial number of the original console associated with the account
    5. The details of a recent transaction made using the account

3. After one month, you receive a file with your personal data. It comes with a password. I had to try a few apps before one worked, so try a few options before complaining to them.
4. Download this folder on your computer.

    1. Find the green button named "Code" and open the menu.
    2. Choose "Download ZIP".
    3. Unzip.
    
5. Move the file you received<sup>[2](#myfootnote2)</sup> in the previous folder.
6. Launch `sony_analysis.Rmd`, [make sure the required packages are installed](http://web.cs.ucla.edu/~gulzar/rstudio/index.html), then Run the whole script and get blown by the time you spent playing video games.

.

[<a name="myfootnote1">1</a>]: If sending these data by email is a problem for you, you can identify yourself by phone. They have a hotline.

[<a name="myfootnote2">2</a>]:  Mine was called `SAR Consolidated WorkBook.xlsx`. If yours too, you don't have anything to change. If the default name has changed, find it in the script and change it.

