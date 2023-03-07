<p align="center"><b>Next.js project with nginx reverse proxy on Docker.</b></p>

<br>

##build
docker-compose build
##start
docker-compose up -d
##stop
docker-compose stop
##delete
docker-compose down
##check docker status
docker-compose ps
##execute command in node
docker-compose exec node sh
##get out of node
exit
##npm install
After `execute command in node` process
npm install
##next start
After `execute command in node` process
npm run build
npm run start
##next start in dev
npm run dev
