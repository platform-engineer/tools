# tools
tools.platformenigneer.net


[Top 10 uncommon DevOps tools you should know  Top of the OPS](https://medium.com/leapp-cloud/top-10-uncommon-devops-tools-you-should-know-91dadde9777e)

# Top 10 uncommon DevOps tools you should know

Hello everyone! You clicked here to take a laugh at yet another boring list, right? I’ll try to surprise you with a list of unique tools that you probably still don’t know! I know you already know about Git, Terraform, Jenkins, and so on, so let’s focus on the **tiny pearls** you can find out there! I’ve chosen only open-source tools to spread some love; if you find anything helpful, you can contribute back.

# 1\. Chaostoolkit

As a DevOps (and software engineer), I find chaos engineering one of the most relevant and thrilling topics to study right now. [Chaostoolkit](http://chaostoolkit.org/) it’s a perfect way to introduce into this world through a straightforward and flexible command-line tool and a way to define experiments with declarative files that you can version.

## Insomnia

I bet you all know Postman for API design, right? I prefer [Insomnia.rest](http://insomnia.rest/) since they’ve taken the extra mile to open-source the complete application and integrations through their [plugin hub](https://insomnia.rest/plugins). I know it’s a bit more popular nowadays, but I started using this when there were just a few thousand stars, and it got better and better over the years. I think the trend will keep up.

## Leapp

[Leapp](https://github.com/Noovolari/leapp) is my go-to tool for accessing my cloud accounts. I was fed up with manually managing local development and operations credentials, so I automated everything most securely. I can’t count how much time it saved me over the years.

It integrates with nearly any development tool (Terraform, CDK, etc.) and some excellent additions like connecting directly to SSM. Like Insomnia, it’s completely open-source, and the repository and slack channel are very active if you want to come around. Also, the tool is getting better at each release, and there is an excellent [roadmap](https://roadmap.leapp.cloud/tabs/4-in-progress) to keep up with what’s new.

![](https://miro.medium.com/max/1400/0*2c4eQfzVmBPBTEHU)

## Gitea

If you don’t live under a rock, you already know about mainstream git repository software like GitHub and GitLab. But what if a highly lightweight, community-driven, and self-hosted alternative exists? That’s [gitea.io](http://gitea.io/). It’s not as full-fledged as its counterparts, but it’s highly promising and painless to install and use and has a very active and welcoming community.

## Hubot

[Hubot](https://hubot.github.com/) is kind of old (at least in software terms!), but I’m amazed at how few people know about the ChatOps model. From 10000 thousand feet perspective, it’s just automation through your go-to chat software (discord, slack, rocketchat, mattermost, etc.), and Hubot paved the way to other similar tools. Maybe it’s less relevant today, but I find an interesting concept nonetheless (I love automation in any form it can take) that can solve a few issues, especially for less technical people.

## Mkdocs-material

I love markdown, and MkDocs is my go-to tool for writing documentation, but it’s pretty bare. [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) is a template that you can put mkdocs on… except it packs a whole world of additional features: versioning your documentation, a native cookie consent solution, rich search previews, and a truckload of other things… seriously give the guy 10$ a month to get supporters-only features, and you’ll get the only documentation tool you will ever need. (for instance, the [AWS Copilot CLI](https://aws.github.io/copilot-cli/) docs were written with this, see for yourself, that’s amazing).

![](https://miro.medium.com/max/1400/0*9tslhhA7-HX76Eyx)

## Podman

I’ve actively used Docker for almost all my container needs, but I’m always happy to take a look at new and emerging technologies. What got me into Podman was the daemonless architectural pattern, and nowadays, I like where the project is going. However, it’s still rough around the edges (especially the docs). Still, when I tried it out the first time, I was able to drop it in the middle of my Dockerfile, and everything just worked.

## Sshuttle

[Sshuttle](https://github.com/sshuttle/sshuttle) is an excellent tool that acts as a “poor man” VPN, allowing you to create a VPN connection from your machine to any remote server you can connect to via ssh. The exciting part is that it is not precisely a VPN and not exactly port forwarding. Internally it assembles the TCP stream locally, multiplexes it statefully over an ssh session, and disassembles it back into packets at the other end to achieve data-over-TCP, which is safe. Useful if your VPN breaks down.


## Infracost

If you’re a Terraform fan, you’ll love this one. What if I tell you you can couple your infrastructure as code with bill forecasting? Sounds fantastic, huh? That’s what [infracost.io](http://infracost.io/) is all about: it will scan through your Terraform files when you commit some changes to git and estimate the resulting billing of your changes! Pretty handy to have before getting unpleasant surprises.

![](https://miro.medium.com/max/1400/0*0QZJp_5oyoJsip3Z)


## Checkov

Ok, here’s the final pearl. [Checkov.io](http://checkov.io/) is a static code analysis tool for checking infrastructure as code misconfiguration. I cannot express how much this one can help find and fix the most basic (and advanced) security problems in your cloud infrastructure, and it comes with support to a whole world of different IaC tools. I also love it because you can run it from the command line.

## [Lightweight certified Kubernetes with Rancher](https://www.rancher.com/products/k3s)

Kubernetes with Rancher

### K3s is an official CNCF sandbox project that delivers a lightweight yet powerful certified Kubernetes distribution designed for production workloads across resource-restrained, remote locations or on IoT devices. When used with Rancher, K3s is simple to install, lightweight yet high availability Kubernetes distribution that can be easily managed within the Rancher orchestration platform.


## Lightweight Kubernetes [K3s](https://k3s.io/)


> 
> #### The certified Kubernetes distribution built for IoT & Edge computing



## [Helm  Quickstart Guide](https://helm.sh/docs/intro/quickstart/)

> This guide covers how you can quickly get started using Helm.

+ [Helm | K3s](https://docs.k3s.io/helm)



## GraalVM

+ [GraalVM](https://www.graalvm.org/latest/docs/)


+ [Get Started with GraalVM](https://www.graalvm.org/22.3/docs/getting-started/)

> # Get Started with GraalVM
> 
> Get started with GraalVM – is a high-performance JDK designed to accelerate Java application performance while consuming fewer resources. GraalVM offers two ways to run Java applications: on the HotSpot JVM with Graal just-in-time (JIT) compiler or as an ahead-of-time (AOT) compiled native executable. Besides Java, it provides runtimes for JavaScript, Ruby, Python, and a number of other popular languages. GraalVM’s polyglot capabilities make it possible to mix programming languages in a single application while eliminating any foreign language call costs.
> 
> Here you will find information about installing GraalVM Community Edition, running basic applications with it, and adding support for accompanying features. Further, you will learn about the polyglot capabilities of GraalVM and see how to build platform-specific native executables of Java applications.
> 


[Java on Truffle](https://www.graalvm.org/22.3/reference-manual/java-on-truffle/)

> # Java on Truffle
> 
> Using GraalVM, you can run Java applications normally [on the JVM](https://www.graalvm.org/22.3/reference-manual/java/), in [Native Image](https://www.graalvm.org/22.3/reference-manual/native-image/), and now on Truffle. Java on Truffle is an implementation of the Java Virtual Machine Specification, [Java SE 8](https://docs.oracle.com/javase/specs/jvms/se8/html/index.html) and [Java SE 11](https://docs.oracle.com/javase/specs/jvms/se11/html/index.html), built upon GraalVM as a Truffle interpreter. It is a minified Java VM that includes all core components of a VM, implements the same API as the Java Runtime Environment library (libjvm.so), and reuses all JARs and native libraries from GraalVM. See the [Implementation Details](https://www.graalvm.org/22.3/reference-manual/java-on-truffle/implementation/) for more information. The project name behind this implementation is “Espresso”. Its open source version is available on [GitHub](https://github.com/oracle/graal/tree/master/espresso).
> 
> The Java on Truffle execution mode runs Java via a Java bytecode interpreter, implemented with the [Truffle framework](https://www.graalvm.org/22.3/graalvm-as-a-platform/language-implementation-framework/) – an open-source library for writing interpreters for programming languages. Now Java can be executed by the same principle as other languages in the GraalVM ecosystem (JavaScript, Ruby, Python, R), directly interoperate with those languages, and pass data back and forth in the same memory space. Besides complete language interoperability, with Java on Truffle you can:





---

+ [edit](https://github.com/platform-engineer/tools/edit/main/README.md)

