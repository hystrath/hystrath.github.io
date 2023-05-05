---
layout: page
title: Synchronisation
subtitle: Fleming release
nav-short: true
--- 

<div id="mySidenav" class="sidenav">
  <a href="javascript:void(0)" class="closebtn" onclick="closeNav()"><i class='fa fa-times'></i></a>
  <header>DOWNLOAD</header>
  <a href="https://hystrath.github.io/download/compatibility/">Compatibility</a>
  <a href="https://hystrath.github.io/download/maintenance/">Maintenance</a>
  <a href="https://hystrath.github.io/download/dev/installation/">Installation</a>
  <a href="https://hystrath.github.io/download/dev/sync/" style="background-color:#FFCCCC">Sync</a>
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

### OF-v2112   
{: #OF-v2112 }

1. Change the current working directory to your local *hyStrath* repository
    ```sh 
    cd $WM_PROJECT_USER_DIR/hyStrath
    ```
    <div style="line-height:50%;">
        <br>
    </div>
2. Grab online updates and merge them with your local work
    ```sh
    git pull origin OF-v2112  
    ``` 
    <div style="line-height:50%;">
        <br>
    </div>
3. Decide which module(s) you wish to synchronise  
    ```sh
    ./install.sh 2>/dev/null
    ```
