# maratonIME
Esse é um blog feito na plataforma [Jekyll](http://jekyllrb.com) baseado no tema [hikari](https://github.com/m3xm/hikari-for-Jekyll). Para o apoio às maratonas de programação no IME-USP.

# Contribuição
Foi criado um ambiente um pouco diferente para se ter uma forma ágil de enviar código novo ao [servidor](http://www.ime.usp.br/~maratona). Por isso, o setup é um pouco diferente ao de um Jekyll normal. 

## Setup
Para instalar o ambiente do site no seu computador, siga os seguintes passos 

1) Baixe o código fonte do site, onde devem ser feitas as alterações  
```
git clone https://github.com/codigoteca-ime-usp/blog-maratonime.git
```  
2) Para entrar na pasta do projeto  
```
cd blog-maratonime
```
3) Isso é muito importante, assim você pode atualizar facilmente o conteúdo do site online.
```
git clone https://github.com/codigoteca-ime-usp/blog-maratonime.git _site  
```
4) Entre na pasta de Build
```
cd _site
```
5) Esse comando faz com que os dois passos acima tenham algum sentido.  
```
git checkout built
```  

Agora é só editar o código em `blog-maratonime` e ser feliz :D.

## Onde Contribuir?
O site é baseado em [Jekyll](http://jekyllrb.com), que é um software escrito em Ruby com os quais é possível montar, de forma rápida e fácil um blog estático com conteúdo feito em [Markdown](http://daringfireball.net/projects/markdown/).  
Para escrever um texto, basta adicionar conteúdo à pasta '\_posts' em forma de Markdown.  
Para alterar o layout e outras coisas sobre o site, aprenda Jekyll :).

## E depois?
Depois de fazer as alterações no código em `blog-maratonime`, você deve construir o site com o Jekyll. Para isso, é necessário tê-lo instalado. Se você tem, siga os seguintes passos:
1) Construa o código estático do site:
```
jekyll build
```
2) Teste suas alterações, veja se está tudo como esperava, commite o código alterado e atualize a branch master:
```
git add (arquivos editados)
git commit -m "(mensagem)"
git push origin master
```  
3) Para atualizar o conteúdo do site online, primeiro faça o commit do código compilado na branch built e atualize no repositório do GitHub.
```
cd built
git add -A
git commit -m "<alguma mensagem>"
git push origin built
```
4) Vá até a pasta do projeto online e atualize o código compilado:  
```
git pull origin built
```

# Sucesso
Esse ambiente foi montado e pensado por [victorsenam](http://github.com/victorsenam). Entre em contato para qualquer ajuda.
