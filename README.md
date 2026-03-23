const calc = (a, b, op) =>
  op === "+" ? a + b :
  op === "-" ? a - b :
  op === "*" ? a * b :
  op === "/" ? (b === 0 ? "erro" : a / b) :
  "inválido";

console.log(calc(10, 2, "+"));