# reverse-shell-generator
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-16-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
Hosted Reverse Shell generator with a ton of functionality -- (great for CTFs)
<br> [![Netlify Status](https://api.netlify.com/api/v1/badges/46dbabe0-23b7-42e6-b04b-e1769dc455ce/deploy-status)](https://app.netlify.com/sites/brave-swartz-5dcdab/deploys)

### Hosted Instance
https://revshells.com

### Features

- Generate common listeners and reverse shells
- Save button to download Payloads from browser.
- Raw mode to cURL shells to your machine.
- Button to increment the listening port number by 1
- URI and Base64 encoding
- LocalStorage to persist your configuration
- Dark, Light and Meme Modes
- HoaxShell integration with custom listener (see link below for more information) | Credit: https://github.com/t3l3machus

### HoaxShell Listener Docs

[https://github.com/t3l3machus/hoaxshell/tree/main/revshells](https://github.com/t3l3machus/hoaxshell/tree/main/revshells)

### Screenshot

![image](https://user-images.githubusercontent.com/70012972/169376352-e6d6b90e-2e2e-46b0-b6f9-0e3f13713e39.png)

## Dev

It's recommended to use the netlify dev command if you're wanting to modify any of the server functions, such as for raw link support:

```
npx netlify dev
```

## Using Docker
Simply run the following commands within this repository to spin up the instance locally using a Docker container

```
docker build -t reverse_shell_generator .

docker run -d -p 80:80 reverse_shell_generator
```

Browse to http://localhost:80

