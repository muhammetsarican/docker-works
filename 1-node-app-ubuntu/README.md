    1  apt-get update
    2  apt install curl -y
    3  curl -sL https://deb.nodesource.com/setup_10.x | bash
    4  apt-get install nodejs -y
    5  ls
    6  cd opt/
    7  ls
    8  mkdir node-app
    9  cd node-app
   10  echo 'console.log("nodejsapp from ubuntu...");' > index.js
   11  cat index.js
   12  node index.js
   13  history