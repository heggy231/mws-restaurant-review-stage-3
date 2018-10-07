# Local Development API Server
## Usage
I am a server for restaurant review stage 2.  Please don't delete me but run me anytime you are 
running restaurant review stage 2.

  * Run the following code your terminal:    
    ###### Install project dependencies
    ```Install project dependencies [don't copy the # hashtag, it is just the indication that this is a code you need to put inside of terminal, run this for the first time only]
    # npm i
    ```
    ###### Install Sails.js globally (run this for the first time only)
    ```Install sails global
    # npm i sails -g
    ```
    ###### Start the server (Do not include #!!)
    ```Start server
    # node server // !!! Do not include #!!!
    ```
    ### You should now have access to your API server environment
    debug: Environment : development
    debug: Port        : 1337

  * We have your data running at http://localhost:1337/restaurants 
  * Check it in your browser
    http://localhost:1337/restaurants 


#### What is this server doing?
This is Node.js and Sails.js servers providing restaurant info to [Restaurant Review Web App](https://github.com/heggy231/mws-restaurant-review)
#### Get Restaurants
```
curl "http://localhost:1337/restaurants"
```
#### Get Restaurants by id
````
curl "http://localhost:1337/restaurants/{3}"
````

## Architecture
Local server
- Node.js
- Sails.js

## Contributors

- [Heggy Castaneda - Frontend engineer](mailto:heggyy@gmail.com)
- [Brandy Lee Camacho - Technical Project Manager](mailto:brandy.camacho@udacity.com)
- [David Harris - Web Services Lead](mailto:david.harris@udacity.com)
- [Omar Albeik - Frontend engineer](mailto:omaralbeik@gmail.com)

## Getting Started

### Development local API Server
_Location of server = /server_
Server depends on [node.js LTS Version: v6.11.2 ](https://nodejs.org/en/download/), [npm](https://www.npmjs.com/get-npm), and [sails.js](http://sailsjs.com/)
Please make sure you have these installed before proceeding forward.

Great, you are ready to proceed forward; awesome!

Let's start with running commands in your terminal, known as command line interface (CLI)

###### Install project dependancies
```Install project dependancies
# npm i
```
###### Install Sails.js globally
```Install sails global
# npm i sails -g
```
###### Start the server
```Start server
# node server
```
### You should now have access to your API server environment
debug: Environment : development
debug: Port        : 1337


If you find a bug in the source code or a mistake in the documentation, you can help us by
submitting an issue to our [Waffle Dashboard](https://waffle.io/udacity/mwnd-issues). Even better you can submit a Pull Request with a fix :)
