# docker-demo
Files and instructions needed to follow along with my https://slides.com/ryanwalls/first-dip-off-the-docker presentation

# Steps to do while we're waiting to get started
*  Download and install VirtualBox.  https://www.virtualbox.org/wiki/Downloads
*  Install Docker https://docs.docker.com/installation
*  Install Docker Compose

   ```bash
   curl -L https://github.com/docker/fig/releases/download/1.1.0-rc1/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose; chmod +x /usr/local/bin/docker-compose
   ```
   
*  Clone this repo.  
*  Make sure `docker-machine` is executable by running  `chmod +x docker-machine`
*  Copy `docker-machine` into some directory that is on your path.  e.g.  /usr/local/bin. This binary is a build of docker machine from Jan 27, 2015 with this commit as the latest: https://github.com/docker/machine/commit/c209704f5affc9e3adfad383d8cefdb9abc1a5c0

