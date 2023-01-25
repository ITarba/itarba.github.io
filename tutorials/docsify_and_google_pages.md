<button name=button_details onclick="myFunction()">Show details</button>

# docsify

## Install docsify-cli
 We need this step because we want to run a server on localhost with live-reload. This will be very helpfull in the future because we can see the changes on the fly.
> More details about docsify-cli are here: https://www.npmjs.com/package/docsify-cli

First thing first, make sure that we have Node.js on our local machine. So, download and install Node.js from this link: https://nodejs.org/en/

<img src="images/tutorials/docsify_google_pages/nodejs.png" name="details" style="height: 200px; width:600px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs2.png" name="details" style="height: 200px; width:200px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs3.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs4.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs5.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs6.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs7.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs8.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs9.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs10.png" name="details" style="height: 200px; width:300px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs11.png" name="details" style="height: 250px; width:500px; display: none; margin-left: auto; margin-right: auto;display: none; "/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

<img src="images/tutorials/docsify_google_pages/nodejs12.png" name="details" style="height: 250px; width:500px; display: none; margin-left: auto; margin-right: auto; display: none;"/>
<figcaption name="details" style=" display: none; margin-left: auto; margin-right: auto; width: 50%;display: none;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

After the Node.js instalation, verify if everithing went well by checking the version number in a console. So open a CMD and type:
```bash
node -v
npm -v
```
<img src="images/tutorials/docsify_google_pages/check1.png" alt="MarineGEO" style="height: 100px; width:200px; display: none; margin-left: auto; margin-right: auto; "/>
<figcaption style=" display: none; margin-left: auto; margin-right: auto; width: 50%;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

> Next, you need to install the docsify-cli:

```bash
npm i docsify-cli -g
```
<img src="images/tutorials/docsify_google_pages/install_cli.png" alt="MarineGEO" style="height: 300px; width:600px; display: none; margin-left: auto; margin-right: auto; "/>
<figcaption style=" display: none; margin-left: auto; margin-right: auto; width: 50%;">Fig.1 - Trulli, Puglia, Italy.</figcaption>

## Initialize the subdirectory
For each new project you need to initialize a new subdirectory.

> Write the following commands to create a new subdirectory
```bash
cd path/to/your/folder
docsify init ./docs
```
> The 'docs' folder will be now initialized and will contain 3 files: 
<ul>
	<li> index.html</li>
	<li> README.md </li>  
	<li> .nojekyll </li>
</ul>

> mode details are avaialble here: https://www.youtube.com/watch?v=TV88lp7egMw 


## Run your local server 

> Open a cmd in a file location where is the root folder of the docsify documentation. In our case the path is D:\root\files\docs\\... and the console will be opened in the \files to directly access the \docs

> Run localhost server using this command
```bash
docsify serve docs
```

> Now, if everithing works fine, you should be able to see the results in a browser at localhost:port


## Push your code on Github
[!] TODO 

## Setup your Google Pages
[!] TODO