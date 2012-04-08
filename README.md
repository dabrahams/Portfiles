# My Local Portfiles

I just added 

    file:///Users/dave/Public/Macports/Portfiles
    
to the front of `/opt/local/etc/macports/sources.conf`

## Making changes

### To calculate the new checksums

    port -v checksum
    
### After adding a new `Portfile`

in this directory,

    portindex
    
