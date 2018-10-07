# hackthebox-c1-encryptbd-2018
HackTheBox C1 by EnctyptBD

## Challenge 1:
Richard Tolar is working in a organization as a Vice President of Accounting. A recent data breach leaks this information. Find out the source (website) of data breach.

**Hints: OSINT, Text Storage Site**



## Challenge 2:
Download the image from [here](https://raw.githubusercontent.com/rudSarkar/hackthebox-c1-encryptbd-2018/master/Challenge-2/thumb.rar) **(pwd: 123)**. Analyze it and find the two hidden messages.

**Hints: Cryptography, Stenography**



## Challenge 3:
Download the malware from [here](https://raw.githubusercontent.com/rudSarkar/hackthebox-c1-encryptbd-2018/master/Challenge-3/system.rar) **(pwd: 123)**. Analyze it (dynamic or static), find out its category, identify the C&C server, exploitation methodology and other activities.

Hints: RAT, Windows



## Challenge 4:
Go to this website [here](http://104.129.171.125/). Find out and exploit the two web application vulnerabilities that are exists on this website.

Hints: Wordpress, OWASP Top10

## Challenge 5: There is a mistake in this php code. Re-code it with a the solution.
```PHP
  <?php
        ...
    if ($_SESSION['admin_loggedin'] !== true) {
    header('Location: /log-in.php');
    }
    ...
  ?>
```
Hints: Script Execution
