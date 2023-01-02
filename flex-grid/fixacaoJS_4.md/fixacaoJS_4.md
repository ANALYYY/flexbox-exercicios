
  const arrayDeNumeros = [1,4,8,2,5,4,10,1,2,4,7,5];

  function contaOcorrencias(arrayDeNumeros, numeroEscolhido) {
      let novoArray = [];
      if(arrayDeNumeros.includes(numeroEscolhido)){
          for(let i in arrayDeNumeros){
              if(arrayDeNumeros[i] === numeroEscolhido){
                  novoArray.push(numeroEscolhido)
              }
          }
          console.log(`O número ${numeroEscolhido} aparece ${novoArray.length}X`);
      }else{
          return (`Número não encontrado`)
      }
  }
    console.log(contaOcorrencias(arrayDeNumeros,4));