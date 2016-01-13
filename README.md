Matthew Silver Resume
====================

This repo contains the style file and content for the resume. To generate a pdf of the resume, make sure that latex and all dependencies are installed (see below) and then just make it in the current directory:

```bash
make
```

Because this resume is on the internet and I'm not super interested in putting my phone number out there, the phone number is anonymized. To make a pdf with a phone number, pass the number as an argument to make:

```bash
make phone=201.555.1234



### Dependencies

All dependencies are stored in the file dependencies.txt. To install these dependencies in ubuntu, run:

```bash
sudo apt-get install $(< dependencies.txt)
```
