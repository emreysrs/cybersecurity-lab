# Lab Report 01 — OWASP Juice Shop Installation

## Objective
Set up a local web security practice environment using OWASP Juice Shop.

## Environment
- OS: Kali Linux
- Virtualization: VMware Fusion
- Container platform: Docker
- Application: OWASP Juice Shop

## Installation
Downloaded the official Juice Shop Docker image:

```bash
docker pull bkimminich/juice-shop
```

Started the application locally:

```bash
docker run --rm -p 127.0.0.1:3000:3000 bkimminich/juice-shop
```

## Result
The application started successfully and was accessible at:

`http://localhost:3000`

## Lessons Learned
- Docker can run web applications in isolated containers.
- DNS configuration is important for downloading container images.
- Localhost binding helps keep a practice application restricted to the local machine.

## Safety
All practice activities are restricted to my own local lab.

## Status
SUCCESS — Installation completed.
