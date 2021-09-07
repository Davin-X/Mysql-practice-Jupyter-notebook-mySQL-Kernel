# Mysql-practice-Jupyter-notebook-mySQL-Kernel
running and practicing MYSQL in Jupyter notebook with MYSQL_KERNEL

In this we will be doing following tasks -> 

1- Installing MySQL-server in Windows (MySQL Sever 8, MySQL workbench 8)

2- installing MySQL kernel for Jupyter

3- running and Practicing MySQL in Jupyter Notebook

Prerequisites => 
 Anaconda Individual Edition having - 
	-  python 3
	- Jupyter Lab / notebook

# 1- installing MySQL-server in Windows 

download mysqlInstaller -

https://cdn.mysql.com//Downloads/MySQLInstaller/mysql-installer-web-community-8.0.26.0.msi

install and setup password 

 # 2 - installing MySQL kernel 
 
 Open anaconda prompt and run->

step1:
```
pip install mysql_kernel
```

To get the newest one from this repo (note that we are in the alpha stage, so there may be frequent updates), type:

```
pip install git+git://github.com/Hourout/mysql_kernel.git
```

#### step2:
Add kernel to your jupyter:

```
python -m mysql_kernel.install
```
now run jupyter notebook 

and create a new Mysql notebook 



---DONE---

# If you want to uninstall it 

## Uninstall

#### step1:

View and remove mysql kernel
```
jupyter kernelspec list

jupyter kernelspec remove mysql
```

#### step2:
uninstall mysql kernel:

```
pip uninstall mysql-kernel
```

ALL DONE!


# 3 - running and Practicing MySQL in Jupyter Notebook

Run Jupyter notebook and create a new mysql notebook

Run following code in a cell

--create connection 

mysql://davin:mysql@localhost:3306

--showing databases

show databases ;
