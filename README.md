# Node.js / MongoDB / Ubuntu 14.04 64-bit Vagrant Box

### How to Use
1. Download and install VirtualBox by [clicking here](https://www.virtualbox.org/wiki/Downloads)
2. Download and install Vagrant by [clicking here](http://downloads.vagrantup.com/)
3. Clone this repository.
4. cd node-mongo-vagrant/
5. vagrant up
6. Grab a cup of coffee while you wait for the server to download and install. This will take a little while depending on your internet connection.
7. vagrant ssh
8. Inside the box, comment out the bind_ip line from /etc/mongod.conf. Then Restart the mongod service: sudo service mongod restart

Once you run it the first time, node will run a default server and you can access it by visiting http://localhost:8080 in your browser.

### Further Reading
- [Vagrant Documentation](http://docs.vagrantup.com/)
- [Node.js](http://nodejs.org/api/)
- [MongoDB](http://docs.mongodb.org)
- [Robomongo](http://robomongo.org/)
- [Inspired](https://github.com/markdunphy/node-mongo-vagrant)