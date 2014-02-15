---
layout: default
title: Assignment 1
permalink: as1/index.html
---

These are images from Assignment 1.

<style>
    #content > p > img {
        width: 450px;
        height: 450px;
        vertical-align: middle;
        -webkit-box-reflect: below 2px -webkit-linear-gradient(top,
                transparent, transparent .8, rgba(255,255,255,0.20));
        -webkit-border-radius: 6px;
           -moz-border-radius: 6px;
            -ms-border-radius: 6px;
             -o-border-radius: 6px;
                border-radius: 6px;
        padding: 4px 4px 2px 4px;
        margin: 1em 1em .1em 1em;
        -webkit-box-shadow: none;
           -moz-box-shadow: 4px;
            -ms-box-shadow: 4px;
             -o-box-shadow: 4px;
    }
</style>

All these commands used `-file 500` to render the images.

###### Image 1
• An image showing diffuse only shading from a single light source
![1.png](1.png)
`./as1 -pl 1000 1000 1000 .8 .4 .4 -kd 1 0 2 `

###### Image 2
• An image showing specular only shading from a single directional light source
![2.png](2.png)
`./as1 -dl 10 10 10 .8 .4 .4 -ks 1 .2 1 -sp 4 -ka .4 .1 .4`

###### Image 3
• An image showing specular only shading from a single point light source
![3.png](3.png)
`./as1 -pl 80 80 90 3.9 .4 .4 -ks 1 .2 1 -sp 1 -ka .4 .2 .4`

###### Image 4
• An image showing combined specular and diffuse shading
![4.png](4.png)
`./as1 -pl 200 200 200 .6 .6 .6 -kd 1 1 0 -ka 0 1 1 -ks .8 .6 .8 -sp 98`

###### Image 5
• An image with multiple light sources
![5.png](5.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4`

***

#### Random And Fun Images!
Also, check out [big/](big/) for some REALLY big files. Like 500 Megapixels! :)

_These were all rendered from file 5, simply for comparison._

![c2.png](c2.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 2`

![c3.png](c3.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 3`

![c4.png](c4.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 4`

![c5.png](c5.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 5`

![c6.png](c6.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 6`

![c7.png](c7.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 7`

![c8.png](c8.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 8`

![c9.png](c9.png)
`./as1 -pl 200 200 200 .4 .4 .4 -dl 200 200 200 .4 .4 .4 -kd .2 .6 .2 -ka 0 .3 .6 -ks .7 .6 .9 -sp 200 -pl 1500 100 100 .2 .3 .4 -dl 100 1500 100 .2 .3 .4 -file 500 -circles 9`


Buggy File (Just for fun!)
![buggy.png](buggy.png)

***
***
