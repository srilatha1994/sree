---
title: "Setting Up minikube GUI"
linkTitle: "Setting Up minikube GUI"
weight: 1
date: 2022-02-25
---

## Overview

- This guide will show you how to setup the minikube GUI
- **WARNING!** This GUI is a prototype and therefore may be unstable or contain bugs. Please use at your own risk, we are not responsible for damages.
- If you experience any bugs or have suggestions to improve the GUI feel free to create a [GitHub Issue](https://github.com/kubernetes-sigs/minikube-gui/issues/new).
- Please note that the SSH functionality currently only works on Linux.

## Before You Begin

- minikube setup and available on your path, follow the [Getting Start doc]({{< ref "/docs/start" >}}) if not already done

## Steps

{{% tabs %}}
{{% mactab %}}
1. [Download minikube-gui](https://github.com/kubernetes-sigs/minikube-gui/releases/latest/download/minikube-gui-macos.dmg)

2. Open the dmg and copy minikube-gui to your Applications folder

3. **Important!** On first time use only, right click minikube-gui and select `Open`, you will see the following, select `Open`

![Mac unverified developer](/images/gui/mac.png)

If you don't see the `Open` option you likely left clicked minikube-gui, make sure to right click and select `Open` (first time only)
{{% /mactab %}}
{{% windowstab %}}
1. [Download minikube-gui](https://github.com/kubernetes-sigs/minikube-gui/releases/latest/download/minikube-gui-windows.zip)

2. Unzip and run minikube-gui.exe

3. If you see the following, click `More info` and then `Run anyway`

![Windows unreconized app](/images/gui/windows.png)
{{% /windowstab %}}
{{% linuxtab %}}
1. [Download minikube-gui](https://github.com/kubernetes-sigs/minikube-gui/releases/latest/download/minikube-gui-linux.tar.gz)

2. Untar and run minikube-gui
{{% /linuxtab %}}
{{% /tabs %}}

