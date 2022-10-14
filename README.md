# Linux-kernels

## Data format

```json
{
    "kernels": {
        "1": {
            "0": [
                {
                    "link": "https://cdn.kernel.org/pub/linux/kernel/v1.0/linux-1.0.patch.alpha.bz2",
                    "version": "1.0.patch.alpha",
                    "major": "1",
                    "minor": "0"
                },
                {
                    "link": "https://cdn.kernel.org/pub/linux/kernel/1.0.patch.alphalinux-1.0.patch.alpha.gz",
                    "version": "1.0.patch.alpha",
                    "major": "1",
                    "minor": "0"
                },
                {
                    "link": "https://cdn.kernel.org/pub/linux/kernel/1.0.patch.alphalinux-1.0.patch.alpha.sign",
                    "version": "1.0.patch.alpha",
                    "major": "1",
                    "minor": "0"
                }
              ...
              ]
        }
    }
}
```

## Generate kernels.json

You can generate/update this list of kernel in JSON locally:

```
$ ./get_kernels.py 
[+] Parsing v1.0/ ...
[+] Parsing v1.1/ ...
[+] Parsing v1.2/ ...
[+] Parsing v1.3/ ...
[+] Parsing v2.0/ ...
[+] Parsing v2.1/ ...
[+] Parsing v2.2/ ...
[+] Parsing v2.3/ ...
[+] Parsing v2.4/ ...
[+] Parsing v2.5/ ...
[+] Parsing v2.6/ ...
[+] Parsing v3.0/ ...
[+] Parsing v3.x/ ...
[+] Parsing v4.x/ ...
[+] Parsing v5.x/ ...
[+] Parsing v6.x/ ...
```

## Contributing

Pull requests are welcome. Feel free to open an issue if you want to add other features.
You can change what ever you want in this repo

