# fast_docker_registry
fast way of creating a let's encrypt docker registry with GUI. I did not find an out-of-the-box solution, so I made this one.

Just swap \<your email\> in nginx-certbot.env with your email and \<your domain\> in user_conf.d/nginx.conf to your domain name and you are good to go.

## Disclaimer

I only tested this on my Raspberry Pi 4. I see no reason why this should not work on other architectures, but no guarantees.

## Acknowledgement

Thanks for <a href="https://hub.docker.com/u/joxit">joxit</a> for creating <a href="https://hub.docker.com/r/joxit/docker-registry-ui">docker-registry-ui</a>. Also a thanks is in order for <a href="https://hub.docker.com/u/jonasal">jonasal</a> for creating <a href="https://hub.docker.com/r/jonasal/nginx-certbot">nginx-certbot</a>.
