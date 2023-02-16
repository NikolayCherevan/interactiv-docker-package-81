## FROM NIK:
You should just clone your project in this folder
(don't forget write . while clone at the end and also change
mapping in compose.dev.yaml if it's needed and project
structure other)

## Main commands (them you may need):

## bin/node-bash 
Check containers files

## bin/root

Root permissions

## docker compose exec -u 0 node sh  

Root permissions for node container

## docker compose exec -u 0 app sh 

Root permissions for main app container with code

## bin/composer

## Other command and recommendations with docker you can find here:

https://github.com/markshust/docker-magento

## and also here for FE devs

https://interactiv4.atlassian.net/wiki/spaces/ENG/pages/3137503256/Development