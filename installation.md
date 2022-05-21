---
layout: page
title: Installation
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/compatibility/">Compatibility</a>
  <a href="https://hystrath.github.io/maintenance/">Maintenance</a>
  <a href="https://hystrath.github.io/installation/">Installation</a>
  <a href="https://hystrath.github.io/sync/">Sync</a>
</div>

<span style="position: fixed;font-size:30px;cursor:pointer; margin:0px; top:60px;left:30px;" onclick="reopenNav()">&#9776;</span>

<script>
function openNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0s";
}

function closeNav() {
  document.getElementById("mySidenav").style.width = "0px";
  localStorage.removeItem('show_sidenav');
}

function reopenNav() {
  document.getElementById("mySidenav").style.width = "210px";
  document.getElementById("mySidenav").style.transition = "0.5s";
  localStorage.setItem("show_sidenav", true);
}

if (localStorage.getItem("show_sidenav")) openNav()
</script>

### OF-v1706
{: #OF-v1706 }

1. In Ubuntu 20.04 LTS or above, downgrade gcc and g++ to version 7
    ```sh
    sudo apt-get install g++-7 gcc-7
    sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-7 7
    sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-7 7
    sudo update-alternatives --config gcc
    sudo update-alternatives --config g++
    ```
    <div style="line-height:50%;">
        <br>
    </div>
2. Download the source .tgz files for Ubuntu (30/06/2017: OpenFOAM v1706) for both [OpenFOAM](https://sourceforge.net/projects/openfoam/files/v1706/OpenFOAM-v1706.tgz) and the [ThirdParty](https://sourceforge.net/projects/openfoam/files/v1706/ThirdParty-v1706.tgz)  
    <div style="line-height:50%;">
        <br>
    </div>
3. Untar them  
    <div style="line-height:50%;">
        <br>
    </div>
4. Install the [system requirements](https://www.openfoam.com/documentation/system-requirements.php)  
    ```sh
    sudo apt-get update
    sudo apt-get install build-essential flex bison cmake zlib1g-dev libboost-system-dev libboost-thread-dev libopenmpi-dev openmpi-bin gnuplot libreadline-dev libncurses-dev libxt-dev
    sudo apt-get install qt4-dev-tools libqt4-dev libqt4-opengl-dev freeglut3-dev libqtwebkit-dev
    sudo apt-get install libscotch-dev libcgal-dev
    ```
    <div style="line-height:50%;">
        <br>
    </div>
5. Install OpenFOAM    
    ```sh
    cd $WM_PROJECT_DIR
    ./Allwmake
    ```
    <div style="line-height:50%;">
        <br>
    </div>
6. Change working directory and clone the hyStrath Github repository   
    ```sh
    cd $WM_PROJECT_USER_DIR
    git clone https://github.com/vincentcasseau/hyStrath.git --branch master --single-branch && cd hyStrath/
    ```
    <div style="line-height:50%;">
        <br>
    </div>
7. Decide which module(s) you wish to install (_NUMPROCS_ is the number of processors to be used)  
    ```sh 
    ./install.sh NUMPROCS 2>/dev/null
    ```
