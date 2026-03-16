### Como usar este código:

1. No VS Code, clique com o botão direito na área vazia da barra lateral esquerda (onde estão os seus arquivos) e selecione **"New File"** (Novo Arquivo).
2. Dê o nome exato de `README.md` (com letras maiúsculas).
3. Copie o bloco de código abaixo e cole dentro desse arquivo.
4. Salve, faça o `git add .`, o `git commit -m "Adiciona README"` e o `git push origin main`, exatamente como você aprendeu!

---

Copie a partir da linha abaixo:

```markdown
# 🌡️ Modelagem e Simulação de Controle de Temperatura em Processos Industriais

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![SciPy](https://img.shields.io/badge/SciPy-Integrate-lightgrey)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-success)

## 📌 Sobre o Projeto
Este repositório contém o desenvolvimento de um modelo matemático e a simulação computacional da dinâmica de aquecimento de fluidos em um ambiente industrial. 

O sistema estudado simula um **tanque de aquecimento a volume constante acoplado a uma tubulação longa** (que gera um atraso de transporte ou "tempo morto"). O objetivo principal é estudar e controlar a temperatura de saída do fluido, permitindo a visualização interativa do comportamento do sistema em malha aberta e em malha fechada utilizando controladores PID.

> **Nota:** Este projeto foi desenvolvido com base nos estudos da disciplina *ENG 07044 - Controle de Processos Industriais* do Departamento de Engenharia Química (DEQUI) da Universidade Federal do Rio Grande do Sul (UFRGS), ministrada pelo Prof. Dr. Jorge Otávio Trierweiler.

---

## ⚙️ Principais Funcionalidades e Aprendizados

* **Modelagem Fenomenológica:** Aplicação de balanços de massa e energia para traduzir o sistema físico em equações diferenciais.
* **Resolução de EDOs:** Utilização do método `solve_ivp` da biblioteca SciPy para calcular a evolução temporal das temperaturas.
* **Tratamento de Tempo Morto:** Discretização da tubulação longa em uma série de sistemas de primeira ordem para simular o atraso de transporte no fluido.
* **Controle em Malha Fechada:** Implementação e sintonia de Controladores PID para lidar com distúrbios e alcançar o *setpoint* desejado.
* **Dashboards Interativos:** Uso avançado de `ipywidgets` e `Plotly` para criar uma interface gráfica dentro do notebook, permitindo alterar os parâmetros do controlador ($K_p$, $T_i$, $T_d$) e visualizar a resposta do sistema em tempo real.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Computação Científica e Matemática:** `numpy`, `scipy.integrate`, `scipy.signal`
* **Engenharia de Controle:** Biblioteca `control` (Módulo MATLAB de compatibilidade)
* **Visualização de Dados:** `matplotlib.pyplot`, `plotly`
* **Interatividade:** `ipywidgets`

---

## 🚀 Como Executar o Projeto na sua Máquina

Se você deseja rodar a simulação interativa localmente, siga os passos abaixo:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_SEU_REPOSITORIO.git)

```

2. **Navegue até a pasta do projeto:**
```bash
cd NOME_DO_SEU_REPOSITORIO

```


3. **Instale as dependências necessárias:**
Recomenda-se o uso de um ambiente virtual. As principais bibliotecas necessárias são:
```bash
pip install numpy scipy matplotlib plotly ipywidgets control jupyter

```


4. **Abra o Jupyter Notebook:**
```bash
jupyter notebook

```


5. Execute o arquivo `00_Introdução.ipynb` e interaja com os gráficos!

---

## 📸 Demonstração Visual

*(Substitua este texto por um GIF ou uma imagem do seu gráfico interativo do Plotly funcionando. Mostre o painel do ipywidgets! Isso faz toda a diferença no portfólio.)*

---

## 👨‍💻 Autor

Desenvolvido por **Bruno Richwicki**.

```