# Default config file of Nginx

This is my first project with Rebrain. Here was created a repository for education purposes only. It will stores default config file of Nginx.

## Getting Started

This project will get you a insight of my skills to create git repositories and to show results of my work.

### Prerequisites

No prerequisites you need to use any files from this project. 

### Installing

You may view and edit the config file of Nginx with any text editor. For example:

```
$ vi nginx.conf
```

Simply copy the config file to your project, edit it and use.

## Running the tests

This part will be filled in some future. At the moment this part isn't necessary.

## Deployment

To deploy config file [nginx.conf](https://gitlab.rebrainme.com/andreyka_larchenko_at_gmail_com/rebrain-devops-task1/-/blob/master/nginx.conf) in your own project you need edit it to meet your requirements.
At least you will need to set the hostname and the TCP port where Nginx should listen for connections.

    server {
            # You would want to make a separate file with its own server block for each virtual domain
            # on your server and then include them.
            listen       80;
            #tells Nginx the hostname and the TCP port where it should listen for HTTP connections.
            #listen 80; is equivalent to listen *:80;
            server_name  localhost;
            # lets you doname-based virtual hosting

And you may of course to do some other changes if you need it.

## Built With

* [GitLab by Rebrain](https://gitlab.rebrainme.com/) - The Git hosting by Rebrain

## Contributing

This part will be filled in some future. At the moment this part isn't necessary.

## Versioning

For the versions available, see the [tags on this repository](https://gitlab.rebrainme.com/andreyka_larchenko_at_gmail_com/rebrain-devops-task1/-/tags). 

## Authors

* **Andrey Larchenko** - [AndreyL](https://gitlab.rebrainme.com/andreyka_larchenko_at_gmail_com)

## License

This part will be filled in some future. At the moment this part isn't necessary.

## Acknowledgments

* *~~I thank my wife for support me in my work~~*
* *I thank guys from Rebrain for interesting task that develops my skills*

