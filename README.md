<div align="center"> 
  
  <h1> Guia prático Github </h1>
 <img src="https://img.icons8.com/nolan/50/github.png"/>

</div>

<div align="">
  
  # Subindo seu repositório no GitHub através da linha de comando
  
  ## Objetivo deste repositório 
  
  Este tutorial é um passo a passo rápido pra quem pretende subir seu repositório no Github, este artigo pode ser de suma importância para quem está iniciando com Git e Github para uso no seu dia a dia.
</div>

## Passos a percorrer:

1. Certifique-se que você tenha o Git instalado em sua máquina. No seu terminal ou prompt de comando, verifique digitando o comando.

```sh
$ git -v 
```
2. No GitHub, crie um novo repositório.

<img src="https://user-images.githubusercontent.com/85380530/142349368-5192b2e2-504a-425a-9891-bc2940309895.png" height="400" width="800">

 Com seu repositório já criado você irá copiar o link HTTPS que foi gerado e guardá-lo para usar nos próximos passos.
 
 <img src="https://user-images.githubusercontent.com/85380530/142349729-d9aa013d-f1da-460f-a8f2-05e4dab42364.png" height="400" width="800">

3. Abra na sua máquina o Git bash ou terminal de comando na pasta do seu projeto.

4. Inicie a pasta como um repositório do Git digitando o comando:

```sh 
$ git init 
```
5. Em seguida, adicione os arquivos de configuração para preparar para fazer um commit: 

```sh 
$ git add . 
```
6. Opcional. Caso não tenha iniciado seu repositório com um README.md, adicione através do comando:

```sh
$ git add README.md
```

7. Crie um commit para subir os arquivos para o repositório.  

```sh 
$ git commit -m "first commit"

```
8. Suba os arquivos utilizando a URL gerada no passo 2 digitando o comando: 

```sh 
$ git remote add origin URL-GERADA-NO-PASSO-2-AQUI
```

9.  Autorize o upload, caso peça seu login e senha autorize.     

```sh 
$ git push -u origin master

```

# 

### Caso este tutorial lhe foi útil, deixe sua ⭐       




