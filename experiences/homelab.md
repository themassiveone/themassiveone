# Homelab Experience

My homelabbing experience has been [erratic](https://www.google.com/search?client=firefox-b-d&q=erratic) to say the least. As I researched certain topics my interest repeatedly shifted spontaneously throughout the years.

## Networking (section incomplete)

##### DNS

##### DHCP

##### Topology

## Virtualization (section incomplete)

Throughout the years, I gathered alot of experience with many different kinds of virtualization techniques.

##### Hosted Hyper-V

As i started my Homelabbing Experience using a prebuild Fujitsu Server, that had Windows Server 2012 R2 preinstalled, Hyper-V Virtualization was not far fetched. Initially I tried to create virtual mashines in order to encapsulate certain applications for security reasons or to flexibily try out new kinds of operating systems like ubuntu desktop.

##### Unraid virtualization

Unraid deemed to be a very flexible virtualization utility, as vms can be created quickly running any os. Additionally certain devices like pci-e cards, usb ports or storage controllers can be passed through to a vm easily. Running KVM based docker containers has been a great option for testing out backend applications effortlessly without the need to read documentations for days. This allows quick evaluations before starting time consuming hosting plans.

I initially bought an unraid license as I required its flexibility regarding storage management eventough I did not know of its virtualization support at the time.

##### Docker

At some point in time I became very interested in container technology as docker became a big topic on YouTube. I researched the topic and watched tutorials on how it actually works.

As I am a big advocate for Single Page Applications (SPA) in Frontends and also very familiar with reusability of code, Docker has fascinated me deeply. Reusing the operating system layer of a bare metal mashine accross multiple virtualized containers felt like such an inovative idea at that time. It also being very lightweight made it sensible to only add nessessary application depencies to a single container.

I very much enjoy optimizing container images to only run their respective software. As organizing multiple docker containers became unreasonable, I reached out to solutions like docker compose and later kubernetes to manage entire hosting environments.

##### Docker Compose

##### Kubernetes orchastration

My Kubernetes experience emerged out of a favor for docker containers. This happened at a time where I also become very passionate with a lot of other DevOps Technologies. Therefore i will mention Kubernetes in the respective DevOps section.

##### Proxmox

As proxmox was the first bare metal virtualization experience Ive ever had, it remains my entry gateway into the world of professional virtualization.

Initially I hosted a PVE node virtually on my Unraid Server, as this seemed to be a effortless way to test out Proxmoxes capabilities. My requirements for a hypervisor at the time were:

- Support for REST communication
- Available Terraform provider
- priceless

##### VMWare ESXI standalone

##### VMWare VSphere cluster

## DevOps (section incomplete)

##### Kubernetes

##### CICD

##### Terraform

## Bare Metal Experience

I received my first server from a family friend as a gift. Its a **Fujitsu Primergy Tower** with the following specs:

```
CPU: Intel® Xeon® CPU E3-1226 v3
Mainboard: FUJITSU D3219-A1
Storage: 2x Seagate ST1000DM003
```

Additionally i received my families old **FritzBox 7490** to use freely. Unfortunately its operating system is irreplaceable, so it cannot be used as a router or layer3 switch in a professional scense. Eventhough this is the case, it can still be used a WIFI Access Point.

At one point in time, I decided to purshase a **Raspi** as a utility server or IOT device. I never realy regreted this deciscion.

```
Device: Rasberry PI Model 4b
Memory: 4GB
Storage: San Disk 32gb microSD card
```

While I was all in for upgrading my gaming rig at some other point in time, I was left with spare hardware parts, which I deemed to be worthwhile the little effort, to assembly **a secondary tower server** out of them.

```
Mainboard: Asus H81M-PLUS
CPU: Intel® Core™ i5-4590
```

Amongst many other things, I also possess 2 cheap Ethernet switches and two 1-Port and a 2-Port Gigabit NIC, which i make use of frequently.

I will also add my own **gaming rig** in here as i (mis)used it as a VM-Host for quite some time aswell.

```
Mainboard: Asus X570F Gaming
CPU: Ryzon 3700x
RAM: 32gb G.Skill Aegis DDR4-3200
GPU: RTX 2070 SUPER
lighting: sick
```

![lighting image](/media/lighting.jpeg)


