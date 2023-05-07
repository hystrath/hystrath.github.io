---
layout: page
title: Installation
subtitle: Dev release
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/download/compatibility/">Compatibility</a>
  <a href="https://hystrath.github.io/download/maintenance/">Maintenance</a>
  <a href="https://hystrath.github.io/download/dev/installation/" style="background-color:#FFCCCC">Installation</a>
  <a href="https://hystrath.github.io/download/dev/installation/#OF-v2112-from-source" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; From Source</a>
  <a href="https://hystrath.github.io/download/dev/installation/#OF-v2112-docker" style="background-color:#FFE6E6; padding-top:4px; padding-bottom:4px">&nbsp;&nbsp; Docker</a>
  <a href="https://hystrath.github.io/download/dev/installation/#OF-v2112-singularity" style="background-color:#FFE6E6; padding-top:4px;">&nbsp;&nbsp; Singularity</a>
  <a href="https://hystrath.github.io/download/dev/sync/">Sync</a>
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

<p align="center">
  <a class="btn btn-outline-dark" href="https://hystrath.github.io/download/fleming/installation/" role="button">Fleming release</a>
  <a class="btn btn-warning" href="https://hystrath.github.io/download/dev/installation/" role="button"><b>Dev release</b></a>
</p>

### From Source
{: #OF-v2112-from-source }

1. Download the source .tgz files for Ubuntu (22/12/2021: OpenFOAM v2112) for both [OpenFOAM](https://sourceforge.net/projects/openfoam/files/v2112/OpenFOAM-v2112.tgz) and the [ThirdParty](https://sourceforge.net/projects/openfoam/files/v2112/ThirdParty-v2112.tgz)  
    ```sh
    sudo apt-get install curl
    curl -L -O https://sourceforge.net/projects/openfoam/files/v2112/OpenFOAM-v2112.tgz
    curl -L -O https://sourceforge.net/projects/openfoam/files/v2112/ThirdParty-v2112.tgz
    ```
    <div style="line-height:50%;">
        <br>
    </div>
2. Untar them  
    ```sh
    tar -zxvf OpenFOAM-v2112.tgz
    tar -zxvf ThirdParty-v2112.tgz
    ```
    <div style="line-height:50%;">
        <br>
    </div>
3. Install the [system requirements](https://www.openfoam.com/documentation/system-requirements.php)  
    ```sh
    sudo apt-get update
    sudo apt-get install build-essential flex bison cmake zlib1g-dev libboost-system-dev libboost-thread-dev libopenmpi-dev openmpi-bin gnuplot libreadline-dev libncurses-dev libxt-dev
    sudo apt-get install qt4-dev-tools libqt4-dev libqt4-opengl-dev freeglut3-dev libqtwebkit-dev
    sudo apt-get install libscotch-dev libcgal-dev
    ```
    <div style="line-height:50%;">
        <br>
    </div>
4. Install OpenFOAM    
    ```sh
    echo -e "\n# OpenFOAM\nalias OF-v2112='source $HOME/OpenFOAM/OpenFOAM-v2112/etc/bashrc'" >> ~/.bashrc
    source ~/.bashrc
    OF-v2112
    cd $WM_PROJECT_DIR
    ./Allwmake
    ```
    <div style="line-height:50%;">
        <br>
    </div>
5. Change working directory and clone the hyStrath Github repository   
    ```sh
    cd $WM_PROJECT_USER_DIR
    git clone https://github.com/hystrath/hyStrath.git --branch OF-v2112 --single-branch && cd hyStrath/
    ```
    <div style="line-height:50%;">
        <br>
    </div>
6. Decide which module(s) you wish to install  
    ```sh 
    ./install.sh 2>/dev/null
    ```

<br>
    
### Docker
{: #OF-v2112-docker }

<br>

### Singularity
{: #OF-v2112-singularity }
