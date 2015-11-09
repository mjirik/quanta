# QuantAn
Quantitative Analyser

# Install

## Windows 
 
* Use [installer](http://147.228.240.61/queetech/install/setup_quantan.exe)

or

* Install [Anaconda for python 2.7](https://www.continuum.io/downloads) 
* Install QuantAn

        conda install -c mjirik -c SimpleITK quantan
        


## Linux (Ubuntu 14.04)

* Install prerequisites

        sudo apt-get install cmake libinsighttoolkit3-dev libpng12-dev libgdcm2-dev git wget
        wget https://repo.continuum.io/miniconda/Miniconda-latest-Linux-x86_64.sh
        source Miniconda-latest-Linux-x86_64.sh
        conda install numpy scipy pip 
        pip install imtools io3d sed3
        
* Install [skelet3d package](https://github.com/mjirik/skelet3d)

        git clone https://github.com/mjirik/skelet3d.git
        cd skelet3d
        mkdir build
        cd build 
        cmake ..
        make 
        sudo make install
        pip install .

* Install Quantan

        pip install quantan

    
        

# Run 

Run QuantAn with:

        python -m quantan

![img](http://147.228.240.61/queetech/www/quantan01.png)

![img](http://147.228.240.61/queetech/www/quanta03.png)

![img](http://147.228.240.61/queetech/www/quanta07.png)

![img](http://147.228.240.61/queetech/www/quanta08.png)
