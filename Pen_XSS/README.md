A powerful XSS scanner made in python 3.7<br/>


## Installing 

Requirements: <br/>

<li> BeautifulSoup4 </li>

```bash
pip install bs4
```
<li> requests </li> 

```bash
pip install requests
```
<li> python 3.7 </li>
<br/>
Commands:

```bash
git clone https://github.com/am9773312/Pen_XSS
chmod 755 -R Pen_XSS
cd Pen_XSS
python3 penxss.py --help 
```
## Usage
Basic usage:

```bash
python3 penxss.py -u http://testphp.vulnweb.com
```
<br/>
Advanced usage:

```bash
python3 penxss.py --help
```

## Main features

* crawling all links on a website ( crawler engine )
* POST and GET forms are supported
* many settings that can be customized
* Advanced error handling
* Multiprocessing support.✔️
* ETC....


## Note

* Sorry for my bad english 
* if you run pwnxss on the win10 terminal you will get an untidy output
* now it doesn't support DOM

