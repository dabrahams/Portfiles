# My Local Portfiles

I just added 

    file:///Users/dave/Public/Macports/Portfiles
    
to the front of `/opt/local/etc/macports/sources.conf`

## Making Changes

### To Calculate the New Checksums

    port -v checksum
    
### After Adding a New `Portfile`

in this directory,

    portindex
    
## Official References

* https://trac.macports.org/wiki/MaintainingAPort
* http://guide.macports.org/#development

