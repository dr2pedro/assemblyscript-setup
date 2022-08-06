# assemblyscript-setup

Na pasta `assembly` existe um `index.ts` que deve conter tudo o que precisa ser compilado. Não mexa na pasta `build` caso não vá finalizar o pacote para uso. Trabalhe com a pasta testes, que é em javascript dado que ele utiliza o `./build/release.js`, e teste toda a sua aplicação para produção. Por enquanto os testes são apenas os casos de uso, caso precise de um setup de testes dê preferência para o `node:test`.

