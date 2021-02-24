We just get an IP, so we run a quick scan using rustscan

```

$ rustscan -a 10.10.10.14 -u5000

```

![Wolfie](images/wolfie/rust.png "Scanning")
![Wolfie](images/wolfie/nmap.png "Scanning")

We have port 80, so let's connect.

![Wolfie](images/wolfie/woas.png "Wiki on a stick")

A little bit of googling shows it's "Woas or Wiki on a Stick". Meh. Let's check the source code first.

![Wolfie](images/wolfie/flag1.png "Flag!")

# o.o

Cool! 100 pts!