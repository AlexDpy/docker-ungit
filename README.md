`docker run -it --rm -p 8448:8448 -v $PWD:/var/www -v /etc/ssh/ssh_config:/etc/ssh/ssh_config -v ~/.ssh:/home/ungit/.ssh -v $SSH_AUTH_SOCK:/ssh-agent -e SSH_AUTH_SOCK=/ssh-agent alexdpy/ungit`
