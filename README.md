# Facebook-Brute-Force
This script will do login brute force in Facebook with a list of passwords.


# Features
1. Easy to use.
2. Easy code.
3. Colored Texts.
4. Using the fastest host in Facebook.
5. Cookies and headers will change every 4-5 attempts.
6. A random proxy every attempt.


# Screenshots
![](https://lh3.googleusercontent.com/-wYLsAuDg02A/YMPqpL31oOI/AAAAAAAAGsw/RlHmqvrRz3Y2EyhS5GYmb8lBOVC-9CLVgCNcBGAsYHQ/s0/Screenshot%2B2021-06-12%2B003031.png)
![](https://lh3.googleusercontent.com/-yRZABBgyQfk/YMPqpBx3ukI/AAAAAAAAGss/w0mby0CfNMYkf1o-6UIdKNsKXVQO5liTACNcBGAsYHQ/s0/Screenshot%2B2021-06-12%2B004907.png)

# Installation
First, you'll need to have:
1. [Python 3](https://www.python.org/downloads/)
2. pip

Once that's all set up:

1. Clone this repository ```git clone https://github.com/m-primo/Facebook-Brute-Force```.
2. Go to the cloned directory ```cd Facebook-Brute-Force```.
3. Install the requirements ```pip install -r primo-pip-reqs.txt```.


# Run
- Using arguments:
```bash
python app.py -u <USERNAME/ID/EMAIL/PHONE> -p <PASSWORD_LIST_FILENAME> -l <LOG_FILE_NAME>
```
- To use a single password:
```bash
python app.py -u <USERNAME/ID/EMAIL/PHONE> -sp <PASSWORD> -l <LOG_FILE_NAME>
```
-> You can ignore the `-l` (log) argument.
- To get the help message:
```bash
python app.py -h
```
- Or you can just run the app and it'll ask you with the inputs:
```bash
python app.py
```


# Contributing
1. [Fork this repository](https://github.com/m-primo/Facebook-Brute-Force/fork).
2. Clone your repository.
```bash
git clone [your_repo]
```
3. Make & commit your changes.
```bash
git commit -m "[message]"
```
3. Push it.
```bash
git push
```
4. Create a [new pull request](https://github.com/m-primo/Facebook-Brute-Force/pulls) in this repository.


# Disclaimer
THIS REPOSITORY AND EVERY SCRIPT INCLUDED IN IT IS FOR EDUCATIONAL, TESTING, AND RESEARCH PURPOSES ONLY. THE OWNER NOR ANY CONTRIBUTOR IS NOT RESPONSIBLE FOR YOUR ACTIONS.


# License
[WTFPL License](LICENSE)
