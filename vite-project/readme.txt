-> docker init
   
    npm run build -> n "no"
     ->  npm run dev
    What port does your server listen on?
    5173


paste docker file from react-docker
second in compose.yaml file replace server with web: remove environment veriable
volumes:
      - .:/app
      - .:/app/node_modules

-> docker compose up "if occure some error the run as Adminstratar yeh.. ya may ask some password duh....."
You got some error "port is already allocated" hahaha... goto in docker desktop stop previous runnig port images....
rerun command.........
and dont forgot add in package.json --host  
->"dev": "vite --host",

#============Docker Compose watch===============

