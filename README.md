# being-productive
sometimes I'm productive but no commits here I can share some experiences

today I was installing mysql and I was following my tutorial.

➜  ~ sudo nano /etc/paths

than I wrote 

/usr/local/mysql/bin

Everything  done

I wrote mysql --version 

Answer zhs: command not found 

Now I wrote on google the right question and received the right answer 

this guy came on my question I followed the instructions and works perfectly 

https://www.google.com/search?q=zsh+path++mysql&sxsrf=AJOqlzVBr_ELZQHlNZvF8X_e-uWv5VIC6Q%3A1678796875788&ei=S2gQZM7aL9GHxc8PwaOmkAc&ved=0ahUKEwiOrLnbtdv9AhXRQ_EDHcGRCXIQ4dUDCA8&uact=5&oq=zsh+path++mysql&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIGCAAQFhAeMgYIABAWEB46CggAEEcQ1gQQsAM6BAgjECc6CAgAEIAEEMsBSgQIQRgAUOMOWIcuYNMxaAFwAXgAgAHXAYgB1QiSAQUzLjQuMpgBAKABAcgBCMABAQ&sclient=gws-wiz-serp#fpstate=ive&vld=cid:e8213921,vid:oxToe-4c6OM

now I can access mysql with command line

I don't know why but didn't work at all  I'm here from 20:00 till 22:02 and I saw a lot of videos hot to fix the problem when came this across

source zshrc  after typing that Enter and quit iterm when I wrote:
echo $PATH came the whole path including mysql now I can say it works and I can sleep well
 
### codespace

Today I heard about codespace have you? such an amazing thing 

code space is a virtual vscode 😳 that was my face today when I saw it for the first time

### Mysql

today I create my first table 

create table states(
  id INT UNSIGNED NOT NULL AUTO_INCREMENT,
  name VARCHAR(45) NOT NULL,
  abbr VARCHAR(2)  NOT NULL,
  region ENUM('North', 'North East', 'Midwest', 'Southeast', 'South') NOT NULL,
  population DECIMAL(5,2) NOT NULL,
  PRIMARY KEY (id),
  UNIQUE KEY (name),
  UNIQUE KEY (abbr)
);

and the first insert 

NSERT INTO states
    (name, abbr, region, population)
VALUES
    ('Bahia', 'BA', 'North East', 15.34),
    ('Ceará', 'CE', 'North East', 9.02),
    ('Distrito Federal', 'DF', 'Midwest', 3.04),
    ('Espírito Santo', 'ES', 'Southeast', 4.02),
    ('Goiás', 'GO', 'Midwest', 6.78),
    ('Maranhao', 'MA', 'North East', 7.00),
    ('Mato Grosso', 'MT', 'Midwest', 3.34),
    ('Mato Grosso do Sul', 'MS', 'Midwest', 2.71),
    ('Minas Gerais', 'MG', 'Southeast', 21.12),
    ('Pará', 'PA', 'North', 8.36),
    ('Paraíba', 'PB', 'North East', 4.03),
    ('Parana', 'PR', 'South', 11.22),
    ('Pernambuco', 'PE', 'North East', 9.47),
    ('Piauí', 'PI', 'North East', 3.22),
    ('Rio de Janeiro', 'RJ', 'Southeast', 16.72),
    ('Rio Grande do Norte', 'RN', 'North East', 3.51),
    ('Rio Grande do Sul', 'RS', 'South', 11.32),
    ('Rondônia', 'RO', 'North', 1.81),
    ('Roraima', 'RR', 'North', 0.52),
    ('Santa Catarina', 'SC', 'South', 7.01),
    ('São Paulo', 'SP', 'Southeast', 45.10),
    ('Sergipe', 'SE', 'North East', 2.29),
    ('Tocantins', 'TO', 'North', 1.55)
    
    Pretty cool 😎 
    
    Today I covered the crud- create rename update and delete 
    
    


