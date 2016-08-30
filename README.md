# super-awesome-txt-classifier

[![Join the chat at https://gitter.im/super-awesome-txt-classifier/Lobby](https://badges.gitter.im/super-awesome-txt-classifier/Lobby.svg)](https://gitter.im/super-awesome-txt-classifier/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Build Status](https://travis-ci.org/snakes-in-the-box/super-awesome-txt-classifier.svg?branch=master)](https://travis-ci.org/snakes-in-the-box/super-awesome-txt-classifier)  

#Usage

####Build for spark
```sbt assembly```
####Run in local machine
```./spark-submit --class "org.snakesinthebox.preprocessing.Main" --master local[4] <path to jar> --files <path to config>```
