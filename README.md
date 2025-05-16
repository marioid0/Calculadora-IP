# Calculadora IP

Uma calculadora de rede IP desenvolvida em Python com interface gráfica usando Tkinter.

## 📋 Descrição

Esta calculadora IP é uma ferramenta que permite calcular diversos parâmetros de rede a partir de um endereço IP e sua máscara de sub-rede. A aplicação oferece uma interface gráfica intuitiva e moderna, com um design elegante em tons de azul escuro.

## 🚀 Funcionalidades

- Cálculo de parâmetros de rede a partir do endereço IP e máscara CIDR
- Identificação do endereço de rede
- Determinação do primeiro e último host utilizável
- Exibição do endereço de broadcast
- Classificação do endereço IP (Classe A, B ou C)
- Identificação se o endereço é público ou privado
- Cálculo do número de sub-redes possíveis
- Contagem de hosts válidos por sub-rede

## 💻 Requisitos

- Python 3.x
- Biblioteca Tkinter (geralmente incluída na instalação padrão do Python)
- Módulo ipaddress (biblioteca padrão Python)

## 🎯 Como Usar
1. Clone o repositório:
```bash
git clone https://github.com/marioid0/Calculadora-IP
```
2. Navegue até o repositório:
```bash
cd Calculadora-IP
```
2. Execute o arquivo `Calculadora_IP.py`
```bash
python Calculadora_IP.py
```
4. Insira um endereço IP válido no campo "Endereço de Rede"
5. Insira a máscara de sub-rede em notação CIDR (exemplo: 24 para /24)
6. Clique no botão "Calcular"
7. Os resultados serão exibidos na área de texto abaixo

## 🎨 Interface

- Design moderno com tema escuro
- Janela de tamanho fixo (600x550 pixels)
- Campos de entrada com fonte legível
- Área de resultados com barra de rolagem
- Botões e elementos visuais intuitivos

## ⚠️ Tratamento de Erros

A calculadora inclui validação de entrada e exibe mensagens de erro quando:
- O endereço IP é inválido
- A máscara CIDR é inválida
- O formato de entrada está incorreto

## 🔧 Desenvolvimento

Desenvolvido utilizando:
- Python como linguagem principal
- Tkinter para a interface gráfica
- Módulo ipaddress para cálculos de rede
