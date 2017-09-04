---
layout: post
title:  "Installing ROS on your workstation"
date:   2015-02-01 13:46:10
answerrostag: "install_ros"
track: [main]
---

We need to install ROS and Ubiquity Robotics packages on both the work station and Magni. There are different distributions of ROS and they are named in alphabetical order from oldest to newest (e.g. Groovy came before Hydro which came before Indigo).

We want to install the long term support, or LTS, distribution called **Kinetic**.

***TIP:** The recently added "Jade" distribution is not LTS.*

## Installing ROS (Workstation and Magni)

For your reference, [The ROS Wiki page](http://wiki.ros.org/kinetic/Installation/Ubuntu) on installing kinetic is excellent. Follow it completely and use all the recommended options such as installing the desktop full version.

***TIP:** If you followed our [Installing Ubuntu tutorial]({{ site.url }}{% post_url 2015-02-01-4%}) you have Ubuntu 16.04.*

***TIP:** All of these commands should be copied and pasted into a terminal. Use ctrl + alt + t to launch a terminal.*

***TIP:** In the ROS documentation for the installation, the bash steps are labeled as “convenient” but not required. However, be sure to do these steps as they make following these articles much easier.*

## Install Magni Packages (Workstation and Magni)

When you install ROS it comes with all the common packages but leaves out lots of stuff some robots won’t need. Obviously, the Magni packages are only for Magni users so we’ll need to install that now.

First, open a terminal and run:

{% highlight sh %}
sudo apt-get update
{% endhighlight %}

When this article was written, the deb format wasn’t available yet so we had to install from the source. Except for some copying and pasting, it’s not more difficult or different.

***UPDATE:** Since writing this, a deb is available but OSRF still recommends installing the source installation while they fix some final bugs (2/11/15).*

Follow the [Magni installation instructions](http://wiki.ros.org/turtlebot/Tutorials/kinetic/Turtlebot%20Installation) by copying every line below “Source Installation” into a terminal.

## Additional Drivers

## Learn more at wiki.ros.org

* [Getting Started with ROS](http://wiki.ros.org/ROS/StartGuide)

