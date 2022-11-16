2022-10-24 21:05
Status: #idea
Tags: [[Coding]], [[Javascript]]

# Anatomia de uma extensão do navegador
Primeiro você tem o manifest.json na raiz do projeto. Ele vai ter referencia para todas as outras partes da sua extensão. 

#### Background page
é para rodar scripts de longa duração. Pelo que entendi ele vai começar a rodar quando tu abre o navegador

#### Content scripts
é o script que é injetado na sua página

#### Browser action
é o popup da extensão. Se tu definir um html vai aparecer o popup, senão vai só disparar um evento q o botão foi clicado

#### Page action 
não sei e não usei

#### Web Acessible resources
eu usei pra botar as imagens que eu coloquei na página

![[Pasted image 20221024210558.png]]

---
# References

[Página da mozila sobre anatomia de uma extensão](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Anatomy_of_a_WebExtension)