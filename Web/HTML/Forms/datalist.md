# Para navegadores que não suportam &lt;datalist&gt;

```js
<label for="carText">Qual marca de carro você mais gosta?</label>
<input type="text" id="carText" name="carText" list="carAutocompleteList">

<datalist id="carAutocompleteList">
    <label for="carSelectionList">ou selecione:</label>
    <select id="carSelectionList" name="carSelectionList">
        <option>Toyota</option>
        <option>Honda</option>
        <option>Nissan</option>
        <option>Hyundai</option>
        <option>Volkswagen</option>
        <option>Ford</option>
    </select>
</datalist>
```
Atualmente todos os navegadores suportam o elemento `<datalist>` e o código acima não vai causar problemas ao implementar em seu projeto
já que implicitamente o navegador vai corrigir a marcação errada, no entanto você pode notar que ao enviar o formulário será adicionado
o conjunto de parâmetro e valor (ex: `carSelectionList=Toyota`) na URL. Já em navegadores mais antigo o mesmo irá ignorar o `<datalist>`,
mas em compensação será exibido tanto o campo de texto e caixa de seleção.
