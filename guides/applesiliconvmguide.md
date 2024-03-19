## Ubuntu Virtual Machine on Apple Silicon (credit to current 1st year student)

[UTM](https://docs.getutm.app/guides/ubuntu/) running [Ubuntu Server for Arm](https://ubuntu.com/download/server/arm) with the Desktop Environment has been tested with the Scotland Yard Coursework and runs reliably on the two machines we have tested it on. It also is useful throughout your studies to have a true Linux environment to supplement your Mac

### Installing UTM running Ubuntu Server + DE

1. Follow the [UTM](https://docs.getutm.app/guides/ubuntu/ tutotial.
2. If you have trouble sharing folders try the following in a terminal (credit to current 1st year student):
```
    $ sudo mkdir [mount point]
    $ sudo mount -t 9p -o trans=virtio share [mount point] -oversion=9p2000.L
    $ sudo chown -R $USER [mount point]
```

   
