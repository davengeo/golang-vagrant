你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
## Vagrant Virtual Development Environment for GoLang

###  Install Vagrant ###

* Download and install [VirtualBox 5.1.6](https://www.virtualbox.org/wiki/Downloads)
* Download and install [Vagrant 1.8.6](http://www.vagrantup.com/downloads.html)

#### Windows Users ####

- Download [Git for Windows](http://msysgit.github.io/):
  - Run the installer and "next" through the wizard until the step to adjust your PATH environment.
  - Choose the third option, "Run Git and included tools from within the Windows Command prompt"
  - **Important**: On the next step, "Configuring the line ending conversions", choose the second option:       "Checkout as-is, commit Unix-style line endings".
  - Choose "next" through any additional steps to complete the Git for Windows install.
  - Open the Windows Command Prompt as **Administrator**

[Fork](http://github.com/lynnaloo/golang-vagrant/fork) this repository on Github.

Clone your fork of the `golang-vagrant` respository to a directory on your host machine:

    host $ git clone https://github.com/<your-github-username-here>/golang-vagrant.git
    host $ cd golang-vagrant

### Connect to the Virtual Machine ###

Start the virtual machine:

    host $ vagrant up

Connect to the virtual machine via ssh:

    host $ vagrant ssh

Try it out!

    guest $ cd dev
    guest $ go run pi.go
