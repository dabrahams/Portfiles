# My Local Portfiles

I cloned this repository into /Library/Portfiles/localhost and added

    file:///Library/Portfiles/localhost
    
to the front of `/opt/local/etc/macports/sources.conf`

See [this bug report](https://trac.macports.org/ticket/36950) if you
think it would be nice to clone this repository under your home
directory.  It wouldn't.

## Making Changes

### To Calculate the New Checksums

    port -v checksum
    
### After Adding a New `Portfile`

in this directory,

    portindex
    
## Official References

* https://trac.macports.org/wiki/MaintainingAPort
* http://guide.macports.org/#development

