# HealPulse

Sistema de monitoramento cardíaco via IoT, desenvolvido como Trabalho de Conclusão de Curso no **Centro Universitário Nossa Senhora do Patrocínio (Itu-SP)**, com o objetivo de usar tecnologia para aumentar a segurança de pacientes em hospitais públicos.

A ideia: dispositivos IoT (pulseiras/sensores) capturam sinais vitais do paciente — ECG, pressão arterial, oxigenação (SpO2), frequência cardíaca e respiratória — e o sistema exibe esses dados em um dashboard simples e intuitivo, gerando alertas automáticos quando algum parâmetro sai do normal. Isso ajuda a equipe de saúde a identificar casos graves mais rápido, sem depender só da triagem manual.

## 🔴 Demonstração ao vivo

Este repositório contém o protótipo da tela de monitoramento (CardioView), publicado via GitHub Pages:

**👉 https://renanc4m1lo.github.io/HealPulse/**

> Abrindo o `index.html` aqui pelo GitHub você só vê o código-fonte — para ver a tela funcionando de fato (com os gráficos de ECG, SpO2 e respiração animados em tempo real), use o link acima.

O protótipo simula os sinais vitais de um paciente e permite trocar entre cenários clínicos pelo seletor no rodapé:
- Normal, Taquicardia, Bradicardia, Hipóxia e Hipertensão

Cada cenário dispara alertas visuais e sonoros quando os valores saem da faixa segura (frequência cardíaca, SpO2, pressão arterial), igual aconteceria com dados reais vindos de um sensor.

## 👥 Equipe

- Gustavo Ianetta
- Matheus Andrade da Silva
- Renan Augusto Camilo da Costa
- Vinicius Guimarães Domenice
- Wiliam Pereira da Silva

**Orientadora:** Waldinelly Martha Alves Costa

## 🛠️ Tecnologia

Este protótipo é só front-end (HTML, CSS e JavaScript puro, sem dependências), com os dados vitais simulados em tempo real no navegador — não há backend real conectado aqui. A proposta completa do sistema (telas de Login, Dashboard, Pacientes e Cadastro de Paciente, com persistência real) prevê HTML/CSS/JS no frontend, PHP + Apache no backend e MySQL como banco de dados, comunicando-se via API REST.
