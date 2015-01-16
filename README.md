# kernelclean

Clean old Ubuntu and Debian kernels easily

# Usage

```
# interactive mode
kernelclean

# automatic mode (assume yes)
kernelclean -y
```

# Sample run

```
runar@server:~$ sudo kernelclean

Running kernel:    3.13.0-43-generic 

Keeping kernels:   3.13.0-44-generic 
                   3.13.0-43-generic 

Purging packages:  linux-headers-3.13.0-39 
                   linux-headers-3.13.0-39-generic 
                   linux-headers-3.13.0-40 
                   linux-headers-3.13.0-40-generic 
                   linux-headers-3.13.0-41 
                   linux-headers-3.13.0-41-generic 
                   linux-image-3.13.0-32-generic 
                   linux-image-3.13.0-37-generic 
                   linux-image-3.13.0-39-generic 
                   linux-image-3.13.0-40-generic 
                   linux-image-3.13.0-41-generic 
                   linux-image-extra-3.13.0-32-generic 
                   linux-image-extra-3.13.0-37-generic 
                   linux-image-extra-3.13.0-39-generic 
                   linux-image-extra-3.13.0-40-generic 
                   linux-image-extra-3.13.0-41-generic 

[Enter] to continue: 

Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following packages will be REMOVED:
  linux-headers-3.13.0-39* linux-headers-3.13.0-39-generic*
  linux-headers-3.13.0-40* linux-headers-3.13.0-40-generic*
  linux-headers-3.13.0-41* linux-headers-3.13.0-41-generic*
  linux-image-3.13.0-32-generic* linux-image-3.13.0-37-generic*
  linux-image-3.13.0-39-generic* linux-image-3.13.0-40-generic*
  linux-image-3.13.0-41-generic* linux-image-extra-3.13.0-32-generic*
  linux-image-extra-3.13.0-37-generic* linux-image-extra-3.13.0-39-generic*
  linux-image-extra-3.13.0-40-generic* linux-image-extra-3.13.0-41-generic*

[...]
```

# Installation

Put the file ```kernelclean``` somewhere (like ```/usr/local/sbin```) and make sure it is executable.

# License

Licensed under the permissive [MIT license](https://github.com/emning/kernelclean/blob/master/LICENSE). Feel free!
