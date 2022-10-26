# Render and props

 `function Welcome(props) {  
	return <h1>Hello, {props.name}</h1>;
}

const root = ReactDOM.createRoot(document.getElementById('root'));
const element = <Welcome name="Sara" />;
root.render(element);

root creates document 
root.render passes element to Welcome function 
Welcome function passes name="Sara" as a prop 
Welcome function returns <h1> Hello, {props.name} </h1>; // props.name is important to be able to read the variable or the value of the variable 
displays Hello, Sara`

## Plain template of what a react file should look like

 `import React from 'react';

class App extends React.Component {
	render() {
		<>  // Frag; placeholder until real code is added in
		</>
	}
}

export default App; // used to pass component to other component`
