# Chatty - Implementação Chatify em Laravel

Este projeto foi desenvolvido com a meta de implementar o Chatify, boilerplate de chat em tempo real feito por manuafio, em Laravel 12.x

## Sumário

Conteúdos abordados nesse README

1. [Criando o Projeto](#1-criando-o-projeto)
2. [Instalando Breeze](#2-instalando-breeze)
3. [Instalando Chatify](#3-instalando-chatify)
4. [Finalizando as Instalações](#4-finalizando-as-instalações)
5. [Código Comentado](#5-código-comentado)
6. [Projeto Rodando](#6-projeto-rodando)
7. [Banco de Dados](#7-banco-de-dados)

---

<br />

## 1. Criando o Projeto

`laravel new laravel-chatty`

<img width="662" height="563" alt="1" src="https://github.com/user-attachments/assets/be30175a-a141-4a76-96e3-916fc5837182" />
<blockquote> Comando inicial para a criação do projeto </blockquote>
<br />

`migrations`

<img width="1012" height="544" alt="2" src="https://github.com/user-attachments/assets/ac28908f-d419-4ae9-94a1-8ae7f5cb4db8" />
<blockquote> Seleção e Criação do Banco de Dados (MySQL) </blockquote>
<br />

`npm install and npm run build`

<img width="664" height="349" alt="3" src="https://github.com/user-attachments/assets/ee94cca2-a642-4baf-8381-3c1e7ecd08c6" />
<blockquote> Instalação e compilação de dependências do Node.js </blockquote>

## 2. Instalando Breeze

`cd laravel-chatty` e `composer require laravel/breeze --dev`

<img width="1202" height="639" alt="1" src="https://github.com/user-attachments/assets/906fbb12-68aa-4bf6-95bf-0109b685b749" />
<blockquote> Requisição da dependência de desenvolvedor do `laravel/breeze` para o projeto via `composer` </blockquote>
<br />

`php artisan breeze:install`

<img width="1214" height="685" alt="2" src="https://github.com/user-attachments/assets/6b805af3-b3e1-4475-b954-53da7287fb0f" />
<blockquote> Instalação do Breeze via `artisan` (php) </blockquote>

## 3. Instalando Chatify

`composer require munafio/chatify`

<img width="1199" height="724" alt="1" src="https://github.com/user-attachments/assets/9bd9907b-17aa-4fa3-b9b5-c3aa7ea26a29" />
<blockquote> Requisição da dependência do `munafio/chatify` para o projeto via `composer` </blockquote>
<br />

`php artisan chatify:install`

<img width="1689" height="897" alt="2" src="https://github.com/user-attachments/assets/0a710603-fdc7-4eba-bce1-c03d7183d42a" />
<blockquote> Instalação do Chatify via `artisan` (php) </blockquote>


## 4. Finalizando as Instalações

`php artisan migrate`

<img width="1192" height="219" alt="1" src="https://github.com/user-attachments/assets/447183af-5a03-4d68-9873-ababc03f4d53" />
<blockquote> Realizando as migrações necessárias para o funcionamento das dependências instaladas (Breeze e Chatify) </blockquote>

## 5. Código Comentado

`.env` e `.env.example`

<img width="462" height="163" alt="env" src="https://github.com/user-attachments/assets/335483e2-f574-4670-a098-6526da740abf" />
<blockquote> Variáveis de Ambiente do Pusher </blockquote>
<br />

`routes/chatify/web.php`

<img width="967" height="773" alt="web" src="https://github.com/user-attachments/assets/a3105810-cec0-41e2-b57e-2ace3aeb29a0" />
<blockquote> Rotas do Chatify </blockquote>
<br />

`resources/views/layouts/navigation.blade.php`

<img width="616" height="93" alt="dashboard" src="https://github.com/user-attachments/assets/b6f9fdb7-54ae-4407-bf72-f0248f4dcc12" />
<blockquote> Link de Navegação para o Chatify </blockquote>

## 6. Projeto Rodando

<img width="1917" height="997" alt="1" src="https://github.com/user-attachments/assets/8dcf4c6a-4770-4b86-bf57-1c099299a5b8" />
<blockquote> Conversa entre dois usuários: <b>Usuário01</b> e <b>Usuário02</b> </blockquote>

## 7. Banco de Dados

`Estrutura do Banco de Dados`

<img width="1051" height="362" alt="estrutura" src="https://github.com/user-attachments/assets/9ab6c37c-22f1-465e-99d0-4bc093b32cc1" />
<br />

`Registros da tabela de mensagens`

<img width="1132" height="393" alt="mensagens" src="https://github.com/user-attachments/assets/f015d8cb-2228-4b98-9c5e-cf5d0f361ecc" />
