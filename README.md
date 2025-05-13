# Poison
![bandicam 2025-04-26 16-36-32-793](https://github.com/user-attachments/assets/2457ae05-77ee-40f0-9975-111f599d6f44)

Ferramenta simples em Bash para detectar vulnerabilidades conhecidas em kernels Linux e recomendar exploits disponíveis para eles.

## 📜 Descrição
Poison é um script que:

- Detecta automaticamente a versão do kernel Linux em uso.

- Compara a versão detectada com uma lista de kernels vulneráveis.

- Indica, caso vulnerável, um link direto para o exploit no Exploit-DB.

- Recomenda a atualização imediata do sistema se uma vulnerabilidade for encontrada.

## ⚙️ Como usar
Clone o repositório:

```bash
wget https://raw.githubusercontent.com/AndreyFreitaz/Poison/refs/heads/main/poison.sh
chmod +x poison.sh
./poison.sh
ou
bash poison.sh
```

## 📋 Lista de Kernels suportados
O script atualmente verifica vulnerabilidades para versões como:

2.6.17

2.6.18

2.6.24

2.6.32

3.0

3.2

3.13

4.4

5.4

5.8

E outros...
