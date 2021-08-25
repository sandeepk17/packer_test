# packer_test


cloned Repo from [StefanScherer](https://github.com/StefanScherer/packer-windows)
Orginal Credits to StefanScherer


1. create and iso folder
    
    a) Download and keep [Windows10.iso](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-10-enterprise) enterprise image
    b) Download [virtio-win.iso](https://fedorapeople.org/groups/virt/virtio-win/direct-downloads/stable-virtio/virtio-win.iso) 

2. Edit the Iso_url and virtio_win_iso path.
3. Change the output directory if needed.
4. Specify the format qcow2 or raw.
5. Remove / keep the post processing part with output format needed.! 
6. run command 

```sh
"packer build windows_10.json"
```
