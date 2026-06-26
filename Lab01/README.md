# Lab 01 - Comunicação entre Duas Redes

## 📖 Descrição

Neste laboratório foi configurada a comunicação entre duas redes distintas utilizando um roteador Cisco.

---

## 🎯 Objetivos

- Configurar endereçamento IPv4;
- Configurar interfaces do roteador;
- Definir o Gateway Padrão;
- Validar a comunicação entre as redes utilizando Ping.

---

## 🖥️ Topologia

PC1 ── Switch1 ── Roteador ── Switch2 ── PC2

---

## 🌐 Endereçamento

### Rede 1

| Dispositivo | IP | Máscara | Gateway |
|------------|----|---------|---------|
| PC0 | 192.168.1.2 | 255.255.255.0 | 192.168.1.1 |

### Rede 2

| Dispositivo | IP | Máscara | Gateway |
|------------|----|---------|---------|
| PC1 | 192.168.2.2 | 255.255.255.0 | 192.168.2.1 |

### Roteador

| Interface | IP |
|-----------|----|
| G0/0 | 192.168.1.1 |
| G0/1 | 192.168.2.1 |

---

## 🧠 Conceitos Aplicados

- IPv4
- Máscara de Sub-rede
- Gateway Padrão
- Roteamento entre Redes
- ICMP (Ping)

---

## ✅ Resultado

As duas redes conseguiram se comunicar com sucesso através do roteador.

---

## 📂 Arquivos

- `lab01.pkt`
- `README.md`
