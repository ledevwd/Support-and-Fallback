# Fornecendo favicons para diferentes tipos de telas e navegadores
A adição dos ícones geralmente são colocadas na mesma ordem em que estão neste documento
para que o navegador possa escolher o ícone mais apropriado para o dispositivo, dependendo
de suas necessidades usando os respectivos atributos `media`, `type` e `sizes`. Os tamanhos
usados nos favicons são comuns e estão sujeitos as variações do seu projeto.

## iPad de terceira geração com tela Retina de alta resolução:
Favicon (144x144 ou 258x258).
```css
<link rel="apple-touch-icon" sizes="144x144" href=".../img/favicon144.png" />
```
## iPhone com tela Retina de alta resolução:
Favicon (114x114).
```css
<link rel="apple-touch-icon" sizes="114x114" href=".../img/favicon114.png" />
```
## iPad de primeira e segunda geração:
Favicon (72x72).
```css
<link rel="apple-touch-icon" sizes="72x72" href=".../img/favicon72.png" />
```
## Dispositivos não Retina iPhone, iPod Touch e Android 2.1+:
Favicon (57x57 ou 64x64).
```css
<link rel="apple-touch-icon" href=".../img/favicon57.png" />
```
## Favicon antigo
Favicon (32x32 ou 196x196) e usando o formato .ico.
```css
<link rel="shortcut icon" type="image/x-icon" href=".../img/favicon32.ico" />
```
## Favicon básico
Favicon (32x32) e usando o formato .png, .jpg, .svg...
```css
<link rel="icon" href=".../img/favicon32.png" />
```
