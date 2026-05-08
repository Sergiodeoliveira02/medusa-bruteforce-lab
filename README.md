# \# Medusa Brute Force Lab

# 

# \## Descrição

# 

# Projeto desenvolvido para fins educacionais utilizando Kali Linux, Medusa e Metasploitable 2 em ambiente controlado.

# 

# O objetivo foi compreender ataques de força bruta e identificar medidas de mitigação.

# 

# \---

# 

# \## Ferramentas Utilizadas

# 

# \- Kali Linux

# \- Medusa

# \- Metasploitable 2

# \- DVWA

# \- Nmap

# \- VirtualBox

# 

# \---

# 

# \## Configuração do Ambiente

# 

# Foram utilizadas duas máquinas virtuais no VirtualBox:

# 

# \- Kali Linux

# \- Metasploitable 2

# 

# As máquinas foram configuradas em rede Host-Only para permitir comunicação em ambiente isolado.

# 

# \---

# 

# \## Reconhecimento com Nmap

# 

# Comando utilizado:

# 

# ```bash

# nmap -sV 192.168.56.20

# ```

# 

# \### Resultado

# 

# !\[Nmap](images/nmap.png)

# 

# \---

# 

# \## Ataque FTP com Medusa

# 

# Comando utilizado:

# 

# ```bash

# medusa -h 192.168.56.20 -u msfadmin -p msfadmin -M ftp

# ```

# 

# \### Resultado

# 

# !\[Medusa](images/medusa.png)

# 

# \---

# 

# \## Teste no DVWA

# 

# Foi realizado um teste simples no DVWA para simular autenticação vulnerável.

# 

# \### Resultado

# 

# !\[DVWA](images/dvwa.png)

# 

# \---

# 

# \## Mitigações

# 

# \- Utilização de senhas fortes

# \- MFA

# \- Bloqueio após múltiplas tentativas

# \- Monitoramento de logs

# \- Restrição de acesso

# 

# \---

# 

# \## Conclusão

# 

# O projeto permitiu compreender conceitos básicos de força bruta, reconhecimento de serviços e boas práticas de segurança ofensiva em ambiente controlado.

