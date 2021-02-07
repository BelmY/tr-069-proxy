# Sagemcom F@ST 5657 configuration decryptor

Based on NoConroy's posts
[Sagemcom F@ST5355 Reverse Engineering - Part 2](https://web.archive.org/web/20180129221204/https://noconroy.net/sagemcom-fast5355-re-p2.html)
and
[Sagemcom F@ST5355 Reverse Engineering - Part 3](https://web.archive.org/web/20180129221204/https://noconroy.net/sagemcom-fast5355-re-p2.html).

## Usage

To decrypt:

    python gsdf.py d < device.cfg | gunzip > device.xml

To encrypt:

    gzip device.xml | python gsdf.py e > device.cfg