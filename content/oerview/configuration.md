---
title: Azure ARC Quick Start
weight: -10
---

Azure Arc enabled servers enables you to manage and govern your Windows and Linux machines hosted across on-premises, edge, and multicloud environments. In this quickstart, you'll deploy and configure the Connected Machine agent on your Windows or Linux machine hosted outside of Azure for management by Arc enabled servers.

## Prerequisites
1. If you don't have an Azure subscription, create a free account before you begin.

2. Deploying the Arc enabled servers Hybrid Connected Machine agent requires that you have administrator permissions on the machine to install and configure the agent. On Linux, by using the root account, and on Windows, with an account that is a member of the Local Administrators group.

3. Before you get started, be sure to review the agent prerequisites and verify the following:

  1. Your target machine is running a supported operating system.

  2. Your account is granted assignment to the required Azure roles.

  3. If the machine connects through a firewall or proxy server to communicate over the Internet, make sure the URLs listed are not blocked.

  4. Azure Arc enabled servers supports only the regions specified here.

## Use Azure Cloud Shell
Azure hosts Azure Cloud Shell, an interactive shell environment that you can use through your browser. You can use either Bash or PowerShell with Cloud Shell to work with Azure services. You can use the Cloud Shell preinstalled commands to run the code in this article without having to install anything on your local environment.
To run the code in this article in Azure Cloud Shell:

  1. Start Cloud Shell.

  2. Select the Copy button on a code block to copy the code.

  3. Paste the code into the Cloud Shell session by selecting Ctrl+Shift+V on Windows and Linux or by selecting Cmd+Shift+V on macOS.

  4. Select Enter to run the code.