##Shell
Aplicatie, interactiva, care ruleaza in terminal si asteapta comenzile tale

* Bash 
* zsh

* `--help` returneza informatii despre comanda. Ex: `ls --help`
* `man <cmd>` - manualul comenzii <cmd> ex: `man ls`

##Variabile in shell 
`<nume_var>=<value_var>` - ex: 


##Files && diectory

* `~` = directorul curent

* pwd - afiseaza directorul curent
* `cd <path>` : schimba directorul curent
* `mkdir <path>` - creare director
* `cp` - copy files and directories
* `mv` - move (rename) files or directories

Ex: `rm -dRf ~/test` - sterge -d = director, -R = recursiv, -f=force(fara confirmare)
* `touch <file_1> [<file_n>]` - creaza fisiere
* `cat <file>' - afisare continut fisier

 

##Diverse

`top` sau `htop` - afisare procese si info system
paginare: 'less' sau 'more'

### Redirectare
 ```
 ls > files.txt  			   //creaz fis files.txt co cout-ul comenzii ls
 ls /home/razvan >> files.txt  //adauga in fisier rez. lui ls
 ```

### Pipe |
  - reirectare iesire (cout) la intrarea (cin) altui program
  
`cat MyFile.cfg | less` - iesirea (cout) lui cat este redirectata ca intrare (cin) la aplicatia less

###screen
- https://www.mattcutts.com/blog/a-quick-tutorial-on-screen/
- http://aperiodic.net/screen/quick_reference

