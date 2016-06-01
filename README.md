# ndevr-wraith
Visual screenshot diff tool based on [BBC Wraith](https://github.com/BBC-News/wraith).

## Dependencies
 - Node@v4.2.1
 - Ruby@2.1.1
 - Imagemagik@0.1.3
 - Phantomjs@2.1.1
 - Wriath@3.2.1
 
### Installing Dependencies
All packages need to be available system-wide. You may use whichever method you wish to install
the packages at their respective versions.

Here is a recommended way to manage the dependencies though:

#### Node
Use [NVM](https://github.com/creationix/nvm) - this will use the version in the .nvmrc file.

#### Ruby
Use [RBENV](https://github.com/rbenv/rbenv) - this will use the version in the .ruby-version file.

#### Imagemagik and Phantomjs
Install globally with NPM

```npm install -g imagemagik@0.1.3```   

```npm install -g phantomjs@2.1.1```

#### Wraith
This is a Ruby gem

```gem install wraith -v 3.2.0```

### Running the tool
Wraith will run agains the requested configuration file. Feel free to copy ndevr.yaml to use for local
testing.  

```cd to [project_root]```  

```wraith configs/ndevr.yaml```

#### View the results
An html page will be created in the configured output directory "shots" alling with the screenshots.

location: [project_root]/shots/gallery.html


