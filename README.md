# Password manager
This application is for my personal use.

# Installation
#### git clone https://github.com/facelesslucifer/password-manager.git

#### npm install

# Run
## Create a new account
##### npm start -- create -n 'accountname' -u 'accountname' -p 'accountpassword' -m 'masterpassword'
e.g npm start -- create -n 'facebook' -u 'youremail@test.com' -p '12345' -m 'securepassword'

## Fetch a account
##### npm start -- get -n 'accountname' -m 'masterpassword'
e.g npm start -- get -n 'facebook' -m 'securepassword'
