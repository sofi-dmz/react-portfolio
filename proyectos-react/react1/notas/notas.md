##Aprendiendo React

#Creando Componentes 

function MyButton() {
  return (
    <button>I'm a button</button>
  );
}

Un componente  es un funcion de Javascript que retorna marcada (markup "html")

Una vez que creamos ese componente lo anidamos en otro (a MyButton lo ponemos dentro de MyApp)

export default function MyApp() {
  return (
    <div>
      <h1>Welcome to my app</h1>
      <h2>This is my app and this is subtle</h2>
      <MyButton />
    </div>
  );
}