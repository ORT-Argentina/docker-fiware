<h1 align="center">
	Fiware ORT
</h1>

<details>
  <summary ><strong>📖 Table of Contents</strong></summary>
  <ol>
    <li>
      <a href="#about-the-project">About the project</a>
      <ul>
      <li><a href="#built-with">Built with</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

## 👓 Documentación

> 🔧 Este repositorio esta destinado a la construcción y educación sobre el entorno Fireware y varios de sus servicios.

### Built with

![Docker](https://d1.awsstatic.com/acs/characters/Logos/Docker-Logo_Horizontel_279x131.b8a5c41e56b77706656d61080f6a0217a3ba356d.png)

![Docker compose](https://quintagroup.com/cms/technology/Images/docker-compose-button.jpg)

<p align="right">(<a href="#top">back to top</a>)</p>

## 🔨 Getting Started

Postman Collection in Web:
[Collection](https://www.postman.com/waynimovil/workspace/public-ort/collection/71111-be6b21f3-7599-4253-8945-d5a4244f8fa5?action=share)

### Prerequisites

We reccommend using [Ubuntu](https://ubuntu.com/) as OS.

### Grafana

Default User/Password

admin - admin

### Installation

1. Configure hosts file


2. Clone the repo

```bash
git clone git@github.com:
```

> **Enviroment:** <br> For use the wallet enviroment, you must clone the related projects and complete the path of the project on the .env file.
>
> Ex: `PROFILE_PATH=`


3. Install & Execute

```bash
docker-compose up -d
```

4. To be able to check that everything is working correctly

```bash
docker ps
```

<p align="right">(<a href="#top">back to top</a>)</p>

## 🧱Fold Structure

> 🔧 [on construction]

<p align="right">(<a href="#top">back to top</a>)</p>

## 🤝Contributing

[Fiware Orion](http://telefonicaid.github.io/fiware-orion/api/v2/stable/)

[Quantumleap](https://quantumleap.readthedocs.io/en/latest/)

[Grafana](https://github.com/grafana/grafana)

[Keyrock](https://keyrock-fiware.github.io/)

[Alt Wirecloud](https://wirecloud.readthedocs.io/en/stable/)

[Draco](https://fiware-draco.readthedocs.io/)

To be able to access the dashboard directly:

http://localhost:8080

Draco UI

https://localhost:8443/nifi

Draco API

https://localhost:8443/nifi-api/flow/status


```bash
docker exec -ti fiware-orion /bin/bash
```

<p align="right">(<a href="#top">back to top</a>)</p>