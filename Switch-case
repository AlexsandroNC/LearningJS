const valor1 = 15;
const valor2 = 3;

const operacao = '/';

function calcular(v1, v2, op) {
  let resultado;

  switch (op) {
    case '+':
      resultado = v1 + v2;
      break;
    case '-':
      resultado = v1 - v2;
      break;
    case '*':
      resultado = v1 * v2;
      break;
    case '/':
      if (v2 !== 0) {
        resultado = v1 / v2;
      } else {
        return 'Erro: divisão por zero!';
      }
      break;
    default:
      return 'Operação inválida!';
  }

  return `Resultado: ${v1} ${op} ${v2} = ${resultado}`;
}

console.log(calcular(valor1, valor2, operacao));
