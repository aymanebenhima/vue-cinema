# Vue.js Cinema

#### Pre-installation

- Ensure [Node.js  >=5.10](https://nodejs.org/en/download/), [NPM](https://docs.npmjs.com) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) are installed on your system

#### Installation

1. Install this code on your local system
    
        ```
        cd /path/to/install/location
        
        git clone https://github.com/aymanebenhima/vue-cinema.git
        ```  
   
2. Change into directory

    ```
    cd vuejs-cinema
    ```
    
3. Install dependencies

    ```
    npm install
    ```

4. Create a `.env` file by copying the sample

    ```
    cp .env_sample .env
    ```
    
    Edit the .env file and replace any variables if needed
    
5. Start project

    ```
    npm run start
    ```

Your site will be available at *localhost:[PORT]* where `PORT` is whatever value is set in your `.env` file.
