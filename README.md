What is this?
=============

Buttons and Scissors is a puzzle game for the Sugar desktop.

How to use?
===========

Buttons and Scissors is part of the Sugar desktop.  Please refer to;

* [How to Get Sugar on sugarlabs.org](https://sugarlabs.org/),
* [How to use Sugar](https://help.sugarlabs.org/),
* [Download Buttons and Scissors using Browse](https://activities.sugarlabs.org/), search for `Buttons and Scissors`, then download, and;
* Refer the 'How to play' section inside the activity

How to upgrade?
===============

On Sugar desktop systems;
* use [My Settings](https://help.sugarlabs.org/en/my_settings.html), [Software Update](https://help.sugarlabs.org/en/my_settings.html#software-update), or;
* use Browse to open [activities.sugarlabs.org](https://activities.sugarlabs.org/), search for `Buttons and Scissors`, then download.

How to run?
=================

Buttons and Scissors depends on Python, PyGTK and PyGame.

Buttons and Scissors is started by [Sugar](https://github.com/sugarlabs/sugar).

Buttons and Scissors is not packaged by Debian and Ubuntu distributions.  
On Ubuntu systems these required dependencies (`python-gtk2-dev` and
`python-pygame`) need to be manually installed.


**Running outside Sugar**


- Install the dependencies - 

On Ubuntu-
```
sudo apt install python-gtk2-dev python-pygame
```

- Clone the repo and run-
```
git clone https://github.com/sugarlabs/buttons-and-scissors-activity.git
cd buttons-and-scissors-activity
python main.py
```

**Running inside Sugar**

- Open Terminal activity and change to the Buttons and Scissors activity directory
```
cd activities\ButtonsandScissors.activity
```
- To run
```
sugar-activity .
```
