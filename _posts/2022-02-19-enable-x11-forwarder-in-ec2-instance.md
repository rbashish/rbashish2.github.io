---
title:  "Enable X11 forwarder in EC2 Instance using putty"
mathjax: true
layout: post
categories: media
---

#### Enable X11 Forwarding from EC2 Linux Server to support GUI based installation from EC2 instance

#### Pre-requisite
- EC2 instance (RHEL/Amazon Linux2/Ubuntu)
- Xming
- Putty

### Steps to follow

#### Step 1: Install required X11 package
```
sudo yum install xorg-x11-xauth
```

- Install testing tool
```
sudo yum install xclock xterm
```


