# E1-1
코디세이 올인원 E1-1

PS C:\Windows\system32> wsl --shutdown
PS C:\Windows\system32> wsl
wymm01@DESKTOP-9LTHJF0:/mnt/c/Windows/system32$ groups
docker run hello-world
wymm01 adm cdrom sudo dip plugdev users docker
Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
4f55086f7dd0: Pull complete
d5e71e642bf5: Download complete
Digest: sha256:11a3eb1597e864c51b3f56733cb2e8a90bf0c284bfc05f9444d81c558bc848aa
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

wymm01@DESKTOP-9LTHJF0:/mnt/c/Windows/system32$ cd~
Command 'cd~' not found, did you mean:
  command 'cdv' from deb erlang-observer (1:27.3.4.6+dfsg-1)
  command 'cde' from deb cde (0.1+git9-g551e54d-3)
  command 'cdi' from deb cdo (2.5.4-1)
  command 'cdp' from deb irpas (0.10-10build1)
  command 'cd5' from deb cd5 (0.1-4build1)
  command 'cdw' from deb cdw (0.8.1-3build4)
  command 'cdo' from deb cdo (2.5.4-1)
  command 'cdb' from deb tinycdb (0.81-2build1)
Try: sudo apt install <deb name>
wymm01@DESKTOP-9LTHJF0:/mnt/c/Windows/system32$ cd ~
wymm01@DESKTOP-9LTHJF0:~$



wymm01@DESKTOP-9LTHJF0:~$ docker info
Client:
 Version:    29.9.2
 Context:    default
 Debug Mode: false
 Plugins:
  agent: Docker AI Agent Runner (Docker Inc.)
    Version:  v1.152.0
    Path:     /usr/local/lib/docker/cli-plugins/docker-agent
  ai: Docker AI Agent - Ask Gordon (Docker Inc.)
    Version:  v1.33.0
    Path:     /usr/local/lib/docker/cli-plugins/docker-ai
  buildx: Docker Buildx (Docker Inc.)
    Version:  v0.38.1
    Path:     /usr/local/lib/docker/cli-plugins/docker-buildx
  compose: Docker Compose (Docker Inc.)
    Version:  v5.6.1
    Path:     /usr/local/lib/docker/cli-plugins/docker-compose
  debug: Get a shell into any image or container (Docker Inc.)
    Version:  0.49.0
    Path:     /usr/local/lib/docker/cli-plugins/docker-debug
  desktop: Docker Desktop commands (Docker Inc.)
    Version:  4.96.3
    Path:     /usr/local/lib/docker/cli-plugins/docker-desktop
  dhi: CLI for managing Docker Hardened Images (Docker Inc.)
    Version:  v0.0.9
    Path:     /usr/local/lib/docker/cli-plugins/docker-dhi
  extension: Manages Docker extensions (Docker Inc.)
    Version:  v0.2.32
    Path:     /usr/local/lib/docker/cli-plugins/docker-extension
  init: Creates Docker-related starter files for your project (Docker Inc.)
    Version:  v1.4.1
    Path:     /usr/local/lib/docker/cli-plugins/docker-init
  mcp: Docker MCP Plugin (Docker Inc.)
    Version:  v0.44.2
    Path:     /usr/local/lib/docker/cli-plugins/docker-mcp
  model: Docker Model Runner (Docker Inc.)
    Version:  v1.2.9
    Path:     /usr/local/lib/docker/cli-plugins/docker-model
  offload: Docker Offload (Docker Inc.)
    Version:  v0.7.19
    Path:     /usr/local/lib/docker/cli-plugins/docker-offload
  pass: Docker Pass Secrets Manager Plugin (beta) (Docker Inc.)
    Version:  v0.3.2
    Path:     /usr/local/lib/docker/cli-plugins/docker-pass
  sandbox: "docker sandbox" is deprecated, use Docker Sandboxes instead (Docker Inc.)
    Version:  v0.13.0
    Path:     /usr/local/lib/docker/cli-plugins/docker-sandbox
  scout: Docker Scout (Docker Inc.)
    Version:  v1.27.0
    Path:     /usr/local/lib/docker/cli-plugins/docker-scout

