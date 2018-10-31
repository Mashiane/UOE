# UOE

**What is UOE?**

UOE, pronounced 'UWE' is a B4J (Basic 4 Java) library that anyone can use to create Material Design websites easily. This library has been written from the ground up using version 1.0.0 of the [Materialize](https://materializecss.com/) web framework. The intentions with UOE is to enable anyone to create websites without having to write any HTML code by using Visual Basic like syntax. UOE has adopted the Material Design framework due to its ease of use and large adoption amongst developers. You might want to visit our [Frequently Asked Questions](http://www.mbangas.com/uoe/faq.html) for more details about UOE. If you want to hear this page being read, go on and select the microphone (bottom right) to have your device read it.

To demonstrate let's see an example below of how a material chip is being created with UOE. To the left is the code to create the chip and the right the resulting chip. That is how one creates material based websites using the UOE library. Please note the comments on the code.

![Example Code](http://www.mbangas.com/uoe/images/examplechip.png)


# Let us explain the code...

Each component in UOE is created using an UOEComponent specifying the name. In most internal components, you will get a reference to the Materialize webiste detailing how that component is defined using HTML syntax. UOE generates the html code for your site using the components you define, You can then link your JS, CSS and any other java-script related framework you want. Each component in Materialize sits inside a responsive grid container. This is a matrix with rows and columns. For more details on the container, you can see here. Basically, you dimension a variable using the component name, initialize it, specify other properties for the component and then add it to the page content. The page content is an instance of UOEContainer.

# What do you need to get started?

Basically, not much. You need B4J from Anywhere Software, a 100% free development tool, to develop desktop, server and IOT solutions. With B4J you can easily create desktop applications (UI), console programs (non-UI) and server solutions. The compiled apps can run on Windows, Mac, Linux and ARM boards (such as Raspberry Pi).

You will need a web browser. Again, you can use your favourate browser, but we suggest you use either Google Chrome or Mozilla Firefox, due to them having excellent developer tools. These can help when your website does not work as expected. You will also need a webserver to host your HTML pages and javascript code. It is possible to run the code by just opening the code file directly from a browser though. We use XAMPP, which is super easy to configure, and available for Windows and Mac. XAMPP provides an installer to set up a local Apache web server, as well as other components you might find useful. We will however not delve much into how to set XAMPP up here.

# How is the UOE website organized?

This website attempts to explain how the UOE B4J library works. Selecting the hamburger menu (top left), provides one with options of the various Materialize components. This menu is organized in a similar fashion like the Materialize website, however in our own fashion. For each component, you get the purpose of the component, the reference to the Materialize website so that you can see how that component is originally defined. You also get a section that indicates how the component is created using the UOE library, including some source code. For each component you also get a property list and a methods list on how everything fits together.

You will better understand how the UOE library works after you have learned about the Materialize framework. Click here to learn more about Materialize.

# The source code...

The UOE website is build using the UOE library and B4J. In the Downloads section (on the sidebar) are links for everything you will need to get started, like B4J, the UOE Library, B4J UOE Skeleton Project etc, but before that, let's continue with the introduction.

# Set Up Development Enviroment

1. Create this folder structure C:\MyApps\B4J\Shared
2. Create this folder structure C:\MyApps\B4J\Libraries
3. Download and install [B4J](https://www.idevaffiliate.com/33168/74.html) (Products Menu) from Anywhere Software and install it
4. If you didn't do so, download and install Java JDK 8, see the B4J page for Installation instructions.
5. Download the [UOE Library](https://www.dropbox.com/s/cg18gc4kl6320pv/UOE.zip?dl=0)
6. Extract the contents of the UOE zip file to C:\MyApps\B4J\Libraries
7. Download and install [XAMPP](https://www.apachefriends.org/index.html%3Cbr/%3E) (optional)
8. Download [B4J 'Hello World' UOE Library Project](https://www.dropbox.com/s/mrwor5g3fby1g0m/MyNewUOE.zip?dl=0)
9. Extract the contents of the project to C:\MyApps\B4J
10. Start B4J development tool
11. Click Tools > Configure Paths and update the respective paths and save (see below)

![Configure Paths](http://www.mbangas.com/uoe/images/configurepaths.png)

12. Close the B4J IDE
13. Start XAMPP Webserver
13. Double click the UOE1.b4j file under C:\MyApps\B4J, this will open the B4J IDE
14. Run the project. It should compile and open your default web browser with the project

Congratulations.

You can then continue to explore the UOE website on how the other components are created inside pages.

https://www.patreon.com/join/mashiane
