# > Node Estudos 🤓 <  

## 📚 Dependências utilizadas:
**🥊 lefthook**: Biblioteca utilizada com a finalidade de rodar determinados scripts de verificação antes de <mark>commits e push's</mark>.    

**biome**: Biblioteca utilizada com a finalidade de integrar o processo de _code linting_, assim como a formatação.  

**jest**: Biblioteca utilizada para realização e conferência dos **testes**.  

**typescript**: _Superset_ do JavaScript que ganhou muita notoridade e importância pelo seu papel fundamental na manutenção da coerência do código, assim como prevenção e detecção de erros de tipagem.

## 🧑🏻‍💻 Clean Code Architecture:

Visa romper o paradigma onde o componente é o **"faz-tudo"** do sistema, invertendo e desacoplando os componentes centrais das suas bibliotecas e frameworks de dependências, _e.g._:

> Assuma que você possui um componente central "Sign up Ctrl"
  
> Você decide utilizar um framework como o Express para a codificação, mas, o quê aconteceria com todo seu sistema caso o Express deixasse de existir?  

> É a partir dessa ideia que a visão do Clean Code Architecture ganha força, inverter a dependência, através de um mediador, de forma que se um dia for necessário, é possível trocar até mesmo o _framework_ utilizado no projeto!