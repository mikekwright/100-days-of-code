# 100 Days Of Code - Log

<a name="toc"></a>
### Table of Contents 
|Day|Focus|Day|Focus|
|:---:|:-----:|:---:|:-----:|
|[Day 1](#day-1) **06/14/2018** | Scala refresher, Codingame Challenge |[Day 2](#day-2) **06/15/2018** | Codingame Challenge, DataSources search |
|[Day 3](#day-3) **06/16/2018** | Environment setup with Scala Notebook, Breeze |[Day 4](#day-4) **06/17/2018** | Raspberrypi Kubernetes cluster setup (start)|
|[Day 5](#day-5) **06/18/2018** | Raspberry Pi Model B+ Kub, Breeze Study | | |

<!--- 
|[Day 1](#day-1) **--/--/--**| Topics |[Day 2](#day-2) **--/--/--**| Topics |
--->

----------
<a name="day-0"></a>
### Day 0: June 13, 2018  

**Today's Focus**: Committing to 100 days of coding and coming up with a plan. 

**Details**:

Today I received an email from [codingame.com](https://www.codingame.com/) that contained an article with
an interesting idea and one that I had not come across.  Namely it was about doing a challenge called
the #100DaysOfCode in which you would commit to spending 1 hour a day improving your coding abilities.  

[The article](https://www.codingame.com/blog/100-days-of-code-challenge) was written by 
[Jason Down](https://twitter.com/jasondown) who shared an overview of his experiences as well as tools
that he used to complete the challenge.  I was inspired and spent a bit of time looking more into
the [#100DaysOfX](http://100daysofx.com/) which gave more details around to challenge and
other potential challenges that I am going to participate in concurrently.  

With all that in place I want to layout some ideas, topics and potential projects that I may spend some of 
my time over the next 100 days.  

- Work towards completing the [DataQuest](https://www.dataquest.io/) "Data Scientist in Python Path"
- Create simple sample ML project using NLP and Scala
- Build a unity or godot game to use as engine for reinforcement learning
- Build webapp using Elm/Elixir (Trying to decide purpose of webapp)
- Increase language skills for golang, kotlin, erlang or julia
- Complete more challenges at [codingame](https://www.codingame.com/), [hackerrank](https://www.hackerrank.com) or [exercism.io](http://exercism.io)

I am very excited to have a reason to start the challenge and to help myself grow.  Let's see what the future
holds.  

__NOTE__: I wonder if the summer was a bad time to start get started with vacations and camping... let's hope I
can find a wifi signal ¯\\_(ツ)_/¯ 

----------
<a name="day-1"></a>
### Day 1: June 14, 2018

**Today's Focus**: In order to help me get setup and ready to go through the Scala ML problem I decided
to have a quick refresher on Scala by reading docs and going through codingame problem.  

**Details**:  The problem that I worked on was a simple one, [Chuck Norris](https://www.codingame.com/training/easy/chuck-norris),
but it was a good refresher to see how I could solve it with immutability and functional programming.  The main
programming concepts that I went through.  

 - Tuples
 - Annonymous functions and the `_` symbol
 - Type conversion (char, num, string, etc)

Now I need to focus on getting the scala notebook running on my machine so that I can use it to document the process
and ML solution.  

**Link to work**: [Gist - Chuck Norris](https://gist.github.com/mikekwright/b3ee383bbcd17f4407951e5662a3a6f7)

[Table of Contents](#toc)

----------
<a name="day-2"></a>
### Day 2: June 15, 2018

**Today's Focus**: Scala refresher / environment setup

**Details**:  

Today was spent in 3 different areas.  

1. Getting the scala jupyter notebook running on windows 10
2. Keep refreshing scala skills
 - [Codingame - Horse Racing Duals - E1](https://www.codingame.com/training/easy/horse-racing-duals)  
 - [Codingame - Last Crusade - E1](https://www.codingame.com/training/medium/the-last-crusade-episode-1)
3. Start to look for data sources that will work with my project

**Thoughts:**:  Everytime I work with scala I keep forgetting how powerful
of a language it is, and of course, how easy it is to write _clever_ code
(that is completely unreadable).  But I do really like to focus exclusively
on solving the problems in a functional style when possible.  

**Link to work**: 
- [Gist - Horse Racing Duals](https://gist.github.com/mikekwright/05f112c3ce8ff7dfd8e9e3d64d92f5e1)
- [Gist - Last Crusade](https://gist.github.com/mikekwright/9a31a3ff02aa007d3ee32f3b66cd1566)   

[Table of Contents](#toc)

----------
<a name="day-3"></a>
### Day 3: June 16, 2018

**Today's Focus**: Scala Notebook setup and Breeze install

**Details**: This was a surprisingly difficult task to get working.  I was running into all sorts of problems
with the versions of the scala notebook that I was trying to run.  Some of them not having access to the scala
mechanism for installing 3rd party libraries.  But was able to finally get it working.  

Now I was only able to get the 0.2.0 version working, I want to get the 0.3.x setup and working, so that will
be my next task.  

**Thoughts:**  Might look at getting [Smile](https://github.com/haifengl/smile) installed as well as 
[Breeze](https://github.com/scalanlp/breeze)

**Link to work**: [Sample Notebook output](https://github.com/mikekwright/simple-modeling-experiment/blob/master/notes/Sentence%20Classifier/06-17-2018%20-%20Scala%20Library%20Example.ipynb)

[Table of Contents](#toc)

----------
<a name="day-4"></a>
### Day 4: June 17, 2018

**Today's Focus**: Get a raspberrypi Kubernetes cluster up

**Details**:  Today's task was a little different from what I have been doing, today I focused on getting a 
raspberry pi cluster I had purchased setup to work with Kubernetes.  Here is the structure of the cluster. 

- [4 Raspberrypi Model B+](http://www.newark.com/raspberry-pi/2773729/sbc-arm-cortex-a53-1gb-sdram/dp/49AC7637?src=raspberrypi)
- [4 32GB MicroSD Cards](https://www.amazon.com/gp/product/B06XWN9Q99)
- [Clear Stack for 4 Raspberrypis](https://www.amazon.com/gp/product/B01LVUVVOQ)
- [USB Power Station](https://www.amazon.com/gp/product/B0793MLKJP)
  - [Micro-USB Cords](https://www.amazon.com/gp/product/B077YF2N71)
- [8 Port Gigabit Switch]()
  - [10 pack 1' Cat5e cables](https://www.amazon.com/gp/product/B00HNV8ND0)

I have it setup as follows.  (Setup was completed by using ideas from 
[this article](https://codeghar.wordpress.com/2012/05/02/ubuntu-12-04-ipv4-nat-gateway-and-dhcp-server/) and
[this article](https://raspberrypihq.com/how-to-turn-a-raspberry-pi-into-a-wifi-router/))   

1. One pi as a master pi
  - This pi has `wlan0` setup to connect to router
  - DHCP is installed and serves on `eth0`
2. Three worker pi
  - `wlan0` is disabled
  - `eth0` is served from master pi

I then went on to work with kubeadm... I had to follow the items in 
[this medium article](https://kubecloud.io/setup-a-kubernetes-1-9-0-raspberry-pi-cluster-on-raspbian-using-kubeadm-f8b3b85bc2d1),
however there were a few things that needed to be changed.  

1. In the `init.sh` file you need to change `cgroup_memory=1` to `cgroup_enable=memory` as stated in the comment. 
2. Need to install a specific version of kubeadm (current version as of today did not work).  The instructions are
found at this issue [here](https://gist.github.com/alexellis/fdbc90de7691a1b9edb545c17da2d975#gistcomment-2605323)
but I have also shared them below.    

        Step 1: uninstall kubernetes, follow the below given commands
        $kubeadm reset
        $sudo apt-get purge kubeadm kubectl kubelet kubernetes-cni kube*
        $sudo apt-get autoremove
        $sudo rm -rf ~/.kube

        Step 2: reboot your pi
        $sudo reboot

        Step 3: Install v1.9.7-00, follow the below given commands
        $ curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add - && 
        echo "deb http://apt.kubernetes.io/ kubernetes-xenial main" | sudo tee /etc/apt/sources.list.d/kubernetes.list && 
        sudo apt-get update -q && 
        sudo apt-get install -qy kubelet=1.9.7-00 kubectl=1.9.7-00 kubeadm=1.9.7-00

        Step 4: Initiate your master node
        $sudo kubeadm init --token-ttl=0 --apiserver-advertise-address=192.168.0.100 --ignore-preflight-errors=ALL should work as expected

3. If you forget the token or hash needed you can run this command on the master

        sudo kubeadm token create --print-join-command

4. Make sure to install a pod network (I was trying out [weave](https://www.weave.works/docs/net/latest/kubernetes/kube-addon/))  

**Extra Docs**:
- [Kube init config file](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-init/)  
- [Dashboard Install](https://docs.giantswarm.io/guides/install-kubernetes-dashboard/)
- [Kube-router (use all version)](https://github.com/cloudnativelabs/kube-router/blob/master/docs/kubeadm.md)
- [Kubeadm Create Cluster Doc](https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/#pod-network)

**Thoughts:**  [Fill in or skip]

![Day 1 Image](https://raw.githubusercontent.com/mikekwright/100-days-of-code/master/images/day1_image.png)

**Examples**: [Fill in with some examples if any] 

**Link to work**: [Github](https://github.com/mikekwright/100-days-of-code/)

[Table of Contents](#toc)

----------
<a name="day-5"></a>
### Day 5: June 18, 2018

**Today's Focus**:  Raspberry Pi Model B+ Kub, Breeze Study 

**Details**:  So I know I was supposed to hold off on working on the raspberry pi cluster, but I just wanted
to do more.  Anyways I got a lot farther into the configuration working at this point.  There are a few
other steps that need to be done.  

- First need to setup a different version of the pieces. 
  - Kubectl (kubectl 1.10.4-00)
  - Kubelet (kubelet 1.10.2-00)
  - Kubeadm (kubeadm 1.10.4-00)
  - Docker (docker-ce 17.12.1~ce-0~raspbian)
- Next you can install using the standard init `kubeadm init`
- When you install weave you will need to install a version that is setup to work on B+ (different)
  - `kubectl apply -f "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 | tr -d '\n')&env.WEAVE_NO_FASTDP=1"`
- Finally you can install an arm version of dashboard
  - `kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v1.8.3/src/deploy/recommended/kubernetes-dashboard-arm.yaml`
  - **NOTE** To make this work you need to add cluster permission.. Save the file (dashboard-role) below and apply 
  - `kubectl apply -f dashboard-role.yaml`
- After running `kubectl proxy` on laptop connect to dashboard
  - `http://localhost:8001/api/v1/namespaces/kube-system/services/https:kubernetes-dashboard:/proxy/#!/node?namespace=default`

**dashboard-role.yaml**

        apiVersion: rbac.authorization.k8s.io/v1beta1
        kind: ClusterRole
        metadata:
          name: kube-dashboard
        rules:
        - apiGroups: ["*"]
          resources: ["*"]
          verbs: ["*"]
        ---
        apiVersion: rbac.authorization.k8s.io/v1beta1
        kind: ClusterRoleBinding
        metadata:
          name: rook-operator
          namespace: rook-system
        roleRef:
          apiGroup: rbac.authorization.k8s.io
          kind: ClusterRole
          name: kube-dashboard
        subjects:
        - kind: ServiceAccount
          name: kubernetes-dashboard
          namespace: kube-system 

**Thoughts:**  Man this was quite the endeavor, and while I don't have it all working yet I do feel a lot better
about where I am.  

**Links:**

- [Dashboard Cluster](https://github.com/kubernetes/kubernetes/issues/63854#issuecomment-389146409)
- [Weave for Pi B+](https://github.com/weaveworks/weave/issues/3314#issuecomment-396257270)

[Table of Contents](#toc)


<!---
Entry template

----------
<a name="day-1"></a>
### Day 1: January 1, 2018

**Today's Focus**: [Fill in] 

**Details**:  [Fill in or skip]

 - I worked on a
 - I completed b
 - I learned c

**Thoughts:**  [Fill in or skip]

![Day 1 Image](https://raw.githubusercontent.com/mikekwright/100-days-of-code/master/images/day1_image.png)

**Examples**: [Fill in with some examples if any] 

**Link to work**: [Github](https://github.com/mikekwright/100-days-of-code/)

[Table of Contents](#toc)

--->
