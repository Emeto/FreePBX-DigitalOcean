![FreePBX Logo](https://www.sangoma.com/wp-content/uploads/2018/01/freepbx-logo.png)

# FreePBX for DigitalOcean
FreePBX is a web-based open source GUI (graphical user interface) that controls and manages Asterisk (PBX), an open source communication server.

This read-me contains information about a FreePBX image I generated for use inside DigitalOcean or other cloud service provider that supports custom images initialized via cloud-init. It has to be noted that since this is a VDI file, it can also be used by any virtualization software that supports the VDI format.

## Image information
|                   |                                      |
|--------------------------|-----------------------------------------|
| Format                   | VDI                                     |
| File Size (gzipped)      | ~ 1.8 GB                                |
| File Size (uncompressed) | ~ 4.4 GB                                |
| Asterisk version         | 13.22.0 (Includes Opus, Silk, and G729) |
| FreePBX                  | 14.0.10.3                               |
| OS                       | CentOS/RHEL 7.6.1810                    |

This image does already contains cloud-init.


## Download link
You can download the gzipped vdi file by following this link

https://dl.emetophobic.com/freepbx-vdi/FreePBX-SNG7-PBX-64bit-1904-stable.gz
