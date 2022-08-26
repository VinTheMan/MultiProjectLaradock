<p align="center">
    <img src="/.github/home-page-images/laradock-logo.jpg?raw=true" alt="Laradock Logo"/>
</p>

<p align="center"><b>Full PHP development environment based on Docker.</b></p>

<p align="center">
    <a href="https://zalt.me"><img src="http://forthebadge.com/images/badges/built-by-developers.svg" alt="forthebadge" width="180"></a>
</p>

<p align="center">
	<a href="https://laradock.io">
	   <img src="https://raw.githubusercontent.com/laradock/laradock/master/.github/home-page-images/documentation-button.png" width="300px" alt="Laradock Documentation"/>
	</a>
</p>

## When in production server

cp docker-compose-server.yml /home/it/PEGA_Projects/MultiProjectLaradock/docker-compose.yml

## Docker compose commands

docker compose up nginx workspace smt_workspace redis mssql <br />
docker compose up -d nginx workspace smt_workspace redis mssql <br />

## Syncing a forked project (update to the newest laradock)

git remote add upstream https://github.com/laradock/laradock.git
git fetch upstream
git rebase upstream/master
