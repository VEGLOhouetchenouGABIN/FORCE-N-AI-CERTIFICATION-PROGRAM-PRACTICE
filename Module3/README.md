# Module3

## All code on this repository is running on docker container notebook

### So if some person want to do same thing , he can follow these steps:

#### 1-Install docker on your system
     -linux sys:  tape install docker on linux on google and follow all steps in order to install it
     -Windows sys:  tape install docker desktop on windows on google and follow all steps to install it
     
     
#### 2-After that pull this jupyter notebook docker image on your sys: 
##### docker pull akaronte/jupyter-notebook

#### 3- After that run this docker command on your sys in order to create docker container and write code on jupyter notebook:
##### docker run --name  'container-name' -p 8888:8888 -v '/path/to/DIRECORY/YOU/WANT/':/notebook -d akaronte/jupyter-notebook


#### NB: Absoluate path  for this part:  '/path/to/DIRECORY/YOU/WANT/'    also replace this  'container-name'  with your conaiter name