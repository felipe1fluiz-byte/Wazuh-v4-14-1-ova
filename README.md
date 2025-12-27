# Laboratório Wazuh 4.14.1 com Kali Linux

Descrição

Este repositório documenta a instalação e a configuração de um laboratório de segurança utilizando o Wazuh v4.14.1 integrado a uma máquina virtual Kali Linux.
O ambiente foi desenvolvido com foco em aprendizado prático, familiarização com o dashboard do Wazuh e treinamento em monitoramento e detecção de eventos de segurança.

## Objetivo

O principal objetivo deste laboratório é:

Compreender a arquitetura do Wazuh (Manager, Indexer e Dashboard);

Explorar o Wazuh Dashboard para análise de eventos e alertas;

Realizar a integração de um agente Wazuh em uma VM Kali Linux;

Simular atividades e eventos de segurança para observação e correlação no Wazuh;

Apoiar estudos e treinamentos na área de Blue Team, SIEM e HIDS.

## Ambiente do Laboratório
## Wazuh

Versão: Wazuh 4.14.1

Componentes instalados:

Wazuh Manager

Wazuh Indexer

Wazuh Dashboard

Sistema operacional: Linux (VM dedicada)

## Kali Linux

Sistema operacional: Kali Linux (última versão estável)

Função:

Host monitorado

Instalação do Wazuh Agent

Geração de eventos para análise no dashboard

## Arquitetura

O laboratório segue uma arquitetura simples:

Servidor Wazuh centralizado, responsável pela coleta, indexação e visualização dos eventos;

VM Kali Linux atuando como endpoint monitorado, enviando logs e alertas ao Wazuh Manager;

Comunicação segura entre agente e manager.

## Atividades Realizadas

Instalação do Wazuh 4.14.1 em ambiente virtualizado;

Configuração inicial do Wazuh Dashboard;

Cadastro e gerenciamento de agentes;

Instalação e configuração do Wazuh Agent no Kali Linux;

Validação da comunicação entre agente e manager;

Análise de eventos de segurança no dashboard;

Exploração de alertas, regras e módulos do Wazuh.

## Requisitos

Ambiente de virtualização (VirtualBox, VMware ou similar);

Conhecimentos básicos de Linux;

Noções introdutórias de redes e segurança da informação.

## Observações

Este repositório possui caráter educacional e de treinamento, não sendo destinado a ambientes de produção.
As configurações podem ser adaptadas conforme a necessidade de estudos ou testes adicionai
