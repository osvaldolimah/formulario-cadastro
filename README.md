Formulário de Cadastro criado com React e Styled Component.

C - Create/Criar
R
U
D

O Formulário fará uma requisição para API, e esta API deve salvar os dados do usuário no banco de dados, e retornar o estado, se conseguiu cadastrar corretamente ou não.

1. Inicio criando a aplicação com:

npx create-next-app 

2. No arquivo index.js criei o formulário com a tag form. Dentro da tag form coloco a tag label, para indicar o que o usuario deve preencher. 
Também dentro da tag form, crio a tag input, que será o campo que o usuario deve preencher. 
Tambem crio a o botão de enviar os dados com a tag buttom, com o tipo submit.

3. Para receber os dados do formulario, criei uma constante utilizando o usestate
const [data, setData] = useState({
    'name': '',
    'email: ''
})
    onde data possui os dados e setData para quando for seta-los. Dentro de useState terá um objeto, com nome na primeira posição e email na segunda, com os valores vazios.
    Quando o usuario abrir a pagina, cria um objeto com os campos vazios. 

4. 


