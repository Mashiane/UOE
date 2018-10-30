# UOE

What is UOE?

UOE, pronounced 'UWE' is a B4J (Basic 4 Java) library that anyone can use to create Material Design websites easily. This library has been written from the ground up using version 1.0.0 of the Materialize web framework. The intentions with UOE is to enable anyone to create websites without having to write any HTML code by using Visual Basic like syntax. UOE has adopted the Material Design framework due to its ease of use and large adoption amongst developers. You might want to visit our Frequently Asked Questions for more details about UOE. If you want to hear this page being read, go on and select the microphone (bottom right) to have your device read it.

To demonstrate let's see an example below of how a material chip is being created with UOE. To the left is the code to create the chip and the right the resulting chip. That is how one creates material based websites using the UOE library. Please note the comments on the code.

'create a chip component variable

Dim chip As UOEChip

'initialize the chip for use, give it id of 'chip1', image to be kenny.png, with white text and a blue background

chip.Initialize(Page,"chip1","Kenny","images/kenny.png","Kenny","white.blue")

'add the chip at row 4 column 2 of the page grid

Page.Content.AddChip(4,2,chip)

# Let us explain the code...

Each component in UOE is created using an UOEComponent specifying the name. In most internal components, you will get a reference to the Materialize webiste detailing how that component is defined using HTML syntax. UOE generates the html code for your site using the components you define, You can then link your JS, CSS and any other java-script related framework you want. Each component in Materialize sits inside a responsive grid container. This is a matrix with rows and columns. For more details on the container, you can see here. Basically, you dimension a variable using the component name, initialize it, specify other properties for the component and then add it to the page content. The page content is an instance of UOEContainer.

# What do you need to get started?

Basically, not much. You need B4J from Anywhere Software, a 100% free development tool, to develop desktop, server and IOT solutions. With B4J you can easily create desktop applications (UI), console programs (non-UI) and server solutions. The compiled apps can run on Windows, Mac, Linux and ARM boards (such as Raspberry Pi).

You will need a web browser. Again, you can use your favourate browser, but we suggest you use either Google Chrome or Mozilla Firefox, due to them having excellent developer tools. These can help when your website does not work as expected. You will also need a webserver to host your HTML pages and javascript code. It is possible to run the code by just opening the code file directly from a browser though. We use XAMPP, which is super easy to configure, and available for Windows and Mac. XAMPP provides an installer to set up a local Apache web server, as well as other components you might find useful. We will however not delve much into how to set XAMPP up here.

# How is this website organized?

This website attempts to explain how the UOE B4J library works. Selecting the hamburger menu (top left), provides one with options of the various Materialize components. This menu is organized in a similar fashion like the Materialize website, however in our own fashion. For each component, you get the purpose of the component, the reference to the Materialize website so that you can see how that component is originally defined. You also get a section that indicates how the component is created using the UOE library, including some source code. For each component you also get a property list and a methods list on how everything fits together.

You will better understand how the UOE library works after you have learned about the Materialize framework. Click here to learn more about Materialize.

# The source code...

This website is build using the UOE library and B4J. In the Downloads section (on the sidebar) are links for everything you will need to get started, like B4J, the UOE Library, B4J UOE Skeleton Project etc, but before that, let's continue with the introduction.
