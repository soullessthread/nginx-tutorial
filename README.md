# nginx-tutorial

Hello
<br />
this is a tutorial for setting up nginx and an example html page

<br/>
<br/>
<h3>Step 1: Creating a Droplet</h3>
<p>
    first we need to create a droplet in digital ocean and log in to it
    we will be using an arch system for this tutorial
    example command for logging in using ssh and public key: ssh -i C:\Users\abbas\.ssh\do-key Peter@137.184.181.71
</p>

<h3>Step 2: Installing the necessary applications</h3>
<p>
    We will be needing the following applications:
</p>
<h5>Vim</h5>
<p>
    Vim is a highly configurable text editor built to enable efficient text editing.
    <img src="https://www.fosslinux.com/wp-content/uploads/2023/01/install-vim-ubuntu.png" alt="Vim" width="500">
    to install vim: sudo packman -S vim
</p>
<h5>Nginx</h5>
<p>
    Nginx, pronounced "engine x," is a widely used open-source web server technology known for its high performance, scalability, and ability to handle a large number of concurrent requests efficiently.
    and we will be using it to serve our html page.
    to install nginx: sudo packman -S nginx
</p>