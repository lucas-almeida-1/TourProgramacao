# TourProgramacao
Olá, pessoal! Se você está no GitHub, deve ter interesse em programar em alguma linguagem, certo? Aqui estarei ensinando os primeiros passos para programar em Python ou C/C++. Vamos aprender?
<div>
	<img src="https://media.giphy.com/media/Oj25fisQ3zhukVWY96/giphy.gif" alt="Gif de um pato amarelo com um óculos preto trabalhando num notebook" width=45 height=45>
</div>

## Preparação inicial para escrever códigos de qualquer linguagem.  

Antes de você escolher programar, seja em Python, C/C++ ou outra linguagem, você precisa saber a diferença entre interpretador e compilador.  
## Interpretador x Compilador
Um computador só entende sinais "0" ou "1". Logo, quando escrevemos nossos códigos em uma linguagem, precisamos de algo que faça essa conversão do código em alto nível, que é facilmente entendido por nós, para uma linguagem de baixo nível, que é facilmente entendido pela máquina. Este é o papel do interpretador e compilador.  
<br>
Considere os dois conversores como um tradutor. O interpretador é um tradutor pessoal que estaria do seu lado te dando dicas para aprender uma nova linguagem e o compilador seria um tradutor online que te dá a tradução pronta para usar.  
Para o interpretador, temos um conversor mais lento, que lê linha por linha e executa no computador. Um exemplo de linguagem interpretada é o Python.  
Já o compilador é um conversor muito mais veloz, lendo todas as linhas de uma vez. Um exemplo de linguagem compilada é o C/C++.  
Para aplicações muito grandes, o ideal é que você use uma linguagem compilada ao invés de uma linguagem interpretada.  

## Como programar em alguma linguagem?
## <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=python" width ="30" height="30" /> </a> Python
Python é uma linguagem interpretada.  
Vamos supor que você queira fazer um projeto em Python na sua máquina.  
Se você teve algum problema com códigos em Python, você precisa instalar o Python e adicionar a variável do sistema em PATH.  

