# fast_docker_registry
fast way of creating a lets encrypt docker registry with gui. I did not find a out of the box solution, so I made this one.

Just swap \<your email\> in nginx-certbot.env with your email an \<your domain\> in user_conf.d/nginx.conf to your domain name and your good to go.

## Disclaimer

I only tested this on my Raspberry pi 4. I se no reason as to why this should not work on other architectures, but no guarantees.

## Acknowledgement

Thanks for <a href="https://hub.docker.com/u/joxit">joxit</a> for creating <a href="https://hub.docker.com/r/joxit/docker-registry-ui">docker-registry-ui</a>. Also a thanks is in order for <a href="https://hub.docker.com/u/jonasal">jonasal</a> for creating <a href="https://hub.docker.com/r/jonasal/nginx-certbot">nginx-certbot</a>.
