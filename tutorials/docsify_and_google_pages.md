# docsify

## Install docsify-cli
 We need this step because we want to initialize and preview our work locally.

> Make sure that we have Nodejsy. Download and install node.js from this link: https://nodejs.org/en/

> Verify if the instalation was fine by cheking the version number in a console. So open a CMD and type:
```bash
node -v
npm -v
```

> Next, you need to install the docsify-cli:

```bash
npm i docsify-cli -g
```
## Iniliatilze the subdirectory
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

> Now, if everithing works fine, you should be able to see the results in a browser at localhost:3000


## Push your code on Github
[!] TODO 

## Setup your Google Pages
[!] TODO