## Instalação do Python
Já considerando que você tenha alguma IDE, como o PyCharm ou o Visual Studio Code, você irá precisar instalar a extensão Python na sua IDE.
OBS.: Caso não tenha instalado nenhuma IDE, aconselho usar o VSCode, por ser mais versátil e amplamente utilizado. [Instale clicando aqui](https://code.visualstudio.com/download).  

Com o VSCode instalado, basta seguir as seguintes instruções:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/90ad5a5b-400e-4da5-b459-d4fe7aa833fe' alt='Interface do VSCode' >
  <p align='center'>Interface do VSCode</p>
</div>

Perceba na imagem e na sua IDE que você vai ter essa aba lateral esquerda com alguns botões.  
Olhando de cima a baixo, temos o 5º Elemento que gerencia extensões da sua IDE. Clique nesse ícone:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/44687794-a91c-457f-8da7-8529aed0aee6' alt='Botão que mostra as extensões da IDE' >
  <p align='center'>Botão que mostra as extensões da IDE</p>
</div>

Perceba que ao clicar no botão, temos uma nova aba listando algumas extensões. No topo da aba, temos uma caixa de pesquisa, procure por Python (Tem um selo da Microsoft embaixo).

<div align='center'>
  <img src='https://github.com/user-attachments/assets/8bbc6ee9-3ea0-45e0-8c1d-6a1c5aae7eb3' alt='Detalhes da extensão Python' >
  <p align='center'>Detalhes da extensão Python</p>
</div>

Uma janela maior se abre detalhando o que a extensão pode fazer. Como queremos escrever códigos em Python, ela se faz necessária. Para isso, basta apertar no botão Install.  
OBS.: Se alguma janela relatar algum erro de segurança, é uma janela indicando que é uma extensão e que se não for confiável, não é seguro instalar. Python é amplamente utilizado e a extensão tem o selo Microsoft. Se julgar seguro, basta apertar na segunda opção 'Install anyway'.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/bd2b26b7-5198-415c-87ab-ee219a3e0e31' alt='Alerta de verificação de assinatura durante instalação da extensão' >
  <p align='center'>Alerta de verificação de assinatura durante instalação da extensão</p>
</div>

Com isso, ainda falta você ter o Python instalado na sua máquina. Antes de instalar, verifique se o Python está instalado.
Para isso, abra o cmd do Windows e digite ou copie e cole o seguinte código:
```
python -V
```
<div align='center'>
  <img src='https://github.com/user-attachments/assets/e3b8435d-8a9f-47e7-82ff-e51b6e6f8658' alt='Comando para verificar a existência do Python em sua máquina digitado no prompt de comando do Windows' >
  <p align='center'>Comando para verificar a existência do Python em sua máquina digitado no prompt de comando do Windows</p>
</div>

Se gerar um erro, você não tem o Python na sua máquina.

## Contornando o problema da Microsoft Store
Você provavelmente já tentou instalar algo na Microsoft Store e deu algum erro, seja ao abrir a loja ou instalando algum aplicativo, certo?  
Infelizmente (ou felizmente), uma forma de contornar este problema é tentando baixar seus aplicativos pelo próprio navegador.  
OBS.: A Microsoft Store Web também não funcionaria se você estiver com este problema, visto que a instalação sempre redireciona o download para a Store instalada na máquina.  

Portanto, vá ao navegador e busque por uma versão do Python. A versão mais comum é a 3.11, que será instalada.
Cole o seguinte texto na barra de pesquisa:
```
python 3.11 download
```
Provavelmente o site do python.org aparecerá como primeira opção, mas se não foi o caso. Abra o site, [clicando aqui](https://www.python.org/downloads/release/python-3110/)

<div align='center'>
  <img src='https://github.com/user-attachments/assets/9df39b66-e142-4618-9e3c-38973633decc' alt='Primeiro resultado ao pesquisar no Google' >
  <p align='center'>Primeiro resultado ao pesquisar no Google</p>
</div>

Descendo toda a página, você verá as versões para instalar no computador. Considerando que você esteja no Windows, clique na opção Windows Installer (64-bit).  

<div align='center'>
  <img src='https://github.com/user-attachments/assets/5033af2a-fd21-400e-a31f-15e7106c57a7' alt='Opções de instalação do Python 3.11' >
  <p align='center'>Opções de instalação do Python 3.11</p>
</div>

Abra o arquivo e instale no computador.

## Adicionando Python como variável do sistema
Após instalar o Python, adicione ele como variável do sistema. Caso não tenha visto durante a instalação qual foi o caminho que o Python foi instalado, te guiarei até lá.  
1. Abra o Microsoft Explorer
2. Vá em Este Computador
3. Disco Local (C:)
4. Usuários
5. Abra seu usuário

<div align='center'>
  <img src='https://github.com/user-attachments/assets/7c2f8af8-6d6a-4361-9413-306034f26386' alt='Parte superior do explorador de arquivos' >
  <p align='center'>Parte superior do explorador de arquivos</p>
</div>


6. Clique em Exibir

<div align='center'>
  <img src='https://github.com/user-attachments/assets/6628c03f-fa8b-4de2-9202-25d9c00533fc' alt='Em Mostrar/ocultar, clique em "Itens ocultos"' >
  <p align='center'>Em Mostrar/ocultar, clique em "Itens ocultos"</p>
</div>

7. Marque a opção "Itens Ocultos"
8. Agora, você verá pastas ocultas, procure pela pasta AppData no seu usuário.
9. Local
10. Programs
11. Python
12. Python311

<div align='center'>
  <img src='https://github.com/user-attachments/assets/68846fc0-5c8a-4567-8a31-d77d27d1b59b' alt='Clique nesse caminho e copie ele com [CTRL] + [C]' >
  <p align='center'>Clique nesse caminho e copie ele com [CTRL] + [C]</p>
</div>


Agora, vamos adicionar este caminho como variável.
Digite "var" no menu iniciar e abra a opção de editar variáveis de ambiente do sistema.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/a4b3887b-0cb2-4b55-947a-cdb7c52f54ee' alt='Primeiro resultado ao digitar "var" no menu iniciar' >
  <p align='center'>Primeiro resultado ao digitar "var" no menu iniciar</p>
</div>

Neste momento, você precisa de permissão de administrador. Contate algum administrador, caso você não seja um, solicitando essa permissão.
Após isso, clique no botão inferior direito "Variáveis do Ambiente..."
<div align='center'>
  <img src='https://github.com/user-attachments/assets/0081c39b-8e60-429a-84ab-5b5ba5dcc3d9' alt='Ao clicar em Variáveis do Ambiente, temos essas duas janelas' >
  <p align='center'>Ao clicar em Variáveis do Ambiente, temos essas duas janelas</p>
</div>

Você tem variáveis de usuário e as variáveis do sistema. No caso, procure por Path em Variáveis do sistema e clique duas vezes nele.  
Clique em uma linha em branco e cole aquele caminho que leva até o Python que você copiou anteriormente.
Aperte OK em todas as janelas.

## Verificando se a instalação foi feita com sucesso
Agora você pode abrir o cmd e digitar ou copiar o seguinte código:  
```
python -V
```
Agora, você deve estar vendo a versão do python sendo exibida pelo prompt de comando.
<div align='center'>
  <img src='https://github.com/user-attachments/assets/dd3648bb-f9fb-4200-91cb-6fb383e75138' alt='Prompt de comando exibindo a versão do Python corretamente' >
  <p align='center'>Prompt de comando exibindo a versão do Python corretamente</p>
</div>

Recomendo que feche o VSCode e abra novamente.

Uma tradição dos programadores é começar escrevendo o primeiro código que imprima "Hello World!" ou "Olá, mundo!" para dar sorte no aprendizado. Siga a tradição para ser um mestre em Python.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/d076a2d8-6f49-4074-b45b-a872bc398bf0' alt='Famoso Hello World! (Olá, mundo!) printado no console do VSCode' >
  <p align='center'>Famoso Hello World! (Olá, mundo!) printado no console do VSCode</p>
</div>

<br>

## C e C++ <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=c" width ="30" height="30" /> <a href="https://skillicons.dev"> <img src="https://skillicons.dev/icons?i=cpp" width ="30" height="30" />
C/C++ é uma linguagem compilada.
Para C ou C++, ao invés de instalar o Python, você vai procurar por
```
mingw download
```
Ou simplesmente, abra [esse site](https://sourceforge.net/projects/mingw/)

<div align='center'>
  <img src='https://github.com/user-attachments/assets/d8297b44-f446-4915-8c6c-60f94ff57374' alt='Página de instalação do MinGW' >
  <p align='center'>Página de instalação do MinGW</p>
</div>

Aperte download e instale o software no "Padrão Windows": Next, Next, Next, Install.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/e35d4185-34d9-400a-a67a-cad521d7f3b2' alt='Para usar C/C++, selecione as opções mingw32-base junto com mingw32-gcc-g++. Caso queira programar em fortran, ada ou quiser uma instalação completa, marque as outras opções que desejar' >
  <p align='center'>Para usar C/C++, selecione as opções mingw32-base junto com mingw32-gcc-g++. Caso queira programar em Fortran, Ada ou quiser uma instalação completa, marque as outras opções que desejar</p>
</div>

Após isso, vá em Installation e aperte na opção "Apply Changes", seguido de um "Apply" na nova janela.

Por fim, basta adicionar o caminho da instalação como variável de ambiente.  
Para esta instalação, o caminho que o MinGW é instalado, caso não tenha sido alterado durante a instalação é o:
```
C:\MinGW\bin
```
Basta copiar este caminho e colocar como variável do ambiente.

<div align='center'>
  <img src='https://github.com/user-attachments/assets/3cfbb672-5a1b-426e-bff3-564938f7b736' alt='Adicionando caminho como variável de ambiente. Lembre que esse caminho deve ser adicionado em "Path" e em "Variáveis do Sistema"' >
  <p align='center'>Adicionando caminho como variável de ambiente. Lembre que esse caminho deve ser adicionado em "Path" e em "Variáveis do Sistema"</p>
</div>

## Extensões essenciais C/C++
Partindo para o VSCode, em extensões podemos instalar algumas que te auxiliarão enquanto programa em C/C++.  
1. C/C++:
<div align='center'>
  <img src='https://github.com/user-attachments/assets/40e1e264-0f14-4567-9a87-a832c8620cbc' alt='Primeira extensão do VSCode. Ela te auxiliará com o intelliSense, sugerindo estruturas e preenchendo automaticamente seu código à medida que você digita' >
  <p align='center'>Primeira extensão do VSCode. Ela te auxiliará com o intelliSense, sugerindo estruturas e preenchendo automaticamente seu código à medida que você digita</p>
</div>

2. C/C++ Compile Run
<div align='center'>
  <img src='https://github.com/user-attachments/assets/e9fa1e53-c2ea-49fe-b052-1b08e34cca36' alt='Segunda extensão do VSCode. Ela te permite executar seu código C/C++ com a tecla [F6] ou apertando o botão '<img src='https://github.com/user-attachments/assets/ca5bfce4-00f8-42c5-b0e9-e56042709dc3' width='' height=''>
  <p align='center'>Segunda extensão do VSCode. Ela te permite executar seu código C/C++ com a tecla [F6] ou apertando o botão <img src='https://github.com/user-attachments/assets/ca5bfce4-00f8-42c5-b0e9-e56042709dc3'> </p>
</div>

## Verificando instalação C/C++
Para verificar se o compilador do C/C++ está funcionando corretamente, podemos dentro do prompt de comando escrever o seguinte comando:
```
gcc --version
```
Se o comando exibir alguma versão, o compilador C está funcionando corretamente.  
Além disso, escreva no prompt de comando:
```
g++ --version
```
Assim como o comando anterior, se exibiu alguma versão significa que o compilador C++ está funcionando corretamente.  

## Hello World C/C++
Não se esqueça de seguir a tradição de todo programador e executar o famoso "Hello World!". Se você conseguiu seguir os passos até aqui, terá o resultado corretamente printado no terminal.
<div align='center'>
  <img src='https://github.com/user-attachments/assets/da0ae24b-38e2-4eae-b52a-0bac77ae2452' alt='Hello World em C++' width='' height=''>
  <p align='center'>Hello World em C++</p>
</div>

Dica: Para outras linguagens, é basicamente o mesmo procedimento, basta apenas buscar o instalador necessário para a linguagem e extensões para adicionar na IDE que podem te auxiliar a programar em C#, Rust, Java etc.  
<br>
<img src="https://github.com/user-attachments/assets/b4567a73-8d99-4be1-81bb-a3c826446a81" alt="computer-cat" width="60" height="35">

Good Luck and Happy Coding!