Server:
 Containers: 1
  Running: 0
  Paused: 0
  Stopped: 1
 Images: 1
 Server Version: 29.9.2
 Storage Driver: overlayfs
  driver-type: io.containerd.snapshotter.v1
 Logging Driver: local
 Cgroup Driver: cgroupfs
 Cgroup Version: 2
 Plugins:
  Volume: local
  Network: bridge host ipvlan macvlan null overlay
  Log: awslogs fluentd gcplogs gelf journald json-file local splunk syslog
 CDI spec directories:
  /etc/cdi
  /var/run/cdi
 Discovered Devices:
  cdi: docker.com/gpu=webgpu
 Swarm: inactive
 Runtimes: io.containerd.runc.v2 nvidia runc
 Default Runtime: runc
 Init Binary: docker-init
 containerd version: b7a25261e029d68978bbf290df0a62fc819b3c51
 runc version: v1.5.2-0-g29dd3dc2
 init version: de40ad0
 Security Options:
  seccomp
   Profile: builtin
  cgroupns
 Kernel Version: 6.18.54.1-microsoft-standard-WSL2
 Operating System: Docker Desktop
 OSType: linux
 Architecture: x86_64
 CPUs: 8
 Total Memory: 3.681GiB
 Name: docker-desktop
 ID: 38556747-0678-4710-99b5-127ac2be444a
 Docker Root Dir: /var/lib/docker
 Debug Mode: false
 HTTP Proxy: http.docker.internal:3128
 HTTPS Proxy: http.docker.internal:3128
 No Proxy: hubproxy.docker.internal
 Labels:
  com.docker.desktop.address=unix:///var/run/docker-cli.sock
 Experimental: false
 Insecure Registries:
  hubproxy.docker.internal:5555
  127.0.0.0/8
  ::1/128
 Live Restore Enabled: false
 Firewall Backend: iptables



 wymm01@DESKTOP-9LTHJF0:~$ docker images
                                                                                                    i Info →   U  In Use
IMAGE                ID             DISK USAGE   CONTENT SIZE   EXTRA
hello-world:latest   11a3eb1597e8       25.9kB         9.49kB    U
wymm01@DESKTOP-9LTHJF0:~$ docker ps
docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES
CONTAINER ID   IMAGE         COMMAND    CREATED          STATUS                      PORTS     NAMES
a3d897962f35   hello-world   "/hello"   47 minutes ago   Exited (0) 47 minutes ago             clever_pascal



wymm01@DESKTOP-9LTHJF0:~$ docker logs clever_pascal

Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/

wymm01@DESKTOP-9LTHJF0:~$ docker run -it ubuntu bash
Unable to find image 'ubuntu:latest' locally
latest: Pulling from library/ubuntu
d9d511d19a19: Pull complete
435bf5c20694: Pull complete
2e7e55092090: Download complete
Digest: sha256:c098726dd9b9733f3e885f8de0ef375206a311b0a317eadc40d347b1115fb944
Status: Downloaded newer image for ubuntu:latest
root@b144a5bfb216:/# ls
echo hello
exit
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
hello
exit


wymm01@DESKTOP-9LTHJF0:~$ docker ps -a
CONTAINER ID   IMAGE         COMMAND    CREATED          STATUS                      PORTS     NAMES
b144a5bfb216   ubuntu        "bash"     4 minutes ago    Exited (0) 3 minutes ago              determined_proskuriakova
a3d897962f35   hello-world   "/hello"   56 minutes ago   Exited (0) 56 minutes ago             clever_pascal


wymm01@DESKTOP-9LTHJF0:~$ docker run -dit --name myubuntu ubuntu bash
6a29715c3495d9fc4fb3d5c39f5c2c367b04cc747e047dca3d99e9dde74caa6a
wymm01@DESKTOP-9LTHJF0:~$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
6a29715c3495   ubuntu    "bash"    19 seconds ago   Up 17 seconds             myubuntu
wymm01@DESKTOP-9LTHJF0:~$ docker exec -it myubuntu bash



root@6a29715c3495:/# ls
bin  boot  dev  etc  home  lib  lib64  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@6a29715c3495:/# echo hello
hello
root@6a29715c3495:/# exit
exit
wymm01@DESKTOP-9LTHJF0:~$ docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS         PORTS     NAMES
6a29715c3495   ubuntu    "bash"    3 minutes ago   Up 3 minutes             myubuntu
