# PHP Avenger

> PHP Avenger is a future collection open source of tools writing in PHP with focus in security and hacking.

### Beta

* PHP Avenger sh ( Search Engineer )

### Future Implementation
r
* PHP Avenger bt ( Brute - Force )
* PHP Avenger sca ( State Code Analyse )
* PHP Avenger pwp ( Plugin WordPress )
* PHP Avenger cj ( Component Joomla )

***
#PHP Avenger SH

> Php Avenger sh is a open source tool with idea **based in fork inurlbr by Cleiton Pinheiro**. Basically **PHP Avenger sh** is a tool automates the process of detecting of possibles vulnerabilities in using mass scan and check if true or false. Php Avenger utility search engineers with google, bing and others using dorks ( advanced searching ).

## Instalation 

The recommended way to install PHP Avenger is through
[Composer](http://getcomposer.org).

```bash
# Install Composer
curl -sS https://getcomposer.org/installer | php
```

Next, run the Composer command to install the latest beta version of Php Avenger SH:

```bash
php composer.phar create-project aszone/avenger-sh
cd avenger-sh
```
## Basic Usage

> Use command for init process, result will print in monitor and save in txt on folder results.

### Get trash search

```bash
php avenger sh --dork="site:com.ar ext:sql password"
```
#### Result of trash search
![alt tag](http://lenonleite.com.br/wp-content/uploads/2016/06/imagem1.png)


### Check Sql Injection
```bash
php avenger sh --dork="site:com.ar inurl:php?id=" --check="sqli"
```
#### Result of Sql Injection
![alt tag](http://lenonleite.com.br/wp-content/uploads/2016/06/imagem2.png)
![alt tag](http://lenonleite.com.br/wp-content/uploads/2016/06/imagem3.png)


### Check Local File Download
```bash
php avenger sh --dork="site:com.ar inurl:download.php?file=" --check="lfd"
```
#### Result of Local File Download
![alt tag](http://lenonleite.com.br/wp-content/uploads/2016/06/imagem7.png)


### Check is Admin Page
```bash
php avenger sh --dork="site:com.ar inurl:admin" --check="isAdmin"
```

### Help for commands
```bash
php avenger sh 
```

## Details

#### Search Engineers
* Google
* GoogleApi
* Bing
* DukeDukeGo
* Yahoo
* Yandex

#### Vulnerabilities Checked
* Sql Injection
* Local File Download
* Admin Page

#### Future Vulnerabilities Checked
* RFI
* Xss
* Sensitive Files
    * Dump Files
    * Config Files
    * Open Folders

#### Features development
* Power Search
* Send Mail for results
* Name of TXT
* Proxys
    * TOR
    * Site of Proxys
    * **Virgem Proxys**
    
## Help and docs
* [Documentation](http://phpavenger.aszone.com.br).
* [Examples](http://phpavenger.aszone.com.br/examples).
* [Videos](http://youtube.com/aszone).
* [Stackoverflow](http://phpavenger.aszone.com.br).

