# CoW Swap Banner

This repository contains the text that is shown as an announcement/warning toast on the CoW Swap UI.

![image](https://user-images.githubusercontent.com/1200333/236169373-07b08e08-feff-4cd9-bf14-2113770ce146.png)

Announcements are network (Mainnet, Goerli, Gnosis Chain) and environment (barn, prod) specific:

To change the text for all environments (barn & production), edit the file `announcements-{network_id}` in the top level folder and commit your change into the main branch.

To change the text only for production, edit and commit the file `announcements-{network_id}` in the top `/production` folder.
Respectively change `/barn/announcements-{network_id}` to only set a text in barn.

**If there is a text in both the top level file as well as in the environment specific subfolder file for a given network, the top level folders' text takes precedence.**

### Network IDs

- 1 = Mainnet
- 5 = Goerli
- 100 = Gnosis Chain
