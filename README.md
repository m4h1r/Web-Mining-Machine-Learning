# Web-Mining-Machine-Learning
Collecting match data from Maçkolik and predict results acording to this data.

This code block firsly ask you a web link from Mackolik.com This site is contains match results. With WebDriver from selenium library, opens the site. Then it's starting to read some values which is affects the result of match. Between the code blocks it's isolating the numeric metrics from strings. In the end of lines, it's writing metrics to a CSV file, and close the Chrome.

a.py ==> This is the script of adding old football match data from Maçkolik. For instance "http://www.mackolik.com/Match/Default.aspx?id=2843918"
p.py ==> This is the script to predict match results according to archived data.
