# Project2

This project is a data visualization for the HPCC servers at Texas Tech.

Website Link:

The left portion of the webpage shows all the different racks in the server. Within each box there is a summary for each rack giving 
the total number of hosts, the totla number of "ok" hosts, the total number of "warning" hosts, and the total number of "critical" hosts.
These racks are also color coordinated. If all the hosts in that rack are ok then the color is green. If one or more hosts are in a
warning state, but none are critical then the color is yellow. Lastly, if any host is critical then the color is red.

Hovering the mouse over any of these racks updates the chart in the center with the correct hosts. If any hosts are in a warning or
critical state then here you can see which hosts are the problem specifically. Similar to the racks you can hover the mouse over these 
and it produces the data for that specific host and displays it on the left.

Each host as 14 different services that are being monitored. Some of which include Fan Health, Inlet Temperature, CPU Temperature, Memory
Health, ect.. All of these services get outputed on the left side of the screen in the same color coordination as the previous two stages.
This section allows the user to see specifically what is wrong with the hosts.

Also at the bottom of the screen there is an overall summary for all the hosts, giving the total number of hosts, and how many are "ok"
in a "warning" and in "critical" states.

![alt text](https://github.com/BradenLee/Project2/blob/master/p2LeeAli.gif)
