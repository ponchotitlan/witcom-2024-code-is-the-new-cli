# [WITCOM 2024 - Puerto Vallarta, MX 🇲🇽🌊🤖](https://witcom.upiita.ipn.mx/)

<p align="center">
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/made-with-python.svg" /></a>
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/built-with-love.svg" /></a>
  <a href="https://forthebadge.com"><img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" /></a>
</p>

## ```</Code is the new CLI>``` Network Programmability and beyond

Muchas gracias por haber formado parte de esta sesión. En este repositorio puedes encontrar las demos que se presentaron durante la charla, así como las diapositivas de la misma.

## Demo 1: NETCONF & YANG

El playbook de Jupyter se encuentra en el directorio raíz de este repositorio. Para hacer uso del contenido, es necesario seguir estos pasos:

1. Descarga el directorio público usando git:

```
git clone https://github.com/ponchotitlan/witcom-2024-code-is-the-new-cli
```

2. Crea un entorno virtual usando ```venv``` e instala las bibliotecas mencionadas en el repositorio. Los siguientes pasos son exclusivos para sistemas Linux (incluso MacOS):
```
(base) ~ % cd witcom-2024-code-is-the-new-cli
(base) witcom-2024-code-is-the-new-cli % python3 -m venv my_venv
(base) witcom-2024-code-is-the-new-cli % source my_venv/bin/activate
(my_venv) (base) witcom-2024-code-is-the-new-cli % pip3 install -m requirements.txt 
(my_venv) (base) witcom-2024-code-is-the-new-cli % pip3 install -r requirements.txt
```

3. Abre el playbook de Jupyter con tu IDE preferido, y selecciona como kernel de Python el entorno virtual recién creado.

## Demo 2: NetDevOps de ACLs

Esta demo está habilitada solamente para mi runner local (algún día será hablitada en un entorno público), pero de mientras puedes consultar el pipeline visto en la charla en [este link de GitLab](https://gitlab.com/ponchotitlan/netdevops-nso-demo/-/pipelines/1298214091). 

La definición del pipeline [puede ser consultada en este archivo.](https://gitlab.com/ponchotitlan/netdevops-nso-demo/-/blob/main/.gitlab-ci.yml?ref_type=heads)

El Merge Request visto en la charla [se encuentra en este enlace.](https://gitlab.com/ponchotitlan/netdevops-nso-demo/-/merge_requests/1)

## Más información
- [💻 Tutoriales de Cisco acerca de Programmability](https://xrdocs.io/programmability/)
- [📦 Model-Driven Programmability](https://developer.cisco.com/site/standard-network-devices/)
- [🏛️ Cisco DevNet](https://developer.cisco.com/)
- [🧠 White paper - How automation is driving network engineer skills transformation](https://www.cisco.com/c/dam/en/us/solutions/collateral/executive-perspectives/technology-perspectives/automation-driving-network-eng-skills-trans.pdf)

---

Hecho con 🧡  por [Alfonso Sandoval - Cisco](https://linkedin.com/in/asandovalros)