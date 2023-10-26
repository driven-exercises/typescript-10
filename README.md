# typescript-10: Identify Yourself

- A função `identity()` abaixo funciona somente com números.
    
    ```tsx
    function identity (value: Number) : Number {
        return value;
    }
    
    console.log(identity(1)) // 1
    ```
    
- Utilizando Generics, generalize para que funcione como a imagem abaixo:
    
    ```tsx
    console.log(identity<number>(42)); // 42
    console.log(identity<string>("Hello")); // Hello
    console.log(identity<number[]>([1,2,3])); // [1, 2, 3]
    ```
    

### Como rodar
- Instale as dependências com o comando `npm i`.
- Rode o comando `npm run dev` e veja os resultados no terminal.