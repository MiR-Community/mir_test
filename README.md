## Overview

This is a custom made site for the Mir Community. The design is heavily inspired by  [StaticMania roxo-hugo design](https://github.com/StaticMania/roxo-hugo)

## Installation

`git clone https://github.com/zaynaib/mir_test.git`

If you have hugo already installed run

`hugo server` to build the site

## Creating Team Member Profile images

To create team member profile images like the ones displayed on the team page make sure the picture is size 250x250 .

Go to static > img > team  and place your picture in the team folder.

Next go to the data folder and edit the team.yml file to include another team member.

## Creating Individual Team Member Pages

Go to content and under the team folder create a hugo bundle. In the bundle create a folder called **images**. Save your photo as **profile.jpg**.

## How to modify the navigation menu

Go into the data folder and modify the menu.yml file. The last item in the yml file will be the pink contact button.

## How to modify links for footer

Go to the config.toml file and modify 

```
[params.footer]

```


## How to modify the about page

Go into the data folder and modify the about.yml file.

## How to modify css

_variables.scss is where all the theme colors are located
_buttons.scss is the css styles for the buttons
_typography.scss  is where the fonts for the theme are located
_navigation.scss is where the navigation styles are located
_team-single.scss is where the location of the layout stay for individual team members are located.

## Features

Bootstrap 4